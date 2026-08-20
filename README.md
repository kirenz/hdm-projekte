# HdM-Projekte

Projektangebote von Prof. Dr. Jan Kirenz an der Hochschule der Medien Stuttgart.

**Website:** <https://kirenz.github.io/hdm-projekte/>

Quarto-Website mit den Projektinformationen für Studierende: pro Semester ein Ordner unter `projekte/`, pro Projekt eine Seite.

## Neues Semester anlegen

1. Ordner `projekte/<semester>/` anlegen (z.B. `ss-2027/`) mit einer `index.qmd` als Übersicht.
2. Pro Projekt `_template/projekt.qmd` dorthin kopieren und ausfüllen.
3. Navbar in `_quarto.yml` auf das neue Semester zeigen lassen, das alte Semester ins Archiv verschieben oder verlinkt lassen.
4. Committen und pushen: GitHub Actions rendert und veröffentlicht automatisch auf `gh-pages`.

## Lokal bauen

```bash
quarto preview
```
