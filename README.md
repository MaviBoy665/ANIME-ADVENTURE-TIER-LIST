# AA Value Tier List

An unofficial value list and trade helper for **Anime Adventures** on Roblox. It is a single static web page with no build step and no dependencies.

**Live site:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

## Features

- **Trade values:** units, gamepasses, stats, skins, relics and new units, with value, demand (1 to 10, shown as a percent) and trend. Search by name or note, filter by category, or show shiny units only.
- **Calculator:** add units to a "You give" side and a "You get" side and see whether the trade is fair, with a balance bar, average demand and warnings for overpriced, hyped or unstable units.
- **Meta tier list:** units ranked by tier, with General, DPS and Support views.
- **Items and stages:** items, story worlds, special stages and unit sources, all searchable.
- Light and dark theme (remembered between visits), mobile friendly, and every tab has its own link (`#trade`, `#calc`, `#meta`, `#info`).

## Run it locally

Download `index.html` and open it in a browser. That's all.

## Deploy with GitHub Pages

1. Put `index.html` in the root of this repo.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute your site is live at the address above.

It also works on Netlify, Cloudflare Pages or any other static host.

## Updating the values

All data lives in the `<script>` block of `index.html`. Trade values are in the `T` list, one unit per line in the form `name|value|demand|flags|note`. Flags: `s` shiny, `o` overpriced, `h` hyped, `u` unstable.

## Credits

**Website creator:** Hev Mavi ([Discord](https://discord.gg/P62dhxbt2))

**Tier list credits**
- Server: [discord.gg/aavl](https://discord.gg/aavl)
- Value list owners: Zog, Nasty
- Value list team: pop, TheFeeit, CoolCockatoo, Shel, Icy
- Honorable mention: showyy, bofa_pp12, Sylox, ifeellikepablos, Zoldic, Caply

**Sources**
- Meta tier list: [Destructoid](https://www.destructoid.com/anime-adventures-tier-list/)
- Items and stages: [Bloxodes Anime Adventures wiki](https://bloxodes.com/wiki/anime-adventures)

## Disclaimer

This is an unofficial fan project and is not affiliated with Roblox or the Anime Adventures developers. Values are community estimates and change often, so use them as a guide and not as the basis for every trade.

## License

The code is released under the license in [LICENSE](LICENSE). The trade values, tier list and item data belong to the sources credited above, and the logo is not covered by the license.
