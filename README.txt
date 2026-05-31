FinTrack — Personal Finance App
================================

Files included:
  index.html      — Main application file
  manifest.json   — PWA Web App Manifest
  sw.js           — Service Worker (offline support)
  icon-48.png     — App icon 48x48
  icon-72.png     — App icon 72x72
  icon-96.png     — App icon 96x96
  icon-144.png    — App icon 144x144
  icon-192.png    — App icon 192x192 (primary / maskable)
  icon-512.png    — App icon 512x512 (splash / store)

How to convert to APK using html2app / WebIntoApp / GoNative etc.:
--------------------------------------------------------------------
1. Upload ALL files from this zip keeping them in the same folder.
2. Set the entry point / start URL to: index.html
3. Use the manifest.json for app name, theme colour, and icons.
4. App name:         FinTrack — Personal Finance
5. Package name:     com.fintrack.personalfinance
6. Version:          1.0.0
7. Theme colour:     #0a0a0f
8. Background:       #0a0a0f
9. Orientation:      Portrait
10. Min SDK:         API 21 (Android 5.0+)

Recommended html2app settings:
  - Enable JavaScript: YES
  - Allow localStorage: YES (app data is stored here)
  - Status bar style: dark / black-translucent
  - Splash screen colour: #0a0a0f
  - Use icon-512.png for splash and Play Store listing
  - Use icon-192.png as the launcher icon
