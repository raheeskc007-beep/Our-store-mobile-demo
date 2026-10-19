BUYBIT PWA v1 — existing prototype packaged for installable web testing

FILES
- index.html: current BUYBIT prototype
- manifest.json: app name, theme, install display and icons
- sw.js: basic app-shell/offline caching
- icon-192.png and icon-512.png: BUYBIT wordmark icons

TESTING
1. Extract this ZIP.
2. Upload all five files together to the same HTTPS hosting folder (for example, the existing GitHub Pages repository). Keep index.html at the folder root.
3. Open the HTTPS site on your phone and use the browser's Add to Home Screen option.
4. Open once while online before testing offline mode.

NOTES
- This is a PWA test package, not an Android APK or an App Store submission build.
- Offline mode caches the app shell. Live product images or external resources may still need internet.
- The prototype's checkout/payment and order data remain demo behavior unless connected to a real backend/payment provider.
