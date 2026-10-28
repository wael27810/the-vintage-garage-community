# Use-Case-Liste

The Vintage Car Garage Community – initialer Entwurf für das Pflichtenheft.

## 1.1 Lagerhalter

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.L.1 | Als Lagerhalter registrieren und grundlegende Informationen hinterlegen | StR.L.1 |
| UC.L.2 | Lagerstandort, Anschrift und Einlagerungskosten erfassen und pflegen | StR.L.1 |
| UC.L.3 | Servicezeiten und Lagerbedingungen festlegen und verwalten | StR.L.1 |
| UC.L.4 | Verschiedene Einlagerungsservices anbieten und verwalten | StR.L.2 |
| UC.L.5 | Verfügbare Stellplätze nach Kategorie angeben und aktualisieren | StR.L.3 |
| UC.L.6 | Spezialisierung auf Fahrzeugmarken aus einer vorgegebenen Liste festlegen | StR.L.4 |
| UC.L.7 | Aktuelle Informationen zur Fahrbereitschaft und zum Wartungsstand eines eingelagerten Fahrzeugs bereitstellen | StR.L.5 |
| UC.L.8 | Reparatur- oder Wartungsanfrage an eine registrierte Werkstatt in der Nähe senden | StR.L.6, StR.W.3 |
| UC.L.9 | Reparatur- oder Wartungstermin mit einer Werkstatt vereinbaren | StR.L.7 |

## 1.2 Einlagerer

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.E.1 | Geeignete Stellplätze in unterstützten deutschen Großstädten suchen | StR.E.1 |
| UC.E.2 | Standortinformationen, Lagerbedingungen und verfügbare Stellplätze einsehen | StR.E.2 |
| UC.E.3 | Angebotene Einlagerungsservices und zugehörige Konditionen einsehen | StR.E.2 |
| UC.E.4 | Standortdetails und individuelles Angebot beim Lagerhalter anfragen | StR.E.3 |
| UC.E.5 | Einlagerungsangebot annehmen oder ablehnen | StR.E.4 |
| UC.E.6 | Ersatz- und Zubehörteile für das eigene Fahrzeug anzeigen lassen | StR.E.5 |
| UC.E.7 | Termine zur Fahrzeugannahme und Fahrzeugrückgabe mit dem Lagerhalter vereinbaren | StR.E.6 |
| UC.E.8 | Zusätzliche Einlagerungsservices beim Lagerhalter buchen | StR.E.7 |
| UC.E.9 | Ersatz- oder Zubehörteil reservieren | StR.EA.3 |

## 1.3 Werkstatt

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.W.1 | Als Werkstattinhaber registrieren und grundlegende Werkstattinformationen hinterlegen | StR.W.1 |
| UC.W.2 | Angebotene Arbeiten und Spezialisierungen auf Fahrzeughersteller angeben und verwalten | StR.W.2 |
| UC.W.3 | Reparaturanfragen von Lagerhaltern einsehen und bearbeiten | StR.W.3 |
| UC.W.4 | Reparatur- oder Wartungstermine mit Lagerhaltern vereinbaren | StR.L.7 |

## 1.4 Ersatzteilanbieter

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.EA.1 | Als Ersatzteilanbieter für Oldtimer und Youngtimer registrieren und Unternehmensinformationen hinterlegen | StR.EA.1 |
| UC.EA.2 | Unternehmensinformationen pflegen | StR.EA.1 |
| UC.EA.3 | Ersatz- oder Zubehörteile mit relevanten Artikelinformationen anbieten | StR.EA.2 |
| UC.EA.4 | Angebotene Ersatz- oder Zubehörteile löschen | StR.EA.2 |
| UC.EA.5 | Reservierungen für angebotene Ersatz- und Zubehörteile einsehen und bearbeiten | StR.EA.3 (Ergänzung) |

## Offene Punkte

- Das Einsehen und Bearbeiten von Reparaturanfragen durch Werkstätten ist eine Konkretisierung von StR.W.3.
- Das Verwalten von Reservierungen durch Ersatzteilanbieter ist eine ergänzende Funktion zu StR.EA.3 und muss mit dem Auftraggeber abgestimmt werden.
- Die nachträgliche Pflege von Stammdaten sowie die genauen Abläufe zur Terminvereinbarung sind zu klären.
