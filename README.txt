Private Browser — PWA files

Files:
- index.html: your existing app with minimal PWA additions
- manifest.json: app name, standalone display mode, and icons
- service-worker.js: caches the app shell for repeat/offline launch
- icons/: app icons

Important:
1. These files do not install themselves. A PWA normally needs to be served from HTTPS (or localhost for development).
2. Upload/hosting may be subject to school rules. Do not publish it publicly if it contains private information.
3. On the Chromebook, open the HTTPS page in Chrome and check the menu for an install option. If blocked or absent, ask the school administrator.
4. "standalone" means a separate app window, not a browser engine independent of Chrome.
5. The current app's iframe may not display websites that prohibit embedding. This package does not bypass those restrictions.
