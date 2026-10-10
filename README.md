# Smart Way website redesign

Responsive static website with a bespoke Three.js sports coupe, GSAP entrance and scroll animations, repair-area controls, mobile/shop switch, service-area search, FAQs, and a guided SMS estimate flow.

Run `npm start`, then open http://127.0.0.1:3000. Run `npm run check` for JavaScript syntax checks. Deploy the contents of `dist/` to any static host.

The site includes Home, Services, How It Works, Our Work, Service Areas, Contact, and Privacy pages. `npm run build` regenerates the supporting pages using the shared homepage shell and the content in `build-pages.mjs`. Google Maps links use the supplied business listing; Google review links open its reviews view. The gallery and privacy page are internal, with no links to the old website.

The estimate helper prepares a message for the verified business number; the customer must send it from their messaging app and can attach photos there. No request is submitted to a backend and no customer details are stored by the website.

Business details and repair photos are sourced from https://www.smartwaymobiledentrepair.com/. The 3D vehicle is an illustrative procedural model. External fonts use Google Fonts. Three.js 0.180.0 and GSAP 3.13.0 are vendored locally. See their distribution headers for licenses.

This is a separate redesign preview. Publishing it does not replace the business's original website or domain.
