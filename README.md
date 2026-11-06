# Mohit Sharma — Business Process Improvement & AI Automation

One-page, mobile-responsive, static website for owner-managed businesses in Ahmedabad.

## Offer
- Sell practical business outcomes rather than a particular ERP or AI tool.
- Free introductory discovery call (approximately 20 minutes).
- Process analysis, tailored proposal, implementation and optional ongoing support.
- No public price list: scope and commercial terms are agreed for each engagement.

## Page
- Hero with a clear appointment request CTA
- Short 3-step process
- FAQs
- Discovery call enquiry form and direct email fallback

## Contact behaviour
The current enquiry form opens an email draft addressed to `mohit@mohitsharma.click`; visitors must **send the draft** using their email application. The site does not save enquiries or automatically book appointments. Verify email delivery before campaigns. Replace the mailto flow with the Google Calendar appointment scheduling URL and/or a backed enquiry form when available.

## Deployment
This is a plain `index.html` site with no build dependencies. It deploys automatically from the GitHub `main` branch through the existing Vercel `mohit-business-website` project.

Custom domain: `mohitsharma.click` (and `www` redirect) are already added to the Vercel project. DNS is currently flagged as misconfigured because the external DNS records point away from Vercel. Update **only the relevant web DNS records** in the authoritative DNS provider, preserving MX/TXT and all other email or service records. Re-check domain settings and HTTPS after propagation.

## Next operational steps
1. Test delivery to `mohit@mohitsharma.click` from a separate mailbox.
2. Add a genuine Google Calendar appointment booking page.
3. Replace the email-draft enquiry method with secure direct submission only when a trusted backend and spam protection are configured.
4. Confirm live desktop/mobile accessibility and consent/privacy wording before outreach.
