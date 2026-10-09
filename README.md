# Echo4ge – spielbare Prototypen

Nur die gebauten Spieldateien (öffentlich). Quellcode, Dokumentation und Originalquellen liegen privat in `IDENTIC-Projects/pr082-game-lab` (`games/echo4ge`, Befehl `npm run build:pages`).

Startseite mit Spielauswahl: https://rasmus33.github.io/echo4ge-play/

- `shadow-sprint/` – Shadow Sprint 0.9.7: `shadow-sprint/?game=shadow-sprint` (Level 4 „Drei Spuren“: `&level=4`)
- `mirror-maze/` – Mirror Maze 0.9.0: `mirror-maze/?game=mirror-maze`

Jedes Spiel ist ein eigener Build in seinem Ordner (Inhalt von `dist/`). Einzige Ergänzung: eine Zeile in der `index.html` des Ordners, die ohne `?game=…` zur Startseite zurückführt. Alte Links auf die Startseite mit `?game=…` (auch Herausforderungs-Links mit `#gegner=…`) leitet die Startseite in den passenden Ordner weiter.

Aktualisieren: neuen Build eines Spiels in seinen Ordner kopieren, die Weiterleitungszeile in dessen `index.html` wieder einfügen, auf `main` und `gh-pages` pushen.
