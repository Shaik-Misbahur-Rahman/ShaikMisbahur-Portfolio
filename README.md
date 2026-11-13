# Shaik Misbahur Rahman — Portfolio

A responsive, minimal dark-theme portfolio built with plain HTML, CSS and JavaScript.

## Run locally

Open `index.html` in a browser, or run a local static server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Before publishing

1. Add your latest resume PDF at `assets/resume.pdf` (create the `assets` folder).
2. Replace `YOUR_EMAIL_ADDRESS` with your public email address.
3. Replace `YOUR-LINKEDIN-USERNAME` with your actual LinkedIn profile username.
4. Verify project descriptions and repository links before sharing with recruiters.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Framework Preset: **Other**. Build Command: leave empty. Output Directory: `.`.
4. Deploy.
5. In Project → Settings → Domains, add `shaikmisbahur.in` and follow the DNS instructions Vercel displays at your domain registrar.

Keep existing email MX/TXT records. Add or update only the website DNS records Vercel requests. DNS values depend on the Vercel setup shown in your dashboard.
