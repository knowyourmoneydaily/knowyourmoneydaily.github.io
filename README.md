# Know Your Money website

One-page site for the Know Your Money Facebook Page and Instagram (@knowyourmoney.daily). Single `index.html`, no build step, no dependencies (Google Fonts only).

Sections: hero with Penny, money-fact ticker, "guess the real price" car game, top videos (cover images link to Instagram), three calculators (compound growth, loan true cost, rule of 72), six money rules, myth/fact flip cards, about Penny, follow call-to-action. Light and dark theme with a toggle.

- Preview: `python3 -m http.server 4180` in this folder, or the `kym-site` entry in `../.claude/launch.json`.
- Links: Facebook https://www.facebook.com/KnowYourMoney.daily/ and Instagram https://www.instagram.com/knowyourmoney.daily/ (the `LINKS` object at the top of the `<script>`).
- Videos: edit the `VIDS` list; covers live in `assets/covers/` (540 px JPGs made from `../Covers-for-Claude/Upload-720/`).
- Faceless brand: Penny only, no personal name or face (keep the commit author as "Know Your Money"). Every number on the page is an example; the footer says "not financial advice".
- Hosted on GitHub Pages at https://knowyourmoneydaily.github.io (pushing to `main` publishes).
