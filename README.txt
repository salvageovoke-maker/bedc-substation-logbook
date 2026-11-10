BEDC SUBSTATION LOGBOOK: FINAL PWA PACKAGE

Files:
- index.html: Final application (Version 8, Monthly Report)
- manifest.webmanifest: App name, display settings and icon definitions
- service-worker.js: Offline app-shell caching
- icon-192.png: Standard 192 x 192 launcher/PWA icon
- icon-512.png: Standard 512 x 512 launcher/PWA icon
- icon-512-maskable.png: Android maskable launcher icon

DEPLOYMENT
1. Upload all files in this ZIP to the root of your GitHub repository.
2. Keep the file names and their root-level locations unchanged.
3. Enable GitHub Pages for the intended branch and root folder.
4. Open the deployed HTTPS website in Chrome on Android.
5. Allow it to load online once, then use Chrome's Install app / Add to Home screen option.

IMPORTANT
- PWA installation and service workers require HTTPS (GitHub Pages provides HTTPS).
- The app stores operational data in browser localStorage on the device/profile. It does not synchronise between devices.
- Do not clear the site's browser storage if you need to retain records.
- The GitHub repository contains the app source and icons. Do not place operational records or confidential utility data in the repository.
- If updating an already installed PWA, upload the new files and reopen the app online. If an old cached version remains, close the app fully and reopen after the service worker updates.
