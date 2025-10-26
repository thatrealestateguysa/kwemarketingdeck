# KW Explore — Marketing Deck Generator (Updated)

This bundle contains:
- `index.html`: Single-file web app (branding uploads, PWA icons, EmailJS)
- `assets/logo.png`: KW Explore logo (used in deck/social/site)
- `assets/icons/`: favicon (16/32), Apple 180, Android 192/512, source icon
- `manifest.webmanifest`: PWA manifest

## Email sending
Emails are sent **FROM**: `Dawie du Toit <dawie.dutoit@kwsa.co.za>` **TO**: the Agent Email you enter.
Configure EmailJS (public key, service ID, template ID) and add your GitHub Pages domain to **Allowed Origins**.

Template variables the app sends:
- `to_email`, `to_name`, `from_email`, `from_name`, `reply_to`
- `property_address`, `suburb`, `wa_link`, `filename`, optional base64 `content` (ZIP attachment <= ~10MB)

## Deploy on GitHub Pages
1) Create a new repo and upload all files in this ZIP.
2) Settings → Pages → Deploy from a branch → `main` / `(root)`.
3) Open the published URL, fill in the form, and generate/email the asset pack.

