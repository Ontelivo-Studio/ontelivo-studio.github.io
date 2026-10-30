# ontelivo-studio.github.io

Public website of Ontelivo (https://ontelivo.com), served by GitHub Pages from `main`.

Static HTML and CSS only; no build step, no analytics, no cookies, no scripts, no external fonts (Fraunces and Nunito, both SIL OFL, are hosted in `fonts/`). Everything in this repository is public: never commit keys, tokens or internal documents.

## Pages

- `index.html`: home (studio, the game in short, tester call).
- `chess-abstract/`: the game page. Describes the idea of the game, not numbers that change (levels, chapters, languages, dates).
- `chess-abstract/support/`: support, contact and FAQ.
- `chess-abstract/privacy/`: privacy policy (Play URL, plan item B8).
- `chess-abstract/terms/`: terms of use (L6).
- `404.html`, `robots.txt`, `sitemap.xml`, `img/` (covers, logo, favicons, social preview), `fonts/`.
- `CNAME` holds the custom domain; `.nojekyll` turns off Jekyll.

## Keep in step with the game

The privacy policy must describe what the game actually sends (GA4, Remote Config, ads, purchases). Change it before a build that changes that, and update "Last updated". Later: `app-ads.txt` (AdMob publisher ID, A4).
