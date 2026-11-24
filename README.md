# Stillword — Offline Bible Study

A privacy-first Bible study web app with chapter tracking across all 66 books, a personal study journal, a 30-day reading plan, and a structured **Life of Christ: 90-day study** curriculum for January–March 2027.

## Study curriculum

Each of the 90 lessons presents a date, study topic, Scripture reading and memory-verse reference. Read the passage, reflect on the lesson theme, record personal insights, practical applications and prayers, then mark the lesson complete. Study at your own pace.

The curriculum is integrated into the app and does not require importing supplementary materials.

## Run

Open `index.html` directly to use it locally. For a hosted web experience, deploy it through GitHub Pages. No account, backend API or internet connection is needed for the core functions once the app files are available locally.

## Data and privacy

Reading progress and notes are saved in browser `localStorage` under `stillword.v1`. Export JSON backups periodically and restore them on another device if needed. Data is not automatically synchronized across devices, and browser storage can be erased if site data is cleared.

## GitHub Pages

In repository Settings → Pages, choose Deploy from a branch, then `main` and `/ (root)`. The site URL will be https://thousands-maker.github.io/stillword-bible-study/ once Pages is successfully deployed.

## Bible text

The app includes a Bible chapter tracker, not the complete text of all 1,189 chapters.
