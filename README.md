# Algorithm Intelligence — GitHub Pages Site

A minimal, fast static site for **algorithmintelligence.store**.

## Files
- `index.html`, `about.html`, `services.html`, `research.html`, `join.html`, `contact.html`
- `404.html` — custom not‑found page (GitHub Pages uses this automatically)
- `styles.css` — shared styles
- `assets/logo.svg` — simple logo

## How to publish (free)
1. Create a new repo (e.g. `algorithmintelligence.store`) and upload all files to the repo **root**.
2. In **Settings → Pages**:
   - *Build and deployment* → **Branch**: `main` and **/ (root)**.
3. Your preview URL will be `https://<username>.github.io/<repo-name>/`.

## Point your domain
1. In **Settings → Pages → Custom domain**, enter `algorithmintelligence.store` and **Save** (this creates/uses a `CNAME` file).
2. In your DNS (registrar or Cloudflare), create:
   - **A** (apex) `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - **CNAME** `www` → `<username>.github.io`
3. Wait for DNS to propagate, then click **Enforce HTTPS** in GitHub Pages.

> Tip: Preview at the GitHub.io URL first by leaving **Custom domain** empty; add it only when DNS is ready.
