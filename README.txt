# VideoHub Pro — Android-first PWA starter

## What is included
- Responsive VideoHub Pro website app.
- 11 interface languages (English, Urdu, Arabic, Spanish, French, Hindi, Simplified Chinese, Portuguese, Bengali, German and Turkish).
- Local video library stored in the browser using IndexedDB.
- Playback, search, favorites and remove controls.
- Social-platform link recognition for Facebook, YouTube, Instagram, TikTok, X, Vimeo and Dailymotion.
- Offline app shell and installable PWA manifest/service worker.

## Important limitations
This is a static PWA starter, not a native Android APK, hosted website, backend, or social-media downloader. Platform link recognition does not grant download permission. It does not bypass login, DRM, paywalls, privacy settings or platform restrictions. Use official export/download tools and only content you own or have permission to use.

## Publish free using GitHub Pages (Android phone)
1. Extract this ZIP on your phone.
2. Sign in to GitHub and create a new public repository named `videohub-pro`.
3. Upload all files from this folder to the repository root (index.html, manifest.json, sw.js, icon-192.png, icon-512.png).
4. In repository Settings → Pages, choose Deploy from a branch, select `main` and `/root`, then Save.
5. Wait for GitHub Pages to publish the site. Open the provided HTTPS URL in Chrome.
6. In Chrome menu, choose Install app or Add to Home screen.

PWA installation requires HTTPS hosting (or localhost). Opening index.html directly from Downloads can test the interface, but service-worker/offline install features require a hosted HTTPS URL.

## Storage
Videos are stored locally in this browser on this device. Browser cleanup, clearing site data, or uninstalling/resetting the browser may remove them. Keep backups of important originals.
