# Pixel Live Translate: releases

The public update channel for the Pixel Live Translate Android app (`com.dali.translator`). The source code is private.

- `latest.json` is the newest app version. The app checks it on start (at most every 6 hours) and offers the update. The APK itself is attached to the GitHub Release `v<version>`.
- `lessons/` holds the live-call lesson packs: `catalog.json`, `packs/*.json` and the scenario card `templates/`. The app downloads packs that are newer than the ones on the phone (Lesson calls → Refresh lessons, or at start).

Install the first time: download the APK from the latest release and open it on the phone.
