# Afza Subhani — Updated Portfolio

Open `index.html` to preview the design and project gallery. For **working contact form delivery**, deploy the complete folder to Vercel (static site + `api/contact.js`). Set these environment variables in Vercel:

- `RESEND_API_KEY` — your Resend API key
- `CONTACT_TO_EMAIL` — the developer’s testing inbox, later replace with the portfolio owner's inbox
- `CONTACT_FROM_EMAIL` — a verified sender address in your Resend account (for example, `Portfolio <hello@your-verified-domain.com>`)

**No real messages can be delivered until the variables and sender domain are configured.** Opening the HTML locally will not run the API endpoint. Test after deployment. Do not place API keys in HTML or commit them. For production add rate limiting / CAPTCHA at the endpoint.

The PDF resume is included. Resume contents are based on supplied descriptions, not independently verified employment history. The brand guidelines PDF contains sample/template wording; do not treat it as a confirmed commercial case study. The project gallery includes all 16 Behance files, 6 other design images, 7 Instagram screenshots, and the PDF. Original file names are preserved in asset paths. No video files were present in the ZIP.

## Latest revisions
- Work grid uses compact uniform cards and `object-fit: contain` to prevent cropping landscape or portrait designs. Open a card to see the full image.
- Instagram insight cards now show figures visible in the supplied screenshots; views and reach are not described as growth percentages.
- Resume buttons download the supplied `GD 2026 resume.pdf` (renamed to `Afza_Subhani_Resume.pdf`).
- Testing recipient defaults to `codewithhanna@gmail.com` unless `CONTACT_TO_EMAIL` is set. Email sending still requires `RESEND_API_KEY`, `CONTACT_FROM_EMAIL`, and deployment with the API endpoint.
- Resume states Visual Arts Institute for the graphic-design certification, whereas the portfolio certificate section says NED Academy. Verify the issuing institution before publication.
