# Turicum Montagen AG

Responsive German-language website built with Vite, vanilla JavaScript and CSS.

## Run

```sh
npm install
npm run dev
npm run build
npm run preview
```

The production site is generated in `dist/`. Configure the host to serve `index.html` for application routes. A `_redirects` file is included for compatible static hosts.

## Content

- Home with a three-image slider, manual controls, pause and reduced-motion support.
- Services overview and four individual service pages.
- About, references, contact, legal and privacy pages.
- Original supplied logo extracted as SVG.
- Four original generated service photographs, optimised as WebP. Prompts and asset paths are in `IMAGE-PROMPTS.md`.
- WhatsApp: https://wa.me/41795541311
- Phone: +41 79 554 13 11
- Address: Althardstrasse 10, 8105 Regensdorf
- Email: info@turicummontagen.ch

Edit service data and page content in `src/main.js`; styling is in `src/style.css`.

## Contact behaviour

The form validates required fields and prepares a message in the visitor's email application or WhatsApp. It does not send a message automatically and has no backend or database. No email service credentials are required.

## Before publication

Add the verified company representation and commercial register details to the legal page, and hosting details to the privacy page. Have the final legal information reviewed for the actual business and hosting setup. Sixteen supplied photographs are shown on the references page. Twelve of these are also assigned to the relevant service galleries. The homepage keeps its existing reference preview. Add verified project names and descriptions when available. The generated photographs are illustrative and must not be represented as completed client projects.

DM Sans and Manrope are served locally from `public/fonts/`; the website makes no external font requests.

## Reference photographs

The four user-supplied WebP images are copied unchanged into `public/images/references/`. The gallery provides full-image viewing, previous/next navigation, keyboard controls and Escape to close. Captions describe visible installations without inventing clients, locations or project dates.

The twelve additional September photographs and their category assignments are documented in `PHOTO-CATEGORIES.md` and `src/project-photos.js`. These files use the original JPG images, without AI editing.
