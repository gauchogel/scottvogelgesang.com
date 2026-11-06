# scottvogelgesang.com

Personal homepage. Plain static files, no build step, hosted on Cloudflare Pages.

| File | Purpose |
|---|---|
| `index.html` | The page: name, title, links, System/Light/Dark theme |
| `404.html` | Served by Pages for unknown paths |
| `_headers` | Security headers Cloudflare Pages applies to every response |
| `favicon.svg`, `apple-touch-icon.png` | Browser tab and iOS home-screen icons |
| `robots.txt` | Allow indexing |

## Deploying

Cloudflare Pages is connected to this repo: every push to `main` deploys automatically.
Build settings: **no framework, no build command, output directory `/`**.

To preview locally:
```bash
python3 -m http.server 8000
```
then open http://localhost:8000.
