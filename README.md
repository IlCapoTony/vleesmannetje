# vleesmannetje.com

Statische landingspagina voor vleesmannetje.com. Plain HTML/CSS/JS, geen build-stap
en geen dependencies.

```
index.html   Landingspagina (CSS en JS inline)
404.html     Foutpagina
assets/img/  Logo, iconen en Open Graph-beeld (AVIF + WebP)
*.pdf        Downloads
robots.txt   Crawl-instructies
sitemap.xml  Sitemap
```

## Lokaal bekijken

```bash
python3 -m http.server 8000
```

Open daarna http://localhost:8000

## Deploy

Elke push naar `main` publiceert de site via GitHub Actions naar GitHub Pages.
