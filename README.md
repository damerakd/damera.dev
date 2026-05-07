# damera.dev

Personal site. Plain HTML + CSS, no build step.

Deploys to GitHub Pages on every push to `main` via `.github/workflows/deploy.yml`.

## Local preview

Open `index.html` in a browser, or:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Custom domain

`CNAME` pins the site to `damera.dev`. DNS is managed in Cloudflare.
