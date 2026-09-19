# Soursprout — Texas cottage food site

Static single-page site for Soursprout (Russian-style sauerkraut). Live on Netlify at `https://soursprout.com` (also `https://soursprout.netlify.app`).

## Compliance notes (TX cottage + HOA)

- Texas **in-person delivery only** (operator or household member). **No shipping. No pickup at the production home.**
- Pre-order product block includes: ingredients, net weight, batch note, ALL-CAPS cottage disclosure, DSHS Cottage Food Registry **#14300**, TCS safe-handling statement.
- No probiotic / gut / immunity / digestion health claims.
- Offering now: Classic only (cabbage, carrots, salt · 16 oz · $12). ~4-day ferment. In-person delivery: Plano, Frisco, Allen, McKinney, Richardson. Contact: soursproutllc@gmail.com.

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
