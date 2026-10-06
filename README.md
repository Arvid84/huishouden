# Huishouden

Webapp voor iPhone: per dag één was, maximaal 30 minuten opruimen en maximaal 30 minuten schoonmaken. Werkt offline nadat je hem één keer hebt geopend.

**Adres:** https://arvid84.github.io/huishouden/

## Op je iPhone zetten

1. Open het adres in **Safari**.
2. Tik op **Deel** → **Zet op beginscherm** → **Voeg toe**.
3. Open de app voortaan via het icoon. Afvinken wordt op je telefoon bewaard.

## Iets aanpassen

- Taken, tijden en frequenties staan als data in `index.html` (zoek op `"tasks":`).
- Na een wijziging: verhoog `VERSION` in `sw.js` (bijv. `v2`), anders blijft je telefoon de oude versie uit de cache tonen. De nieuwe versie verschijnt de tweede keer dat je de app opent.
