# KW Explore — Marketing Deck Generator (Static Web App)

This folder contains a single–page web app that builds a full marketing asset pack for any property:
- PPTX marketing deck
- Social PNGs (IG/Facebook/Reel cards)
- QR codes (WhatsApp + site)
- One‑page property site (HTML) + PWA icons/manifest
- Copy pack (TXT)
- KPI tracker (XLSX)
- Optional: email ZIP via EmailJS

## Quick start
1. Open **index.html** in your browser and fill in the fields.
2. Click **Generate Asset Pack** to download a ZIP.
3. (Optional) Enter your EmailJS keys and press **Email Results (ZIP)** to email the pack.

## Deploy to GitHub Pages
1. Create a repo and commit the content of this folder.
2. Settings → Pages → Source: **Deploy from a branch**; Branch: **main**; Folder: **/**.
3. Your site will be available at `https://<username>.github.io/<repo>/`.

## Branding
- Replace **assets/logo.png** with your KW Explore logo (PNG/SVG rasterized to PNG).
- Replace **assets/icons/icon-source.png** with your app icon; we generated sizes for desktop & Android: 16/32/180/192/512.

## EmailJS
Create a Service and Template. Allow your Pages domain in EmailJS settings.
Template variables used by the app:
- `to_email`, `property_address`, `suburb`, `wa_link`, `filename`, and optional base64 `content` for the ZIP.
