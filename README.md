# Soursprout — Texas cottage food site

Static single-page site for Soursprout (Russian-style sauerkraut). Live on Netlify at `https://soursprout.com` (also `https://soursprout.netlify.app`).

## Compliance notes (TX cottage + HOA)

- Texas **in-person delivery only** (operator or household member). **No shipping. No pickup at the production home.**
- Pre-order product blocks include: ingredients, net weight, ALL-CAPS cottage disclosure, and DSHS Cottage Food Registry **#14300**. Classic sauerkraut also includes a batch note and the TCS safe-handling statement. Sourdough Bread is a separate label (contains wheat; no safe-handling statement, no refrigeration line, no batch-number format).
- No probiotic / gut / immunity / digestion health claims.
- Offering now: Classic sauerkraut (cabbage, carrots, salt · 16 oz · $12) and Sourdough Bread (oval batard-style loaf · about 1.75 lb / approx. 790 g · $12). Kraut ferment is 72–96 hours. In-person delivery: Plano, Frisco, Allen, McKinney, Richardson. Contact: soursproutllc@gmail.com.
- `assets/images/sourdough.jpg` is a temporary illustrative image. Replace it when a real loaf photo is available.

## Stack

- Single `index.html` + `assets/images/`
- Tailwind via CDN, vanilla JS
- Order flow: inquiry form → `mailto:` (no card checkout yet)

## Local preview

```bash
python -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to the GitHub repo connected to Netlify. Do not cancel HostGator prepaid hosting until Brian APPROVEs.

## Images

```
assets/images/
├── hero.jpg
├── classic.jpg
├── beet.jpg
├── spicy.jpg
├── pantry.jpg
├── making.jpg
├── serving.jpg
└── logo.jpg
```
