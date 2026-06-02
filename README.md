# BudOS Website

Single-page marketing site for **BudOS** — custom software & websites for cannabis dispensaries and cultivators.

- **Domain:** budos.co
- **Stack:** Single `index.html` — vanilla HTML/CSS/JS, no frameworks, no build step.
- **Fonts:** Plus Jakarta Sans + DM Mono (Google Fonts)

## Deploy

This is a zero-build static site. Deploy anywhere:

- **Vercel:** Import the repo (or drag the folder into the dashboard). No config needed.
- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root.

To point `budos.co` at it, add a `CNAME` file containing `budos.co` and update DNS.

## Before launch — swap these placeholders

- `https://calendly.com/YOUR_LINK` → real Calendly booking URL (appears ~6×)
- Contact email is currently `tpillay710@gmail.com`

Find & replace across `index.html`:

```bash
sed -i '' 's|https://calendly.com/YOUR_LINK|https://calendly.com/your-real-link|g' index.html
```
