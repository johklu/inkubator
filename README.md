# Inkubator-Register

Demo eines gemeinsamen Registers für Zellkultur-Inkubatoren: Wer züchtet gerade
welche Zelllinie auf welcher Ebene, und was ist als Nächstes fällig?

*English: demo of a shared register for cell culture incubators. The app itself
can be switched between German and English.*

## Stand: Demo

Die Demo ist eine einzelne Datei, `index.html`. Sie braucht keinen Server und
keine Installation: Datei im Browser öffnen genügt.

- Die Daten sind Beispieldaten mit erfundenen Personen.
- Änderungen werden nur im jeweiligen Browser gespeichert (`localStorage`).
  Es gibt noch **keine** gemeinsame Datenbank und **kein** Login. Die Auswahl
  „Angemeldet als“ simuliert nur, wie es mit mehreren Personen aussieht.

## Was die Demo zeigt

- **Inkubatoren**: jeder Inkubator mit seinen Ebenen, jede Kultur als Kachel
  an ihrem Platz, farblich markiert nach Fälligkeit.
- **Liste**: alle Kulturen als Tabelle, auch die bereits entnommenen.
- **Verlauf**: wer hat wann was gemacht.
- **Kultur eintragen / bearbeiten**: Zelllinie, Passage, Gefäß und Anzahl,
  Medium und Zusätze, Standort, verantwortliche Person, Projekt, nächste Aktion
  mit Datum, Mykoplasmen-Test, Sicherheitsstufe, Notizen.
- **Protokollieren**: Mediumwechsel, Passage, Kontrolle (mit Konfluenz), Notiz,
  Entnahme mit Grund.
- **Sprache**: Deutsch und Englisch, umschaltbar oben rechts.

## Nächste Schritte (nach der Demo)

Gemeinsame Datenbank und Server, Login und Rechte, Datenschutz, Erreichbarkeit
im Institutsnetz bzw. von außen.
