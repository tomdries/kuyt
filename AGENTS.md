# Kuyt Dreigingsklok

Satirische doomsday clock-website over het scenario dat Dirk Kuyt hoofdtrainer wordt van Feyenoord.

## Project

Één zelfstandig `index.html`-bestand — geen build-tool, geen dependencies. Inline HTML, CSS en JavaScript.

## Layout

1. **Header** — "Het is 12 minuten voor Kuyt"
2. **Klok** — grote SVG-analoge klok (doomsday-stijl) met wijzers op 11:48; de 12 is vervangen door "KUYT"
3. **Nieuwsfeed** — berichten in FR12.nl-stijl, geladen vanuit `articles.csv` (kolommen: `URL`, `Minutes`, `Date`, `Uploaded`). De `Uploaded`-kolom wordt op `1` gezet zodra een artikel in de HTML is opgenomen. De HTML toont per artikel alleen: de titel (gelinkt aan de bron-URL), de score (`+X minuten` of `−X minuten`), en één zin die de score motiveert. Minuten zijn altijd hele minuten.

## Design

- Zwarte achtergrond, dieprode accenten (#cc0000)
- Serif (Georgia) voor koppen, monospace voor nieuws en labels
- Sfeer: Bulletin of the Atomic Scientists, maar dan voor Kuyt
