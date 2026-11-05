# ShoalsConcrete.com — expanded SEO website package

## What is built
- Responsive branded homepage with supplied circular logo, service cards, project gallery placeholders, interactive guided Larry intake, estimate form, and site visit/live sections.
- 13 detailed, distinct service pages with clear titles, canonical URLs, structured Service JSON-LD, FAQ content, internal links, and conversion links.
- 4 useful concrete education guides and resources index.
- North Alabama service-area page (no fabricated city offices or thin duplicate city pages).
- Dedicated Larry, estimate, calendar, livestream, projects, and privacy pages.
- XML sitemap, robots.txt, Organization structured data, Open Graph metadata, and favicon.

## Important production limitations
- Larry on homepage is a guided *demonstration*, not a generative AI model. Dedicated /larry/ routes to the demonstration. An AI backend, approved pricebook, secure prompt safeguards, and CRM integration are still needed.
- The homepage estimate form computes area and a *starting-rate illustration* only. It opens an email draft to the previously supplied Haraway Contracting Gmail address; the customer must manually send the email. It does not store a lead. The /estimate/ page links to this functional prototype. Implement a secure backend with consent, spam protection, photo uploads, confirmation, and error handling.
- /schedule/ requires a real public booking link. Connect Google Calendar Appointment Schedules (or another supported booking platform) and verify booking privacy. No real appointments are displayed or created.
- /live/ requires an XbotGo or YouTube viewing link. Automatic live status requires a trusted endpoint; do not display LIVE without verifying it.
- The homepage and gallery now use original project photographs from the supplied archive. Confirm photo rights and any customer permissions before publication.
- Confirm legal business name, phone, contact email, office/service area, licenses/insurance statements, and advertised prices before publication.
- $5.25/SF pole barn and $8/SF PEMB rates and optional $250 wash drain are *user-provided advertised starting figures*; verify scope, minimums, exclusions, and feasibility before launch. Do not imply they are firm bids.
- The privacy page is a draft and MUST be replaced with an accurate policy once real integrations are chosen.

## Publishing
Use a static host with clean URL folder support, such as Netlify, Cloudflare Pages, or a correctly configured web host. Upload the full folder, not only index.html. Root-relative paths (`/assets/...`) require hosting at domain root. Set DNS and HTTPS. Configure 404 handling.

## SEO launch plan
1. Verify domain ownership in Google Search Console and submit `https://shoalsconcrete.com/sitemap.xml`.
2. Claim/verify the accurate Google Business Profile, match company name/contact details across site and listings, add real photos, hours, categories, and respond to genuine reviews.
3. Replace illustrative images with original projects; include useful captions, actual location when approved, project type, slab size, scope, and outcomes.
4. Publish genuinely helpful project case studies with permission rather than duplicating generic city landing pages.
5. Verify Core Web Vitals/mobile usability, page indexing, redirects, alt text, form accessibility, and canonical URLs.
6. Track estimate requests, booking conversions, phone calls, and Search Console queries. Improve content based on qualified leads, not keyword repetition.
7. Add live-stream recording recaps and transcripts with real project context where permissions allow.
8. Have the owner review all claims and pricing. Search rankings cannot be guaranteed.

## Sources informing implementation
- Google Search Central SEO Starter Guide: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- Google people-first content guidance: https://developers.google.com/search/docs/fundamentals/creating-helpful-content
- Google Business Profile local ranking guidance: https://support.google.com/business/answer/7091
- XbotGo Chameleon live streaming: https://xb2025.zendesk.com/hc/en-us/articles/5396571156766-XbotGo-Chameleon-Livestream-Methods-and-Setup-Guides


## Photo integration — November 2026
- 39 carefully selected photographs from the uploaded `shoals concrete.zip` are included as optimized WebP assets, used on the homepage, service pages, and filterable projects gallery.
- Images are described by visible content only; locations, measurements, completion dates, and engineering performance have not been invented.
- Original uploads remain unchanged; the source ZIP is not needed to serve the website.
- The livestream is deliberately offline until a verified stream URL is configured.
- Publishing to the public domain requires an authenticated hosting provider and domain DNS setup; building a ZIP does not publish a website.

## Launch blocker
Vercel/hosting and DNS credentials are not connected to this conversation. This is a ready-to-upload static site, not a public deployment. Connect hosting, then verify all customer-facing business contact details and prices before making the domain live.


## V2 additions
- Public consultation hours and date-specific time buttons, with required job address and mailto appointment REQUEST. Not a real-time calendar, not confirmed, no automatic reminders. Google Calendar Appointment Schedules or an authenticated scheduling backend is needed for booking and notifications.
- Larry V1 detailed rules-based cost estimator with category line items, PDF via browser print and CSV spreadsheet download. Uses third-party budget ranges, not confidential Haraway pricebook.
- Fuel/travel formula: $100 per 15 one-way miles, scaled proportionally, zero charge for free site visits. The amount is only billed on completed-work invoices after approval. Must verify routing and terms.
- Live stream page is intentionally OFFLINE with audio mute default, construction-site warning, and configurable URL.
- Site mapping intake with utility/property line prompts; no live satellite imagery or slope API until Google Maps billing and key are configured.
- Expanded business values copy and concrete engraving service details.

## Deployment status
The connected Vercel integration currently exposes read-only project/deployment actions; it does not expose a deployment-create or upload action. This package is not published.
