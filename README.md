# Gamers Watchlist

Nintendo Switch reviews, deals & accessories.

## Project Structure

```
gamerswatchlist/
├── index.html          ← Homepage
├── vercel.json         ← Vercel config
├── css/
│   ├── style.css       ← Main styles (shared across all pages)
│   └── article.css     ← Article page styles
├── js/
│   └── main.js         ← Site-wide JS
└── pages/
    └── switch2-review.html   ← Switch 2 review article
```

## Deploy to Vercel (5 minutes)

1. Push this folder to a GitHub repo
2. Go to vercel.com → New Project → Import your repo
3. No build settings needed — it's static HTML
4. Hit Deploy

Your site will be live at a vercel.app URL instantly.
To connect your custom domain (gamerswatchlist.com):
- Vercel Dashboard → Project → Settings → Domains → Add gamerswatchlist.com
- Add the DNS records Vercel gives you to your Porkbun domain settings

## Adding New Articles

1. Copy `pages/switch2-review.html` as your template
2. Update the title, meta description, and content
3. Link the new page from `index.html`
4. Push to GitHub — Vercel auto-deploys on every push

## Adding New Affiliate Links

Replace any `href="#"` placeholder with your actual affiliate link.
Use Pretty Links (when you move to WordPress) to keep them clean:
e.g. gamerswatchlist.com/go/amazon
