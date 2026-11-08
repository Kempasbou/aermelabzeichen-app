# Ärmelabzeichen – Oberfläche

Einfache Web-Seite (GitHub Pages) für die Ärmelabzeichen-Sammlung.

- **Foto prüfen**: ein oder mehrere Abzeichen fotografieren → Claude bestimmt Ort, Bundesland und Regierungsbezirk und gleicht mit der Liste ab (neu / schon vorhanden / vermutlich mit Begründung).
- **Aufnehmen**: angehakte Abzeichen werden in die Liste geschrieben (neue Zeile bzw. Anzahl +1), Einzelbilder werden ausgeschnitten und gespeichert.
- **Liste herunterladen**: aktuelle Liste als CSV (öffnet in Excel).

Die Daten liegen im privaten Repo `Kempasbou/aermelabzeichen`; diese Seite enthält keine Daten und keine Schlüssel.

## Einrichtung (einmal pro Gerät)

Unter „Einstellungen“ eintragen – wird nur im Browser des Geräts gespeichert:

1. **Anthropic-Schlüssel** aus console.anthropic.com (API Keys).
2. **GitHub-Schlüssel**: Fine-grained Personal Access Token, *Repository access* nur `aermelabzeichen`, *Permissions → Contents: Read and write*.
