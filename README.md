# MY LIFE PWA v1.1

A free, offline-capable personal iPhone PWA using HTML, CSS, vanilla JavaScript and browser localStorage. No backend or account required.

## Features
- Home dashboard and quick actions
- AED expenses with categories, dates and deletion
- Monthly budgets, spending totals and progress bar
- Date-wise daily planner with completion tracking
- Travel destinations, dates and budgets
- Activity reminders: date, time, category, repeat (daily/weekly/monthly/yearly), edit, dismiss, and delete
- In-app due alerts while the app is open (no background push notifications)
- JSON backup export/import
- Installable PWA manifest and offline service worker

## Publish for free
1. Create a GitHub repository and upload the contents of this folder to the repository root.
2. In repository Settings → Pages, choose **Deploy from a branch**, branch `main`, folder `/ (root)` and Save.
3. Wait for the HTTPS GitHub Pages URL to become available.
4. On iPhone, open the HTTPS URL in **Safari**, tap **Share**, then **Add to Home Screen** and **Add**. On some iOS versions choose **Open as Web App** if shown.

For local desktop testing, run `python -m http.server 8000` from this folder and open http://localhost:8000. Service workers require HTTPS or localhost.

## Privacy and limits
Data is saved only in the current browser/device storage. Clearing Safari website data, changing device or deleting website storage may permanently remove data. Use Settings → Export backup regularly and store backups safely. Import replaces all current records. No account sync or automatic cloud backup. The app is not a secure password vault and does not include HealthKit, background push notifications, live travel booking, or investments in v1.


## Version 1.2: Travel departure alerts
When adding a trip, select the departure date and local departure time. The app automatically displays a reminder 2 hours before that time, including when the reminder falls on the previous calendar day. Existing trips without a departure time remain unchanged; add a new trip with time to use this feature. The reminder is displayed only while the app is open (or when reopened after the alert time). It is NOT a reliable background alarm and cannot guarantee an audible alert while the phone is locked. For important flights also use iPhone Clock or Calendar alarms.
