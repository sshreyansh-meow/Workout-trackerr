GYM TRACKER — PWA FILES

Files:
- index.html: your existing tracker with PWA metadata/registration added
- manifest.json: installable app settings
- sw.js: caches the app shell so it can open offline after the first successful load
- icons/: app icons

IMPORTANT:
1. These files do not automatically move data from the old Acode/browser location.
2. Before switching, open your old tracker, tap the 💾 backup button, and copy/save the backup code somewhere safe.
3. After the hosted PWA is opened, use 📂 Restore and paste the backup code to bring your routines/history over.
4. Chart.js is loaded from a CDN, so charts may need internet; the rest of the app shell can open offline after it has been cached.
5. PWA installation requires an HTTPS website. Keep the GitHub repository private if you want; this ZIP alone is not hosting.
