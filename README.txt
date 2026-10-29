SAHU CONSTRUCTION HAJIRI REGISTER - FIRST VERSION

FILES
- index.html: app UI and local data logic
- manifest.webmanifest: installable PWA metadata
- sw.js: offline app-shell cache
- icon.svg: app icon

HOW TO USE
1. Upload the contents of this folder to a static HTTPS host (GitHub Pages works).
2. Open the hosted index.html link in Chrome on Android.
3. First open while online, then use Chrome menu > Add to Home screen / Install app.
4. Add workers, mark attendance, and record payments/advances.
5. Download JSON backup regularly, especially before clearing browser data or changing phones.

DATA
- Worker records, attendance, and transactions are stored in localStorage on this browser/device.
- The app does not send data to a server and does not require internet for normal use after first load and offline cache installation.
- Importing a backup replaces current data and asks for confirmation.
- Existing attendance for the same date is never overwritten silently; confirmation is required.

IMPORTANT LIMITATION
This first version uses local browser storage, not cloud sync. Browser data clearing, uninstalling/clearing site data, or device loss can erase records. Download backups frequently and test restore with a copy before relying on it for official accounts.
