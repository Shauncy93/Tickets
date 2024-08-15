# Tickets
Tickets Validierung
# Ticket-Validator

Dieses Projekt ist ein QR-Code-basierter Ticket-Validator, der Registrierungsnummern gegen ein Google Spreadsheet überprüft.

## Funktionsweise

1. Der Benutzer scannt einen QR-Code, der eine Registrierungsnummer enthält.
2. Die App sendet diese Nummer an ein Google Apps Script.
3. Das Script überprüft, ob die Nummer in einem der beiden spezifizierten Sheets des Google Spreadsheets vorhanden ist.
4. Das Ergebnis (gültig/ungültig) wird an die App zurückgesendet und angezeigt.

## Technologie-Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Google Apps Script
- Datenbank: Google Sheets

## Setup

1. Klonen Sie dieses Repository.
2. Stellen Sie sicher, dass Sie Zugriff auf das verknüpfte Google Spreadsheet haben.
3. Konfigurieren Sie das Google Apps Script wie in der Dokumentation beschrieben.
4. Aktualisieren Sie die `apiUrl` in der `index.html`-Datei mit der URL Ihres bereitgestellten Google Apps Scripts.
5. Hosten Sie die `index.html`-Datei auf einem Webserver Ihrer Wahl (z.B. GitHub Pages).

## Nutzung

Öffnen Sie die gehostete `index.html`-Datei in einem modernen Webbrowser auf einem Gerät mit Kamera. Scannen Sie einen QR-Code, der eine gültige Registrierungsnummer enthält.

## Beitragen

Beiträge zu diesem Projekt sind willkommen. Bitte öffnen Sie ein Issue oder einen Pull Request, wenn Sie Verbesserungen vorschlagen möchten.

## Lizenz

[Fügen Sie hier Ihre gewählte Lizenz ein]
