# Lunar Defense — website

Static site (plain HTML, no build step). Open `index.html` in a browser to preview locally;
drop these files into the GitHub Pages repo to publish.

## Pages
- `index.html` — homepage (now includes a **Products** section + nav link)
- `mobile.html` — Lunar Defense Mobile Security marketing page
- `support.html` — App Store support page (link this from App Store Connect)
- `privacy.html` — consumer privacy policy (replaces the old one)
- `news.html` — unchanged

## Before publishing — swap these placeholders

1. **App Store URL.** Buttons currently read “Coming soon”. When the app is live, replace the
   coming-soon elements with links to the App Store listing:
   - `index.html` → Products card (the `App Store · Coming soon` span + the
     `Coming soon to the App Store` status badge → “Live on the App Store”)
   - `mobile.html` → hero + final CTA (two “Coming soon to the App Store” buttons) and the
     three pricing buttons (Download free / Start free trial / Go Pro monthly)
2. **App Store badge art.** The coming-soon buttons are custom-styled placeholders. Once live,
   swap in Apple’s official “Download on the App Store” badge (don’t recreate Apple’s art).
3. **Carousel screenshots.** The hero carousel on `mobile.html` rotates
   `assets/app-screens/1.png`, `2.png`, `3.png` (currently 1 real screenshot + 2 placeholders).
   Replace them with your own using the same filenames. The static phone in the “Sweep free”
   section uses `assets/app-screens/sweep-report.png`.

## Notes
- Fonts (IBM Plex) and Tailwind (homepage only) load from CDNs — needs internet on first load.
- Pricing: Free / Pro Monthly $4.99 / Pro Yearly $49.99 (3-day trial).
- Support + Privacy contact: support@lunardefense.co
