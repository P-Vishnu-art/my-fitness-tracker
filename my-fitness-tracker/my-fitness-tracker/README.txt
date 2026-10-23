MY FITNESS TRACKER — PHONE SETUP

Files
- index.html: the tracker
- manifest.json: installable-app details
- sw.js: offline caching
- icon.svg, icon-192.png, icon-512.png: app icons

RECOMMENDED: PUBLISH WITH GITHUB PAGES
1. On your laptop, sign in to GitHub and create a new public repository named my-fitness-tracker.
2. Extract the ZIP, then upload all the files inside the my-fitness-tracker folder to the repository root (including index.html, manifest.json, sw.js, and all three icon files). Do not upload only the ZIP.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, then select branch main and folder /(root), then Save.
5. Wait for GitHub Pages to publish. The website URL will look like https://YOUR-USERNAME.github.io/my-fitness-tracker/ (replace YOUR-USERNAME with your GitHub username).
6. Open that URL on your phone.
   - Android (Chrome): browser menu ⋮ → Install app or Add to Home screen.
   - iPhone (Safari): Share button → Add to Home Screen.
7. Open it from the new home-screen icon. Load it once while online; after the service worker caches the files, the tracker can work offline.

TRACKING / PRIVACY
- Checkmarks are saved locally in the browser on the device where you use the tracker.
- Phone and laptop progress will not automatically sync with each other.
- Clearing the browser's site data may erase the saved tracker data.
- Use “Export my progress” in the app to download a JSON backup.
- The app uses no account and sends no workout data to a server.

NOTE
You can test index.html on your laptop by opening it in your browser, but installation and offline caching require the site to be served over HTTPS (GitHub Pages provides HTTPS).
