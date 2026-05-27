# Soursprout — Cottage Food Website

Beautiful, simple, and appetizing single-page website for Soursprout, a small-batch cottage food business specializing in traditional Russian-style sauerkraut.

## What's Included

- **Hero** with stunning custom food photography
- **About Us** section with story and values
- **Our Kraut** — three product cards (Classic, Beet & Garlic, Spicy Dill) with pricing and images
- **How to Order** with clear local pickup / farmers market / shipping options + working inquiry form
- **Gallery** showcasing the beautiful process and finished product
- **Testimonials** (ready for real ones)
- **FAQ** accordion
- Fully responsive, mobile-friendly design
- Subtle interactions and smooth scrolling

## Custom Graphics

All 8 images were generated specifically for this brand using AI. They live in:

```
assets/images/
├── hero.jpg       (hero banner)
├── classic.jpg
├── beet.jpg
├── spicy.jpg
├── pantry.jpg
├── making.jpg
├── serving.jpg
└── logo.jpg
```

## Quick Start (Local Preview)

1. Open `index.html` directly in a browser, **or** for the best experience:

```powershell
# From the project root
python -m http.server 8000
# Then visit http://localhost:8000
```

Or use any static file server (Live Server extension in VS Code is perfect).

## Customization Guide

### 1. Contact Information (important!)
Search and replace these placeholders in `index.html`:

- `hello@soursprout.com` → your real email
- Instagram / Facebook links in the footer (currently `#`)
- Farmers market schedule and location details
- Your actual town/region

### 2. Pricing & Products
Adjust prices, add new varieties, or change descriptions in the product cards (around lines 160–280).

### 3. Your Story
The About section can be updated with your real family story, location, or specific details.

### 4. Adding Real Testimonials
Replace the placeholder quotes with actual customer feedback.

### 5. Logo
The circular logo in the navbar and footer uses `assets/images/logo.jpg`. Replace it with your own logo or a better version anytime (keep square-ish proportions).

## Hosting (Free & Easy Options)

- **GitHub Pages** (recommended if you use Git)
  1. Push this folder to a GitHub repo
  2. Go to Settings → Pages → Deploy from `main` branch
  3. Your site will be live at `https://yourusername.github.io/soursprout`

- **Netlify Drop** (easiest)
  1. Go to https://app.netlify.com/drop
  2. Drag the entire `soursprout` folder onto the page
  3. Done — instant free hosting + custom domain option

- **Vercel**, **Cloudflare Pages**, or any static host

## Notes for Cottage Food Businesses

- The ordering flow currently uses a `mailto:` link (opens the visitor's email client). This is reliable and free.
- For a more polished experience later, you can connect the form to **Formspree**, **Tally**, or **EmailJS** in under 10 minutes.
- Consider adding your local cottage food permit info or cottage food law disclaimers if required in your state.

## Tech Stack

- Pure HTML + Tailwind CSS (via CDN)
- A few lines of vanilla JavaScript
- No build tools or dependencies needed

Enjoy sharing your beautiful kraut with the world!

---

Made with care for Soursprout. Feel free to reach out if you want help adding a real cart, payment integration, blog, or anything else.