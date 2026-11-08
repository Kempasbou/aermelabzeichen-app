# Ärmelabzeichen – Oberfläche

Einfache Web-Seite (GitHub Pages) für die Ärmelabzeichen-Sammlung.

- **Foto prüfen**: ein oder mehrere Abzeichen fotografieren → Claude bestimmt Ort, Bundesland und Regierungsbezirk und gleicht mit der Liste ab (neu / schon vorhanden / vermutlich mit Begründung).
- **Aufnehmen**: angehakte Abzeichen werden in die Liste geschrieben (neue Zeile bzw. Anzahl +1), Einzelbilder werden ausgeschnitten und gespeichert.
- **Liste herunterladen**: aktuelle Liste als CSV (öffnet in Excel).

Die Daten liegen im Repo `Kempasbou/aermelabzeichen`; diese Seite enthält keine Daten und keine Schlüssel.

## Einrichtung (einmal pro Gerät)

Beide Schlüssel sind freiwillig (unter „Einstellungen“, nur im Browser des Geräts gespeichert). Ohne Schlüssel: nur Liste ansehen und herunterladen.

1. **Anthropic-Schlüssel** (console.anthropic.com → API Keys) – schaltet „Foto prüfen“ frei.
2. **GitHub-Schlüssel** – schaltet „Aufnehmen“ frei: Fine-grained Personal Access Token, *Repository access* nur `aermelabzeichen`, *Permissions → Contents: Read and write*.
