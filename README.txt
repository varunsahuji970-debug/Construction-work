SAHU CONSTRUCTION HAJIRI REGISTER - WEEKLY CHART + ADVANCE UPDATE

FILES
- index.html: app UI and local data logic
- manifest.webmanifest: installable PWA metadata
- sw.js: offline app-shell cache (updated for this release)
- icon.svg: app icon

HOW TO USE
1. Upload all files in this folder to your existing HTTPS GitHub Pages repository.
2. Keep the existing localStorage key and do not clear browser/site data; this update is designed to keep existing workers, sites, attendance, and payments on the same device.
3. Add sites from Dashboard > Site Management and add workers from the Mazdoor tab.
4. Open the “7 दिन” tab, choose a site and week starting date. The date is aligned to Monday.
5. Mark each day P (Present), A (Absent), or H (Half-day), then tap “7 दिन का चार्ट सेव करें”. Existing records prompt for confirmation; only workers shown in the chart are updated.
6. To record an advance directly from the weekly chart, enter the amount in that worker row and tap “+ दर्ज”. It appears in that week's advance column. For an older week, enter a date within the selected week when prompted.
7. Use the Paid checkbox at the end of each row to mark that worker's weekly payment status. Download the weekly chart as CSV if needed.
8. Download a JSON backup regularly, especially before clearing browser data or changing phones.

DATA AND SAFETY
- Data is stored locally in the browser on this device and works offline after the app has loaded online once.
- The update keeps the existing local storage key and adds weekly paid/unpaid status without intentionally replacing existing records.
- Saving a weekly chart asks for confirmation if any records already exist in that site/week; it updates only the workers shown in the chart and preserves other workers' entries.
- Browser data clearing, uninstalling/clearing site data, or device loss can erase records. Download backups frequently.
