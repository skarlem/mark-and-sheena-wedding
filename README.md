# Mark & Sheena — Wedding Invitation

A three-page wedding invitation website. Plain HTML and images, no build step.

- `index.html` — the page (pages stack vertically and scroll on every screen size)
- `assets/page-1.webp` … `page-3.webp` — invitation pages cropped from the original artwork
- `assets/thumbnail.jpg` — link preview image (page 1) for Messenger, Facebook, etc.
- `assets/share-preview.jpg` — the zip's original landscape preview card, currently unused

Tap targets on the artwork open Google Maps (venue address, map, button, QR code), call the RSVP number, or start an RSVP email.

## Preview locally

Open `index.html` in a browser.

## Publish (GitHub Pages)

Push to a public repo named `mark-and-sheena-wedding`, then Settings → Pages → Deploy from a branch → `main` / root.
The site is served at https://skarlem.github.io/mark-and-sheena-wedding/. If the repo name changes, update the `og:url` and `og:image` URLs in `index.html`.
