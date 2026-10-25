# FinSmart privacy / legal site

Static site, no build step. Deploy as its own Vercel project (Framework Preset: Other).
The policy shows at `/` and also at `/privacy`.

Before deploying, replace these placeholders (search all files):
- `REPLACE_WITH_YOUR_EMAIL` -> your real contact email
- `REPLACE_PROMO_URL`       -> the URL of your deployed landing page, e.g. https://finsmart.vercel.app

Quick way (Mac/Linux):
  sed -i 's#REPLACE_WITH_YOUR_EMAIL#you@example.com#g; s#REPLACE_PROMO_URL#https://finsmart.vercel.app#g' index.html
