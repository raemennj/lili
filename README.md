# lili

Liliana Jewall’s dress-up studio and little world. A complete static web app with avatar customization, saved looks, room decorating, furniture interactions, wallpapers, colors, and holiday items.

Play: https://raemennj.github.io/lili/

On iPhone, open in Safari, tap Share, then Add to Home Screen. The game works offline after the first successful online visit. Looks and rooms are saved in this browser on this device. Saves from the original Sites address remain at that address; browsers do not transfer them between websites.

## Hosting

In repository Settings → Pages, select Deploy from a branch, main, / (root). No build or dependencies are required. To test locally, run `python3 -m http.server 8000` and visit localhost:8000.

When changing cached files, increment the cache version in sw.js.
