TS PERSONAL OS — ANDROID APP / PWA

Files:
- index.html       Main TS app
- manifest.json    App name, icon and install settings
- sw.js            Offline/app-shell support
- icons/           TS app icon files

IMPORTANT:
Do not open index.html directly from your phone if you want the Install App option.
Upload ALL these files/folders to the ROOT of your GitHub Pages repository.

Recommended GitHub Pages structure:
repo/
  index.html
  manifest.json
  sw.js
  icons/
    icon-192.png
    icon-512.png
    favicon-64.png

Then open the GitHub Pages website in Chrome on Android.
Use Chrome menu -> Add to Home screen / Install app.
The custom cherry-blossom icon is supplied by manifest.json.

If Chrome still shows an old icon after an update, remove the old TS shortcut/app,
clear the site's cached data if necessary, reload the GitHub Pages site, and install again.
