# ontelivo-studio.github.io

Public website of Ontelivo (https://ontelivo.com), served by GitHub Pages from `main`.

Static HTML and CSS only; no build step, no analytics, no cookies, no scripts, no external fonts (Fraunces and Nunito, both SIL OFL, are hosted in `fonts/`). Everything in this repository is public: never commit keys, tokens or internal documents.

## Pages

- `index.html`: home (hero with Google Play button, the goal, the story of the studio, download call).
- `chess-abstract/`: the game page (hero, how it plays, FAQ, download band). Describes the idea of the game, not numbers that change (levels, chapters, languages, dates). Keep it to what is true of the game today and in step with the Google Play listing. The visible FAQ and the FAQPage JSON-LD in its head must match word for word.
- `play/`: short, noindex link page with one Google Play button and a link to the TikTok profile (`@chess.abstract`). Use `https://ontelivo.com/play/` in the Instagram bio and other social profiles instead of the raw Play link.
- `chess-abstract/support/`: support, contact and FAQ.
- `chess-abstract/privacy/`: privacy policy (Play URL, plan item B8).
- `chess-abstract/terms/`: terms of use (L6).
- `llms.txt`: short fact sheet for AI search engines; update it when the Play listing facts change (category, ads, purchases).
- `404.html`, `robots.txt`, `sitemap.xml`, `img/` (covers, logo, favicons, social previews: `og.png` for the studio, `og-chess-abstract.jpg` for the game and `/play/`), `fonts/`.
- `CNAME` holds the custom domain; `.nojekyll` turns off Jekyll.

The Google Play link (`https://play.google.com/store/apps/details?id=com.ontelivo.chessabstract`) appears in the nav, the home hero and download band, and the game page; change it everywhere at once if the package name ever changes.

## Keep in step with the game

The privacy policy must describe what the game actually sends (GA4, Remote Config, ads, purchases). Change it before a build that changes that, and update "Last updated". Later: `app-ads.txt` (AdMob publisher ID, A4).
