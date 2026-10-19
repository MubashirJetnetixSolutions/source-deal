# Source Deals — Original Green Version

Original green-and-copper website, including the homepage and About page. Next.js App Router, React, Tailwind CSS, GSAP and Base UI custom dropdowns. All application code is JavaScript/JSX.

## Run locally

Use Node.js 22.13 or newer. Open a terminal in this folder, then run:

```bash
npm install
npm run dev
```

Visit http://localhost:3000.

## Production

```bash
npm run build
npm start
```

## Vercel

Upload this project to your own Git repository and import it into Vercel. Select the Next.js framework preset, use this folder as the root, and leave the output directory at its default. Build command: `npm run build`. No environment variables are required.

## Main files

- `app/page.jsx`: homepage content and scroll animations
- `app/about/page.jsx`: About page
- `app/globals.css`: design, responsive layouts and dropdown styles
- `components/site/Header.jsx`: floating header and mobile menu
- `components/site/ModernSelect.jsx`: custom dropdown
- `public/images/`: included photography and original logo
- `public/fonts/`: included font

## Current functionality

Property and destination links open the existing sourcedeals.co.uk pages. The enquiry form opens the visitor’s email app with a prepared enquiry; it does not send email through a server. WhatsApp links use the existing business number.
