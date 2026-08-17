# Lunar Defense — website

Static site (plain HTML, no build step). Open `index.html` in a browser to preview locally;
drop these files into the GitHub Pages repo to publish.

## Pages
- `index.html` — homepage (now includes a **Products** section + nav link)
- `mobile.html` — Lunar Defense Mobile Security marketing page
- `msp.html` — Lunar Defense Managed marketing page
- `support.html` — App Store support page (link this from App Store Connect)
- `privacy.html` — consumer privacy policy (replaces the old one)
- `news.html` — unchanged

## App Store listings

Both iOS apps are live. Every download button uses Apple’s official badge
(`assets/app-store-badge.svg`) linking to:

- Mobile Security — https://apps.apple.com/app/lunar-defense-mobile-security/id6775614713
- Managed — https://apps.apple.com/app/lunar-defense-managed/id6792022798

Enterprise is still a “Coming soon” card on `index.html` with no App Store link.

## Screenshots

`mobile.html`’s hero carousel rotates `assets/app-screens/1.png`, `2.png`, `3.png`; the static
phone in the “Sweep free” section uses `sweep-report.png`. `msp.html`’s carousel rotates
`MSP-1.png` through `MSP-4.png`. Replace in place using the same filenames.

## Notes
- Fonts (IBM Plex) and Tailwind (homepage only) load from CDNs — needs internet on first load.
- Pricing: Free / Pro Monthly $4.99 / Pro Yearly $49.99 (3-day trial).
- Support + Privacy contact: support@lunardefense.co
