# Last Seen

A murder logic puzzle: 40 cases from 4×4 to 8×8. Installable and playable offline.

## Put it on GitHub Pages

1. Create a new public repository on GitHub, for example `last-seen`.
2. Upload every file in this folder to the repository root. There are no subfolders,
   so you can select them all at once, even from a phone.
   On github.com: **Add file → Upload files**, drag them in, then **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment*, set **Source** to
   *Deploy from a branch*, pick **main** and **/ (root)**, then **Save**.
4. After a minute or two the game is live at
   `https://YOUR-USERNAME.github.io/last-seen/`.

## Install on Android

Open that address in Chrome. Tap **Install the app** on the home screen of the game,
or use Chrome's ⋮ menu → **Install app**. It gets its own icon, opens full screen,
and works offline after the first visit.

## Updating

After changing `index.html`, edit the first line of `sw.js` (for example
`last-seen-v7` → `last-seen-v8`) and upload both files. Installed copies update the
next time they're opened online. Saved progress is kept.
