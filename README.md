# Prof. R. K. Singh — Digital Business Card

**Live site:** [rksinghdu.github.io/RK-VC/](https://rksinghdu.github.io/RK-VC/)

A responsive, professional digital business card for **Prof. R. K. Singh**, Professor, Faculty of Commerce and Business, Delhi School of Economics, University of Delhi.

---

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Complete single-file website (HTML + CSS + JS) |
| `rksingh.vcf` | vCard 3.0 contact file for Save Contact download |
| `photo.png` | Profile photograph (place in root alongside index.html) |
| `logo.png` | Institution logo (optional; used in header badge) |

---

## Updating

All editable content is in `index.html`. Key locations:

- **Name / Title** — `<h1 class="hero-name">` and `<p class="hero-title">`
- **Phone / Email** — `href="tel:..."` and `href="mailto:..."` in the actions grid
- **Specialisation chips** — `.spec-chips` section
- **Social links** — `.socials-row` section
- **Colours** — CSS custom properties in `:root` at the top of `<style>`

After editing `index.html`, also update `rksingh.vcf` to keep both in sync.

---

## Pending updates

- Replace the LinkedIn URL placeholder (`/in/rk-singh-du`) with your actual LinkedIn profile URL
- Replace the Google Scholar URL placeholder with your actual Scholar citations ID

---

## Deployment

Hosted via GitHub Pages (branch: `main`, root: `/`). Any push to `main` auto-deploys.

---

## Credits

Designed and built for Prof. R. K. Singh, DSE, University of Delhi.  
QR code generation via [qrcodejs](https://github.com/davidshimjs/qrcodejs).