# GAURAV - Portfolio Website

Single-file portfolio (`index.html`) + photo (`gaurav.jpg`). No build step.

## Files
- `index.html`  - poori website (HTML + CSS + JS ek hi file me)
- `gaurav.jpg`  - original photo (same folder me rehni chahiye)
- `vercel.json` - cache + security headers
- `robots.txt`  - search engines ko allow karta hai

## Deploy (GitHub + Vercel)
1. GitHub par naya repo banao (jaise `portfolio`) aur ye saari files upload karo.
2. vercel.com par login karo -> Add New -> Project -> apna repo Import karo.
3. Framework Preset: **Other**. Build Command aur Output Directory khaali chhodo. Deploy dabao.

## Deploy ke baad zaroor karo
- `index.html` me `og:image` ki value `gaurav.jpg` se badal kar poora URL karo,
  jaise `https://aapka-site.vercel.app/gaurav.jpg` (WhatsApp/Google preview ke liye).
- Chahein to `<meta property="og:url">` aur sitemap.xml bhi apne domain ke saath add karo.

## Baad me badalna
- Project screenshot / URL: `index.html` me `var IMG=` aur `var RAW=` dhundo.
- Prices: `var PL=` (pricing) aur `function calc()` (calculator).
- Social links: footer me `instagram.com` / `linkedin.com` dhundo.
