ROOTED — setup

WHAT'S HERE
  index.html          the whole app (works on its own if you just open it)
  manifest.json       lets phones install it like an app
  sw.js               makes it work fully offline
  icon-*.png          app icons
  apple-touch-icon.png  home screen icon for iPhone

HOSTING ON GITHUB PAGES (same as your training-log site)
  1. Create a new repo (e.g. "rooted") or a folder in an existing Pages repo
  2. Upload all 6 files
  3. Enable GitHub Pages (Settings > Pages > deploy from main branch)
  4. Visit https://YOURUSERNAME.github.io/rooted/ on each kid's phone

SAVING TO THEIR PHONES
  iPhone:  open the link in Safari > Share button > "Add to Home Screen"
  Android: open in Chrome > menu (3 dots) > "Add to Home screen" / "Install app"
  After the first visit it works completely offline.

NOTES
  - Each phone keeps its own favorites, journal, and weekly memory verse
    (nothing is shared or sent anywhere — all data stays on the device)
  - The memory verse changes each Monday, tailored to whichever emotion
    they visited most the week before; falls back to classics if unused
  - To update content later, edit the DATA section in index.html and
    bump the cache name in sw.js (e.g. 'rooted-v2')
