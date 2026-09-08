
<div align="center">

<img src="assets/icon.png" width="120" alt="Carcassonne Scoring app icon">

# Carcassonne Scoring — Landing Page

**Real-time score tracker for the board game Carcassonne. Up to 9 players, game history, 100% offline.**

[**Live site**](https://govorec.github.io/carcassonne-scoring-site/) · [Privacy Policy](https://govorec.github.io/carcassonne-scoring-site/privacy/PRIVACY) · [Support](https://govorec.github.io/carcassonne-scoring-site/#support)

<a href="https://apps.apple.com/app/apple-store/id6763508490?pt=128781731&ct=gh_readme&mt=8">
  <img src="assets/Badge/Download_on_the_App_Store_Badge_US-UK_RGB_blk_092917.svg" height="50" alt="Download on the App Store">
</a>

</div>

---

## About

This repository hosts the marketing site for **Carcassonne Scoring** — an iOS companion app that replaces pen and paper at the game table. Put the phone in the middle of the table and every player sees the live score.

**App highlights:**
- Real-time score tracking with a tap-friendly medieval-styled UI
- 2–9 players, no-scroll layout for up to 6
- Full score history with running totals
- Random first-player roulette
- Share final results to any app
- 100% offline · no ads · no accounts · no data collection

## Site features

- Single static page (`index.html`) — no build step, styled with Tailwind CSS (CDN)
- Client-side i18n in **8 languages** (EN, DE, FR, ES, UK, RU, ZH, JA): UI strings, localized screenshots and localized App Store badges swap with the language
- Privacy policies in 7 languages rendered by GitHub Pages (Jekyll) from `privacy/*.md`
- Privacy-friendly, cookie-less analytics (Cloudflare Web Analytics + GoatCounter)

## Structure

```
index.html            # the landing page (markup + i18n dictionary + scripts)
assets/               # icon, hero background, per-language screenshots, App Store badges
privacy/PRIVACY*.md   # localized privacy policies (Jekyll-rendered)
_includes/            # head-custom.html — analytics injected into Jekyll pages
```

## Development

No tooling required — open `index.html` in a browser. Deployment is automatic: every push to `main` is published by GitHub Pages.

---

*Carcassonne is a trademark of its respective owners. This is an unofficial companion app and is not affiliated with or endorsed by the trademark holders. App Store and the App Store badge are trademarks of Apple Inc.*

© 2026 Oleg Kozlovskyi
