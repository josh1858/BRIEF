BA EFW PWA package

Files:
- index.html: app
- manifest.webmanifest: PWA manifest
- sw.js: service worker for offline app shell
- icons/: install icons

How to use:
1. Upload this folder to any HTTPS web hosting, or test locally with: python3 -m http.server 8000
2. Open the site in Chrome/Edge/Safari.
3. Use the browser Install/Add to Home Screen option.

Note: PWA install and service workers do not run from a file:// URL. Live weather requires internet; the briefing form and embedded airport list work offline after first load.
