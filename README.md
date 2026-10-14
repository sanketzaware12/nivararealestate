# NIVARA ESTATES — Multi-page real-estate website

A custom responsive frontend concept using HTML5, CSS3 and vanilla JavaScript. It uses the supplied reference project's architectural photos where suitable, rearranged under a new brand, logo, colour palette and layout.

## Pages
- `index.html` — Home, property search, featured listings, brand introduction and discovery flow
- `about.html` — Story, mission, vision, principles and placeholder team profiles
- `projects.html` — Searchable property listing with type, location, budget and status filters plus Load More
- `property-details.html?id=aurora` — Reusable property details page; supported IDs: `aurora`, `willow`, `solstice`, `terrace`, `horizon`, `meadow`
- `services.html` — Proposed service categories
- `gallery.html` — Category filters and keyboard-accessible image lightbox
- `contact.html` — Validated enquiry form, contact placeholders and FAQ accordion

## Run locally
Open `index.html` in a browser, or serve the folder using VS Code Live Server / another static file server. Google Fonts are optional; local fallback fonts are specified.

## Configure before publishing
1. Replace placeholder contact information (`+91 00000 00000`, `hello@example.com`, Pune address and business hours) with approved business details in the HTML footer/contact sections.
2. Edit `CONFIG` at the top of `js/main.js`. Set `whatsappNumber` to digits only, including country code, e.g. `919876543210`. Once set, the enquiry form and the floating WhatsApp button open WhatsApp with a ready message to that number. Until configured, the form only shows a demo message.
3. Replace demonstration properties, prices, status, amenities and images in the `properties` array in `js/main.js` with verified listing data.
4. Connect a backend, form provider or email service if enquiries must be stored or delivered. Current form validation is client-side; it does not save leads. If WhatsApp is configured, form submission opens a prefilled WhatsApp message for the user to send.
5. Add a verified map URL/address and genuine company/team details. No actual reviews, credentials, RERA number, awards, verified statistics or legal/financial promises are claimed.
6. Test every page and form on the target hosting environment. The website uses relative paths and can be deployed to static hosting such as GitHub Pages, Netlify or Vercel.

## Notes
- The listings and prices are clearly sample demonstration content and must not be treated as real offers.
- The proposed service categories need client confirmation.
- All eight reference project photos are local in `assets/images/`; replace them with licensed, approved company imagery before production.
- No framework or backend is required for the static frontend. Form delivery requires a configured integration.
