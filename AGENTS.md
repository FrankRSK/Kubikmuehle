# AGENTS.md - Kubikmühle

## Projekt
3D Vier Gewinnt (Kubikmühle) - statisches Single-File Spiel in `index.html`.

## Architektur
- Gesamte Anwendung in einer Datei: `index.html` (CSS + JS eingebettet)
- Three.js via CDN: `https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js`
- Keine Build-Tools, keine Paketverwaltung, keine Tests

## Entwicklung
- Keine Build/Test/Lint-Commands vorhanden
- Änderungen direkt in `index.html` vornehmen
- Lokal testen: Datei im Browser öffnen oder via Webserver bereitstellen
- Version (0.14) in Titelzeile hardcoded: `3D Vier Gewinnt - Kubikmühle (0.14)`

## Besonderheiten
- KI-Schwierigkeit: 3 Stufen (Einfach=1, Mittel=2, Schwer=3/Strategisch)
- Sound via Web Audio API, Toggle in UI vorhanden
- Unterstützt Desktop (Maus+Scroll) und Mobile (Touch+Pinch)
- `info.txt` enthält Spielbeschreibung, wird nicht vom Code eingebunden
