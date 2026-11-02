# Renaissance Founder Academy OS

A mobile-first, installable Progressive Web App for the 12-school Renaissance Founder Academy.

## Features
- Complete 12-school curriculum with departments and topic-level tracking
- Topic statuses: Not started, Learning, Practicing, Applied, Revision, Mastered
- Topic notes and next actions
- Daily tasks with due dates, priority, school association and completion
- Study session logging
- Practical founder projects
- Analytics by school, mastery status, study hours and task completion
- JSON backup export and import (Backup / Restore controls)
- Local-first storage; no account or server required for the basic version

## Run locally
Open `index.html` in a modern browser. For full PWA installation and offline caching, serve the folder over HTTPS or localhost.

## Install on Android
1. Upload the contents of this folder to an HTTPS static host (for example GitHub Pages, Netlify or Cloudflare Pages).
2. Open the hosted URL in Chrome on Android.
3. Open Chrome menu → **Install app** or **Add to Home screen**.
4. Launch **Renaissance Founder OS** from your home screen.

## Data and privacy
The app stores progress, tasks, notes, sessions and projects in this browser's localStorage. Data remains on the device/browser profile. Use **Backup** regularly. Clearing browser data can erase the app's local data. Exported JSON files contain your learning records; keep them private.

## Important limitations
This is a PWA, not a signed native APK. It can be installed on Android from an HTTPS host. Multi-device sync, user accounts, cloud backup, notifications and AI tutoring are not included in this first release.
