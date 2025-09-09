# Amrendra Yadav — Portfolio

This is a multi-page static portfolio (HTML/CSS/JS) optimized for quick deploy to Netlify or Vercel.

## Setup
1. Replace `assets/resume.pdf` and `assets/favicon.ico`.
2. Update contact form Formspree ID in `contact.html` (action URL).
   - Create a free Formspree form: https://formspree.io
   - Use the provided form endpoint: `https://formspree.io/f/<YOUR_ID>`

## Deploy to GitHub + Netlify
1. `git init && git add . && git commit -m "initial"`
2. Create GitHub repo and `git remote add origin ...` then `git push -u origin main`
3. On Netlify: New site > Import from Git > connect repo > Deploy.
   - Or drag & drop the repo folder into Netlify Sites dashboard.

## Deploy to Vercel
1. Connect Vercel to your GitHub account and import the repo.
2. Deploy (Vercel auto-detects static site).

## Notes
- Theme preference stored in `localStorage`.
- Contact form uses Formspree — no server required.
