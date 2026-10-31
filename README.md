# Mark & Sheena — Wedding Invitation

A three-page wedding invitation website. Plain HTML and images, no build step.

- `index.html` — the page (pages stack vertically and scroll on every screen size)
- `assets/page-1.webp`, `page-2-motif.webp`, `page-3.webp` — invitation pages cropped from the original artwork. Page 2 is taller (507×1124): a blank strip was added under the venue address, and the motif (colour swatches and names) is drawn over it in `index.html`, so the colours and names can be edited there.
- `assets/thumbnail-page-1.jpg` — link preview image (page 1) for Messenger, Facebook, etc. Facebook caches preview images by URL, so a new thumbnail needs a new filename.
- `assets/share-preview.jpg` — the zip's original landscape preview card, currently unused

Tap targets on the artwork open Google Maps (venue address, map, button, QR code), call the RSVP number, or start an RSVP email.

## Preview locally

Open `index.html` in a browser.

## Publish (GitHub Pages)

Push to a public repo named `mark-and-sheena-wedding`, then Settings → Pages → Deploy from a branch → `main` / root.
The site is served at https://skarlem.github.io/mark-and-sheena-wedding/. If the repo name changes, update the `og:url` and `og:image` URLs in `index.html`.
