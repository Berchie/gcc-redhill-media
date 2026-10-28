# Grace Community Church, Redhill — Communication & Media

Ministry information and volunteering opportunities for Sound, Social Media, and Streaming & Lighting, including Projection.

## Published files

- `index.html`: the responsive webpage.
- `assets/`: the logo, photographs and sign-up QR code.
- `brochures/gcc-media-ministry-brochure.pdf`: the latest six-page brochure.
- `PHOTO-CREDITS.md`: photography sources.

## Hosting

GitHub Pages publishes the `main` branch from the repository root. `.nojekyll` keeps these files as a plain static website. No build tools or paid hosting plan are required.

The webpage links to the PDF using a relative path, so both are hosted together. Sign-up buttons use the existing Google Form.

## Updating

Replace the PDF at the same path to keep its link stable. Edit `index.html` or replace the relevant files in `assets/` to update the webpage. Commit changes to `main`; GitHub Pages publishes them automatically.

## Share the site

Website: https://mediabrochure.gccredhill.org.uk/

Brochure: https://mediabrochure.gccredhill.org.uk/brochures/gcc-media-ministry-brochure.pdf

The access QR is in `assets/brochure-access-qr.png`; a printable display is in `brochures/gcc-media-qr-display.pdf`. This access QR opens the webpage. The sign-up QR in the brochure continues to open the Google Form.

## Custom domain

The configured custom domain is `mediabrochure.gccredhill.org.uk`. In GoDaddy DNS, add a CNAME record named `mediabrochure` pointing to `berchie.github.io` (TTL: 1 hour). Keep the tracked `CNAME` file when updating this website. HTTPS becomes available after DNS and certificate checks complete.
