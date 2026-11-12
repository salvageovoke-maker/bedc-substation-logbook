BEDC SUBSTATION LOGBOOK: FINAL PWA PACKAGE
Version: 21.1

PACKAGE CONTENTS
- index.html: Complete BEDC Substation Logbook application.
- manifest.webmanifest: PWA name, display settings and icon definitions.
- service-worker.js: Offline app-shell caching.
- icon-192.png: Original 192 x 192 launcher/PWA icon.
- icon-512.png: Original 512 x 512 launcher/PWA icon.
- icon-512-maskable.png: Original Android maskable launcher icon.

The approved BEDC logo and icon artwork from the previous package have been retained.

DEPLOYMENT
1. Extract all files in this ZIP.
2. Upload all files to the root of the GitHub repository, replacing the previous application files.
3. Keep the filenames and root-level locations unchanged.
4. Enable GitHub Pages for the intended branch and root folder.
5. Open the deployed HTTPS website in Chrome on Android.
6. Reopen the installed app while online so the updated service worker can install the new version.

DATA PRESERVATION
- The app stores operational records in browser localStorage on the device/profile.
- This package retains the existing application storage keys. Updating the app at the same GitHub Pages address should preserve existing records.
- Do not clear the site's browser storage or uninstall the installed app as an update step.
- Export a backup before deployment as a precaution.
- PIN hashes and recovery credentials remain device-local and are not included in operational backups.

IMPORTANT
- PWA installation and service workers require HTTPS. GitHub Pages provides HTTPS.
- The app does not synchronise operational data between devices.
- Do not commit operational records or confidential utility data to the GitHub repository.
