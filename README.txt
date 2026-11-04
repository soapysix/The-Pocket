The Pocket standalone (for Whop)
index.html      full version (paid members). Reads data.json.
free.html       free version: pick of the week + TD board. Reads data-free.json.
data.json / data-free.json  the picks data. Replace these files to update the site; pages re-read them every 60 seconds.
Host all four files together on any static host (Vercel, Netlify, GitHub Pages), then add the URLs to your Whop as an app/link:
free.html for everyone, index.html behind the paid tier. Static hosting alone cannot lock a page; keep the full URL private or use Whop's gated embed.
Slips are read-only here and never show stake amounts.
