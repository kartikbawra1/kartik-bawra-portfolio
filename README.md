# Kartik Bawra — Personal Portfolio

A modern, responsive personal website for Kartik Bawra.

## Stack
- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- No build step / no npm required

## Run locally
Open `index.html` in a browser.

For a local server (recommended), use VS Code Live Server or:
```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Vercel
1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New Project**.
3. Import the GitHub repository.
4. Framework preset: **Other** (or let Vercel detect it).
5. Build Command: leave empty.
6. Output Directory: leave empty / root.
7. Deploy.

## Connect a GoDaddy domain
After deployment, open the Vercel project:
**Settings → Domains → Add Domain**

Enter your GoDaddy domain. Vercel will show the exact DNS records required for your domain.

Then in GoDaddy:
**My Products → Domains → DNS → Manage DNS**

Add/update the records Vercel tells you to use. Do not guess DNS values; use the values shown by Vercel.

## Before publishing
- Change `your-email@example.com` in `index.html` to your real email.
- Optionally add Instagram/LinkedIn links.
- Replace any wording you want to personalize.
- Keep `assets/kartik.jpg` in place so the portrait loads correctly.
