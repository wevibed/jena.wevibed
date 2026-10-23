# Jena Cleaning Services website

Responsive multi-page React + Vite website redesign with a full-bleed photographic hero, headline-only hero text, and an overlapping service-card carousel.

## Pages
- Home with image-led hero and interactive services carousel
- Services
- Residential Cleaning
- Commercial Cleaning
- Post-Construction Cleaning
- About
- Contact & Bookings

## Run locally
1. Install Node.js (LTS).
2. Run `npm install`.
3. Run `npm run dev`.
4. Run `npm run build` for a production build (outputs `dist/`).

## Cloudflare Pages
- Framework preset: Vite
- Build command: `npm run build`
- Build output directory: `dist`
- Root directory: `/`
- `public/_redirects` supports client-side routes.

## Notes
- The home hero displays only “A cleaner space. A better feeling.” over a full-width photograph.
- The service carousel includes all seven cleaning services, image-led split cards, neighbouring cards, arrow controls and pagination dots.
- The floating contact button uses a WhatsApp-style phone-in-chat icon and links to `https://wa.me/263782460809`.
- Images and Google Fonts load from external URLs and require an internet connection.
- The contact form prepares a WhatsApp message for the visitor to review and send; it does not send automatically.
- Confirm service areas, operating hours and quote details before launch. Replace illustrative photos with approved business photos when available.
