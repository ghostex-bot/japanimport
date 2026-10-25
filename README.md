# japanimport.ch

Statische Webseite für Japan Import (eine Marke von Exotic Cars Schmutz).

- `index.html` – die gesamte Seite (HTML, CSS, JS in einer Datei, DE/EN)
- `netlify.toml` – Hosting-Konfiguration für Netlify (optional)
- `img/` – Fahrzeugfotos (hier ablegen, im HTML referenzieren)

## Online stellen
1. Dieses Repo auf GitHub.
2. Bei Netlify oder Cloudflare Pages «Import from Git» → dieses Repo wählen, Build-Befehl leer, Publish-Verzeichnis `.`.
3. Domain japanimport.ch beim Hosting hinzufügen und die angezeigten DNS-Einträge beim Domain-Anbieter setzen.

Danach ist jeder Push auf `main` nach 1–2 Minuten live.

## Bearbeiten
Texte stehen am Ende von `index.html` im Objekt `T` (de/en). Fahrzeuge sind die `<article class="car">`-Blöcke im Abschnitt `#angebote`.
