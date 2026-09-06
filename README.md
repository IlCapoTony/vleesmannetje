# vleesmannetje.com

Statische website voor vleesmannetje.com. Plain HTML/CSS/JS, geen build-stap.

```
index.html              Homepage
assets/css/style.css    Styling
assets/img/             Afbeeldingen
files/                  PDF's en downloads
```

## Lokaal bekijken

```bash
python3 -m http.server 8000
```

Open daarna http://localhost:8000

## Deploy

Elke push naar `main` publiceert de site via GitHub Actions naar GitHub Pages.
