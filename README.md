# Gauri's Diet Clinic — Website

A simple static website for *Gauri's Diet Clinic* styled to use the attached logo's color palette.

**Quick Links**
- Live page: open [index.html](index.html)

**Description**
- This project is a single-page static site (HTML + CSS) intended to present services, testimonials and contact information for the clinic.
- The stylesheet has been updated to use CSS variables derived from the supplied logo so the whole site uses the logo's colors.

**Color Palette (from logo)**
- **Primary (blue):** #1E6F8F
- **Secondary (yellow):** #F5B322
- **Dark (text):** #4A4A4A
- **Light (background):** #F5F6F6
- **White:** #FFFFFF

These are available as CSS variables in the top of `index.html` under the `:root` selector (e.g. `--primary`, `--secondary`).

**Serve locally**
1. Open a terminal in the project folder.
2. Run a simple HTTP server (Python included on many systems):

```bash
python -m http.server 8000
```

3. Open http://localhost:8000 in your browser.

**Edit colors**
- To tweak colors, edit the `:root` variables at the top of `index.html`. The site references semantic variables (`--primary`, `--secondary`, `--dark`, `--light`, `--white`) so changing those will update the whole site.

**Commit changes**
```bash
git add index.html README.md
git commit -m "Use logo palette and add README"
```

**Notes & Next Steps**
- I updated styles to use the logo palette and adjusted UI elements for contrast; please review visually and tell me if you prefer the CTA to use yellow (`--secondary`) instead of blue (`--primary`).
- If you want, I can also extract the logo into `images/logo.svg` and reference that for sharper display.

---
Made by your coding assistant — edits live in `index.html`.
