# FinSmart privacy / legal site

Static site, no build step. Deploy as its own Vercel project (Framework Preset: Other).
The policies show at `/` and also at `/privacy`.

## Linking to a document or section

Each document and section has its own URL, so you can link straight to it (for example from the
Google OAuth consent screen or the app stores):

- `/#privacy` - Privacy Policy
- `/#terms` - Terms & Conditions
- `/#google-sms` - Google & SMS Data Policy
- `/#deletion` - Account Deletion Policy
- `/#privacy-09` - a specific section (here: Privacy Policy, section 09 "Deleting your data")

## Contact email

The contact email is `oscar@finsmart.co.za`. To change it, update `CONTACT_EMAIL` in the
`<script>` block of `index.html`, plus the three static `mailto:` links in the sidebar,
`<noscript>` fallback, and footer.

## Editing content

All policy text lives in the `DOCUMENTS` array in `index.html`. When you change a policy,
also update the "Effective" date in that document's `intro` and the "Updated" label in the top bar.
