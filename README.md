# ROOT — Rooted in the Word

A beginner-friendly, static Bible reading and study planner designed for GitHub Pages.

## Included features
- Botanical ROOT dashboard and navigation
- Bible chapter tracker for all 66 books (1,189 chapters)
- Personal reading schedule
- R.O.O.T. Bible study journal: Read, Observe, Understand, Transform
- Prayer journal with status tracking
- Scripture library with topic categories
- Daily reflection journal
- Growth overview and personal goals
- Local data storage in the browser
- JSON backup export and import
- Installable PWA shell and offline caching

## Publish on GitHub Pages
1. Download and unzip `root-bible-planner-github.zip`.
2. Create a new GitHub repository named `root-bible-planner` (Public is simplest for GitHub Pages).
3. Upload the seven files and folders' contents directly into the repository root. `index.html` must be at the top level, not inside another folder.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then Save.
7. Wait for GitHub to publish the site. Open the URL shown in the Pages section.

## Important notes
- Entries are saved in the browser on the device where you use the app. They are not automatically synced between devices or browsers.
- Use **My Growth → Export my ROOT data** regularly to download a backup. Use **Import backup** to restore it.
- The first visit needs an internet connection to load the page. After the app has been cached, its core files can work offline.
- The Google Fonts import is an optional online enhancement. If offline, the app uses fallback fonts.
- Bible passage references are provided as a place to record your reading. This app does not include a copyrighted Bible text or choose a Bible translation for you.

## Updating later
When replacing files, keep the filenames unchanged. If the service worker cache needs refreshing after a future code update, increment the cache name in `service-worker.js` (for example, `root-bible-planner-v2`).
