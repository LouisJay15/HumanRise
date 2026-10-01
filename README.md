# HumanRise

People-first HR & Recruitment website.

Static multi-page site — plain HTML + CSS, no build step.

## Pages
- `index.html` — Home
- `about.html` — About
- `services.html` — Services
- `business.html` — For Businesses
- `jobs.html` — Jobs
- `submit-cv.html` — Submit CV
- `contact.html` — Contact

## Structure
- `hr-styles.css` — site stylesheet
- `assets/` — logos and imagery

## Brand guidelines
The HumanRise Corporate Identity (CI) guidelines live in `brand/`:
- `brand/index.html`: guidelines (web version, served at `/brand/`)
- `brand/HumanRise-CI-Guidelines.pdf`: guidelines (A4 PDF for print and sharing)
- `brand/HumanRise-CI-Guidelines.pptx`: guidelines as an editable PowerPoint deck (16:9)
- `brand/HumanRise-CI-Guidelines-Slides.pdf`: the PowerPoint deck as a PDF
- `brand/tokens.css`: brand colour, type, radius and shadow variables
- `brand/assets/`: cleaned logo set (colour, white, Deep Rise, black, email), star colourways, avatar, example photos and partner logos

## Running locally
Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying
Works on any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
For GitHub Pages: Settings → Pages → deploy from the `main` branch root.
