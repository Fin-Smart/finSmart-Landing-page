# FinSmart privacy / legal site

Static site, no build step. Deploy as its own Vercel project (Framework Preset: Other).
The policy shows at `/` and also at `/privacy`.

Before deploying, replace these placeholders (search all files):
- `oratiledineo12@gmail.com` -> your real contact email
-        -> the URL of your deployed landing page, e.g. https://finsmart.vercel.app

Quick way (Mac/Linux):
  sed -i 's#REPLACE_WITH_YOUR_EMAIL#you@example.com#g; s#REPLACE_PROMO_URL#https://finsmart.vercel.app#g' index.html
