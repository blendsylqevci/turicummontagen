# Verification

- Production build: `npm run build` passed.
- Browser: homepage rendered on desktop (1280px) and mobile (390px); screenshots visually inspected.
- Hero slider: direct slide selection, next button and pause control worked.
- Mobile menu: opened and exposed all service and page links; contact navigation worked.
- All four service pages, about, references and contact loaded at 320px with no horizontal overflow or Vite error overlay.
- Browser error log was empty.
- Contact form rejected empty required inputs and accepted complete values.
- WhatsApp submission was intercepted in the test browser: correct Swiss destination and message content verified, with the expected status text. No message was sent.
- Email opens the user's mail application; delivery depends on that application and is not implemented as a server-side submission.
- Font files and licences are local; generated images are local optimised WebP assets.

Before publishing, complete verified legal/company/hosting information and add real approved project references. See README.md.

## Expanded service pages and brand update

- All four service pages now include category-specific scope, applications, quality details, a four-step process, four FAQs and a project enquiry checklist.
- Original SVG logo blue measured as RGB 27, 117, 188 (#1B75BC); applied across the website with black, white and pale blue supporting surfaces.
- Final production build passed.
- All four pages tested at 320px: no horizontal overflow, four scope cards, four process steps, four FAQs, loaded hero images.
- Desktop and mobile service introductions and an expanded FAQ were visually inspected.
- FAQ click opens its answer; the section navigation reaches #fragen.
- Service CTA preselects Lüftung on the contact form.
- Service overview includes all four cards and three new coordination sections.
- Homepage retains its three-image slider and has no mobile overflow.
- Reduced-motion CSS disables added entrance and reveal animations.
