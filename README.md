# BookAVibe One-Page Website

Simple, mobile-first static website for a cozy cafe called **BookAVibe**.

## Included Files

```text
bookavibe-site/
|-- index.html
|-- styles.css
|-- script.js
|-- favicon.svg
|-- README.md
`-- images/
    |-- app-icon.svg
    |-- hero.avif
    |-- interior.avif
    |-- food.avif
    |-- b1.avif
    |-- b2.avif
    |-- b3.avif
    |-- b4.jpg
    |-- b5.webp
    |-- b7.avif
    `-- logo.jpg
```

## What This Page Includes

- Warm, cozy visual system (cream + rust + deep green)
- Accessible semantic structure and keyboard focus states
- Mobile hamburger navigation with tiny JS toggle
- Sections: Hero, About, Featured Menu, Hours & Location, Reservations, Newsletter, Contact
- Footer with secondary navigation, address, and social links
- SEO metadata, Open Graph tags, and JSON-LD (`CafeOrCoffeeShop`)

## Quick Customization

1. Change colors in `styles.css` at the `:root` variables (`--rust`, `--cream`, `--green`, etc.).
2. Change fonts in `index.html` Google Fonts link and in `styles.css` (`Poppins`, `Merriweather`).
3. Replace photos in `images/` and update paths in `index.html` (`hero.avif`, `interior.avif`, `food.avif`).
4. Update business details:
   - Address/hours/contact text in `index.html`
   - JSON-LD business info in `<script type="application/ld+json">`
5. Replace social links (`#`) with real profile URLs.

## Run Locally

Open `index.html` in any browser.

## Deploy to Static Hosting

### GitHub Pages

1. Push this folder to a GitHub repository.
2. In repository settings, open **Pages**.
3. Set source to the branch/folder containing `index.html`.
4. Save; your site is published on the provided GitHub Pages URL.

### Netlify

1. Drag and drop the `bookavibe-site` folder in Netlify Drop, or connect your Git repo.
2. Build command: none.
3. Publish directory: the folder containing `index.html`.

## Maintenance Notes

- CSS is framework-free and intentionally small for easy edits.
- All content is in plain HTML/CSS with a single tiny JS file for nav behavior.
- Images use modern formats and `loading="lazy"` where appropriate.
