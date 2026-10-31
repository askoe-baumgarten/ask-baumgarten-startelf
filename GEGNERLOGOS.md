# Gegnerlogos für ASK Baumgarten

Die Gegnerliste wird aus `gegnerlogos.json` geladen. Ein Eintrag ist auf allen Geräten verfügbar, sobald GitHub Pages die Änderung veröffentlicht hat.

## Neuen Gegner hinzufügen

1. Das Gegnerwappen im Repository in den Ordner `gegnerlogos/` hochladen (z. B. `gegnerlogos/ufc-neckenmarkt.png`).
2. `gegnerlogos.json` bearbeiten und den Namen und den Dateipfad hinzufügen:

```json
{
  "gegner": {
    "UFC Neckenmarkt": "gegnerlogos/ufc-neckenmarkt.png"
  }
}
```

3. Änderungen committen und die Website neu laden. Ein Stern ★ markiert Gegner mit einem gemeinsamen Logo.

**Wichtig:** Der Eintrag oben ist nur ein Beispiel. Das Bild muss wirklich im genannten Pfad existieren. Hochladen über die Website speichert ein Logo nur im Browser; GitHub Pages kann ohne zusätzliche Anmeldung und Backend keine Dateien ins Repository schreiben.
