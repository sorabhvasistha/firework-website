# Classic Fireworks Website

A clean, promotional two-page website for a fireworks company focused on lead generation and client inquiries.

## Overview

This project is designed to help a fireworks company present a polished online presence while encouraging visitors to submit an intake form for event inquiries. The site balances festive visuals with a professional layout and is built to be easy to edit in WordPress or adapted into a production-ready front-end.

## Project Goals

- Showcase the company’s long-standing experience in pyrotechnics
- Present a strong hero section on the home page with a lead form
- Highlight service offerings and past display themes on the second page
- Capture event inquiry details such as name, phone, email, date, venue size, and message
- Provide a clean, mobile-friendly responsive layout
- Use placeholders where branded assets are still pending

## Pages

### Page 1: Home / Lead Capture

This is the primary conversion page.

Features include:
- Bold hero banner with fireworks imagery
- Messaging that emphasizes decades of experience and expertise
- A client intake form capturing:
  - Full name
  - Phone number
  - Email address
  - Event date
  - Venue size
  - Message / event details
- Form submission handling designed to route inquiries to the business inbox

### Page 2: Services / Showcases

This page expands on the company’s offerings and visual range.

Features include:
- Service highlights for weddings, corporate events, and public celebrations
- Display photography or placeholder imagery
- Clear calls-to-action encouraging users to inquire or call
- A return path to the intake form for conversion

## Folder Structure

```text
firework-website/
├── index.html
├── index1.html
├── index2.html
├── index3.html
├── index4.html
├── index5.html
├── styles.css
├── assets/
│   ├── banner1.png
│   ├── banner2.png
│   ├── banner3.png
│   ├── classiclogo.png
│   └── ...
├── README.md
└── .git/
```

## Technologies

- HTML5
- CSS3
- Bootstrap 5
- Light JavaScript for form behavior and view switching
- External Google Fonts and image assets

## Setup

1. Open the project folder in a browser directly, or use a local web server if preferred.
2. Make sure all assets in the `assets/` folder are present.
3. If you are placing this into WordPress, convert the HTML sections into theme blocks or a custom page template as needed.

## Notes for WordPress Use

- The markup is structured cleanly enough to be adapted into a WordPress page or custom template.
- Replace placeholder images with final branding and event photography.
- Update the form action logic or email routing once production email settings are available.
- Keep the Bootstrap CDN link unless the site is being fully embedded into a self-hosted setup.

## Recommended Next Steps

- Replace placeholder logos and photos with final branded assets
- Refresh the logo design in a dedicated brand pass
- Connect the intake form to a production email service or form handler
- Review mobile behavior and spacing on all breakpoints
- Finalize the website copy and service wording for business tone

## Form Behavior

The intake form is designed to collect lead information and can be connected to an email backend or a form-processing service. For production use, the form should be wired to a real server endpoint or email integration.

## Branding Direction

This project follows a festive but professional direction:
- warm gold accents
- dark premium backgrounds
- fireworks imagery
- clean typography and strong hero emphasis

## License

This project is intended for client work and can be adapted for business use.

## Contact

For ongoing edits or production handoff, update the business details, form email target, and final assets before deployment.
