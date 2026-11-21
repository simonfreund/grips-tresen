# GRIPS Tresen Website

Statische Website für https://grips-tresen.de, vorbereitet für GitHub Pages.

## Dateien

- `index.html`: Startseite mit animiertem Logo und Link zur Karte.
- `karte.html`: Speise- und Getränkekarte mit allen Mengen, Preisen und Hinweisen.
- `styles.css`, `karte.css`: gemeinsame Gestaltung und Kartenlayout.
- `assets/`: GRIPS-Logo in Normal- und Blinzelzustand.
- `downloads/GRIPS_Tresen_Preisliste_A4.pdf`: Preisliste zum Ansehen und Herunterladen.
- `fonts/`: lokal eingebundene Rois Bold sowie Zine Sans Display OT Regular und Bold.
- `.nojekyll`: direktes Ausliefern der statischen Dateien ohne Jekyll-Verarbeitung.

## Herkunft

Am 20. November 2026 aus dem veröffentlichten Netlify-Deploy `6a5e5012bb60b07b4f89a8fa` gesichert.
Das Originalarchiv liegt außerhalb dieses Repositorys im Projektordner unter `backups/`.

## Lokal ansehen

Im Repository-Ordner `python3 -m http.server 8080` ausführen und http://localhost:8080 öffnen.

## Geplantes Hosting

GitHub Pages: Branch `main`, Verzeichnis `/ (root)`.
Domain: `grips-tresen.de`. Die Domain wird erst nach Abstimmung umgestellt.
Es werden keine Build-Werkzeuge, Pakete oder zusätzlichen Hosting-Dienste benötigt.

Vor Änderungen an der produktiven Website ist eine Abstimmung erforderlich.
Die Speise- und Getränkekarte steht in `karte.html` als HTML und weiterhin als PDF-Download bereit.
