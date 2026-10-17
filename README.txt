NANAK SHOP V2 — FRONTEND DEMO

Open index.html directly or run the folder using VS Code Live Server.
Pages:
- index.html — home, product catalogue, filters/search, testimonials, cart and checkout
- about.html — expanded purpose/story/vision/values page
- terms.html — separate Terms & Conditions starter page
- privacy.html — separate Privacy Policy starter page
Assets:
- assets/css/style.css
- assets/js/app.js

V2 features:
- Responsive layout for mobile/tablet/desktop
- Mobile navigation opens from the left using Bootstrap offcanvas
- Donation announcement marquee
- Gurudwara/langar/community-service themed image direction (external demo image URLs; replace with client-approved Gurudwara images before production)
- Scroll reveal animations, hover transitions and reduced-motion accessibility support
- Cart stored in localStorage under key nanakShopCartV2; changes persist after refresh
- Checkout form serializes customer, delivery and selected items into a versioned JSON payload and downloads nanak-shop-order-enquiry.json
- Separate About, Terms and Privacy pages
- Homepage values-based demo testimonials

Important:
1. Replace +91 XXXXX XXXXX and tel:+91XXXXXXXXXX with the verified client number.
2. About page explicitly avoids inventing a founding date/founder history; add verified client details when available.
3. Testimonials are illustrative values-based statements, not real customer reviews. Replace with approved reviews before launch.
4. Terms/Privacy are starter templates, not legal advice; client must review and approve them.
5. This is frontend only. JSON is downloaded locally; no API request, email, WhatsApp order, payment or database submission occurs.
6. Images are external URLs and require internet. Review/replace images with client-approved Gurudwara/langar photography for production.
7. Product list and quantities are demo examples. Prices are not configured.
8. Later Laravel integration: convert pages to Blade layouts/views, serve assets from public/, validate requests server-side, and submit the same JSON schema to a Laravel endpoint.
