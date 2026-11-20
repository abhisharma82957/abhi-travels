# Abhi Tour & Travels — Next.js Website

## Run locally
1. Install Node.js 20 or newer.
2. Run `npm install`.
3. Run `npm run dev`.
4. Open http://localhost:3000.

## Deploy to Vercel
Push this folder to GitHub and import the repository in Vercel. Set `NEXT_PUBLIC_SITE_URL` to your final domain (for example `https://yourdomain.com`) in Vercel Environment Variables, then redeploy.

## Features
- Home, About, Services, Blog and Contact pages
- Six individual service landing pages
- Three editable blog articles
- Mobile-responsive navigation and layouts
- WhatsApp enquiry form (opens WhatsApp; no backend storage)
- Click-to-call and email links
- Dynamic sitemap, robots.txt, per-page metadata and TravelAgency structured data

## Edit content
- Business details, services and blog posts: `lib/data.js`
- Site design: `app/globals.css`
- Homepage: `app/page.jsx`

## Before launch
- Replace the example domain with your real domain.
- Confirm all listed services are actually offered; adjust content if necessary.
- Add your own licensed destination photos if desired.
- Verify phone/email, test WhatsApp on mobile, and submit `/sitemap.xml` to Google Search Console.
- Travel pricing, availability and booking are handled by direct enquiry, not automatic checkout.
