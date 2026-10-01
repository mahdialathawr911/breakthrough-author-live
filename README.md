# Breakthrough Author Live

A single-file, self-contained landing page for the "Write Your Bestselling Book in 4 Weeks" coaching challenge. Dark-navy/gold mobile-first sales page with a light/dark theme toggle, built in plain HTML/CSS/JS — no build step, no framework.

**Live URL:** https://mahdialathawr911.github.io/breakthrough-author-live/

## Placeholders that still need replacing

1. **VSL embed** — inside the `#vsl` div in the hero section; paste your real YouTube/Vimeo/Wistia iframe embed code.
2. **4 photos** — swap the SVG icon placeholders for `<img>` tags:
   - `data-photo-slot="sai"` (Section 3, credibility)
   - `data-photo-slot="myono"` (Section 4, case study 1)
   - `data-photo-slot="aila"` (Section 4, case study 2)
   - `data-photo-slot="kaley"` (Section 4, case study 3)
   Drop image files into `assets/photos/`.
3. **Coupon code** — currently shows `CHALLENGE47` in the price block (Section 8, `#checkout`).
4. **Checkout URL** — every gold button currently points to `#checkout`; replace `href="#checkout"` with the real GHL checkout link once it exists.
5. **Facebook Pixel ID** — `YOUR_PIXEL_ID` in `<head>`. PageView and ViewContent fire automatically; InitiateCheckout fires on every gold button click; Purchase is stubbed as a comment to fire on the real thank-you page.

## How to edit

- Everything lives in a single file: `index.html` (inline `<style>` and `<script>`, no build step).
- Open it by double-clicking it locally, or via Live Server — it also works as-is on GitHub Pages.
- Colors, fonts, and spacing are controlled by CSS custom properties at the top of the `<style>` block (`:root` for dark/default, `[data-theme="light"]` for the light theme overrides).
- To change copy, search the file for the section comment (e.g. `SECTION 4 · CASE STUDIES`) and edit the text directly.
