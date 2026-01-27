# ToolHub (statische Mini-Tools)

Kleine, schnelle Rechner & Tools (HTML/CSS/JS), optimiert für Mobile und SEO.

## Live (Cloudflare Pages)
Dieses Repo ist für Cloudflare Pages gedacht:
- Framework: **None**
- Build command: **(leer)**
- Output directory: **/**

## Struktur
- `/` → Hub-Startseite
- Jede Tool-Seite als eigener Ordner mit `index.html`:
  - `/ei-rechner/`
  - `/mischverhaeltnis/`
  - `/steakandbread-timer/`
  - `/abokosten-rechner/`

SEO Dateien:
- `/sitemap.xml`
- `/robots.txt`
- `/_redirects` (für 301 Redirects / Aliases)

## Deployment (Kurz)
1. Repo auf GitHub pushen
2. Cloudflare → Pages → Create project → GitHub Repo auswählen
3. Deploy
4. Optional später: eigene Domain unter Pages → Custom Domains verbinden

## Hinweise
- Canonical URLs und `sitemap.xml` auf die echte Domain umstellen, sobald vorhanden.
- Kein SPA-Router: Jede Seite ist statisch erreichbar (SEO).
