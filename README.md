# Future Leadership Day Innsbruck 2026 — Location Update

Mobile-first, interaktive One-Page-Seite zur Location-Empfehlung (Saal Friedrich,
Radisson RED Innsbruck) für Ali Mahlodji & Team.

## Als GitHub Page veröffentlichen

1. Neues Repository auf GitHub anlegen (z. B. `leadership-day-innsbruck`), Sichtbarkeit
   **Private** empfehlenswert, da interne Preis- und Kontaktdaten enthalten sind.
2. Diesen kompletten Ordner (inkl. `assets/`) in das Repository pushen:
   ```bash
   git init
   git add .
   git commit -m "Location update: Saal Friedrich"
   git branch -M main
   git remote add origin git@github.com:DEIN-USERNAME/leadership-day-innsbruck.git
   git push -u origin main
   ```
3. Im Repository unter **Settings → Pages** als Quelle `Deploy from a branch`,
   Branch `main`, Ordner `/ (root)` wählen.
4. Nach 1–2 Minuten ist die Seite unter
   `https://DEIN-USERNAME.github.io/leadership-day-innsbruck/` erreichbar.
5. Bei einem **privaten** Repo ist GitHub Pages nur mit GitHub Pro/Team/Enterprise
   öffentlich zugänglich — sonst Repo kurzzeitig auf "Public" stellen oder den Link
   nur direkt (unlisted) teilen.

## Struktur

```
index.html               – die komplette Seite (HTML/CSS/JS, keine externen Abhängigkeiten außer Google Fonts)
assets/img/               – Fotos (Location, Saal, Video-Poster)
assets/video/              – 3 komprimierte Rundgang-Clips (~22 MB gesamt)
```

## Inhalte aktualisieren

Alles liegt in einer einzigen `index.html` (Text, Preise, Termine). Einfach die
gewünschten Stellen anpassen und erneut pushen — GitHub Pages aktualisiert sich
automatisch nach jedem Push auf `main`.
