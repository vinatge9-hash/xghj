# The Daily Grind — Website Build

This project provides a complete 5-page (plus README) static website for a cozy, modern coffee shop named The Daily Grind.

Phase: Discovery -> Build

Pages:
- index.html: Home with hero, featured drinks, and testimonials
- about.html: Our Story with founders image
- contact.html: Visit page with address, hours, and contact form
- cart.html: Fully client-side functional cart (localStorage) with ability to review items
- checkout.html: Checkout flow with delivery details and order summary
- README.md: This documentation

Technical notes:
- All styling is done with Tailwind CSS classes loaded via CDN. Fonts are designated via Tailwind config (Lora for headings, Inter for body).
- Images use the required placeholder syntax: src='https://images.pexels.com/photos/8293777/pexels-photo-8293777.jpeg?auto=compress&cs=tinysrgb&h=650&w=940'
- Accessibility: semantic HTML5 elements, semantic headings, descriptive alt attributes.
- Animations: on-load fade-in and viewport-based section reveal implemented with simple JS and Tailwind utility classes.
- Currency uses a simple client-side calculation; no server calls are required for this demo.
- The current date/context (Saturday, September 6, 2025, Nadargul, Telangana, India) is reflected in pages when applicable.

Usage:
- Open index.html in a modern browser. Use the navigation or the CTA buttons to explore.
- The Cart and Checkout are client-side simulations suitable for demonstration purposes. You can add items to the cart from the Home page and view them in the Cart page, then proceed to Checkout.

Copyright 2025 The Daily Grind.