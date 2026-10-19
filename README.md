# Echo4ge – spielbare Prototypen

Nur die gebauten Spieldateien (öffentlich). Quellcode, Dokumentation und Originalquellen liegen privat in `IDENTIC-Projects/pr082-game-lab` (`games/echo4ge`, Befehl `npm run build:pages`).

Startseite mit Spielauswahl: https://rasmus33.github.io/echo4ge-play/

- `ai-kimia/` – AI-Kimia 0.7.0 „Das Echo“ mit eigener Stimme je Figur, deinem Echo über viele Läufe, Echoborns Erkenntnis, Regionen mit eigenen Regeln, Tales als Zwischenspielen, Schicksalskarte, Regionswächtern und dem Echo des Tages (Hauptspiel): `ai-kimia/?game=ai-kimia`. In dieser `index.html` zusätzlich Titel und Beschreibung für Link-Vorschauen angepasst.
- `shadow-sprint/` – Shadow Sprint 0.9.11: `shadow-sprint/?game=shadow-sprint` (Level 4 „Drei Spuren“: `&level=4`, Level 5 „Koloss“: `&level=5`, Boss-Test Level 6 „Spiegel“: `&level=6`, Level 7 „Yin und Yang“: `&level=7`)
- `tharos-abrisskommando/` – Tharo’s Abrisskommando 0.1.0 „Stonefall Symphony“ (Rhythmus meets Zerstörung, vier Hallen): `tharos-abrisskommando/?game=tharos-abrisskommando`, direkt in eine Halle `&halle=1` … `&halle=4` (gesperrte Hallen führen ins Menü). In dieser `index.html` zusätzlich Titel und Beschreibung für Link-Vorschauen angepasst.
- `face-off/` – Face/Off – Der Maskenball 0.1.0 (Memory + Bluff, fünf Tänze, „Findest du mich?“-Links mit `#finde=…`): `face-off/?game=face-off`. In dieser `index.html` zusätzlich Titel und Beschreibung für Link-Vorschauen angepasst.
- `nivors-nachtlauf/` – Nivor’s Nachtlauf 0.2.0 „Silent Stride“ (Stealth-Rennen, echte Entscheidungen statt Knopf-Spam, drei Strecken, Mitternachtsmeisterschaft, Freundes-Links mit `#lauf=…`): `nivors-nachtlauf/?game=nivors-nachtlauf`. In dieser `index.html` zusätzlich Titel und Beschreibung für Link-Vorschauen angepasst.
- `mirror-maze/` – Mirror Maze 0.9.0: `mirror-maze/?game=mirror-maze`

Jedes Spiel ist ein eigener Build in seinem Ordner (Inhalt von `dist/`). Einzige Ergänzung: eine Zeile in der `index.html` des Ordners, die ohne `?game=…` zur Startseite zurückführt. Alte Links auf die Startseite mit `?game=…` (auch Herausforderungs-Links mit `#gegner=…`, `#finde=…` bzw. `#lauf=…`) leitet die Startseite in den passenden Ordner weiter.

Aktualisieren: neuen Build eines Spiels in seinen Ordner kopieren, die Weiterleitungszeile in dessen `index.html` wieder einfügen, auf `main` und `gh-pages` pushen.
