# Kellerer Legal – Website

**Live-Domain:** https://kellerer-legal.com

## Deployment (GitHub Pages)
1. Neues Repo `kellerer-legal` anlegen (public).
2. `index.html`, `portrait.jpg`, `CNAME`, `.nojekyll` hochladen (Root des Repos).
3. Settings → Pages → Source: Deploy from branch → Branch: main → /(root).
4. Custom domain setzen: `kellerer-legal.com` → Enforce HTTPS aktivieren.

## DNS bei Porkbun
A-Records (@):
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

CNAME:
- Host: `www` → `DEIN_GITHUB_USERNAME.github.io`

## Inhalte anpassen
- Impressum (Kammer, Berufshaftpflicht, USt-ID falls vorhanden).
- Optional: Google-Fonts lokal hosten.
