# Stillword — Offline Bible Study

A privacy-first, static offline Bible study app with Bible chapter tracking, study journal, 30-day reading plan and a **Read Pray Grow (RPG) January–March 2027** devotional companion.

## Run

Open `index.html` locally; for a reliable installable PWA and offline caching, deploy the files to HTTPS (e.g. GitHub Pages) or serve via `python -m http.server 8000`. No server API and no user accounts.

## Devotional PDF

This repository includes **only the date index, titles, Scripture references and memory-verse references** for the user-provided 2027 Q1 RPG booklet, not its full copyrighted commentary. Import your own copy of `27_01jan-mar.pdf` via **Daily devotional → Import your PDF**. The file is stored in the browser's IndexedDB, not sent to a server. The browser's PDF reader may not honour the `#page=` target on all devices.

## Data and privacy

Reading progress and notes live in `localStorage` under `stillword.v1` (retained for compatibility with v1). The devotional PDF is stored in IndexedDB. The JSON backup includes study progress and devotional notes, but **not** the PDF file. Use one backup per browser profile, and reimport your booklet after switching devices. Browser storage can be removed by site data clearing or private browsing. No cloud synchronization.

## GitHub Pages

Push the app files to the root of a new GitHub repository (such as `stillword-bible-study`), then configure Settings → Pages → Deploy from branch → main / root. Do not push personal backup files or the devotional PDF without permission from the publisher.