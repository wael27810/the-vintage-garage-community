
# Use-Case-Liste



### 1.1 Lagerhalter

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.L.1 | Der Lagerhalter erstellt ein Konto und hinterlegt seine grundlegenden Informationen | StR.L.1 | 
| UC.L.2 | Standort, Anschrift (Adresse des Lagerstandort) und Einlagerungskosten erfassen und pflegen.  | StR.L.1 |
| UC.L.3 | Servicezeiten und Lagerungsbedingungen festlegen, erfassen und verwalten.| StR.L.1 |
| UC.L.4 | Verschiedene Einlagerungsservices anbieten und verwalten | StR.L.2 |
| UC.L.5 | Verfügbare Stellplätze nach Kategorie angeben und aktualisieren| StR.L.3 |
| UC.L.6 | Spezialisierung auf Fahrzeugmarken aus einer vorgegebenen Liste festlegen. | StR.L.4 |
| UC.L.7 | Aktuelle Informationen zur Fahrbereitschaft und zum Wartungszustand eines eingelagerten Fahrzeugs bereitstellen | StR.L.5 |
| UC.L.8 | Eine Anfrage für Reparaturen oder Wartungsarbeiten an eine registrierte Werkstatt in der Nähe senden. | StR.L.6, StR.W.3 |
| UC.L.9  | Einen Termin für die Reparatur - oder Wartungsarbeiten mit einer Werkstatt vereinbaren. | StR.L.7 |


### 1.2 Einlagerer

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.E.1 | Geeignete Stellplätze in unterstützten deutschen Großstädten suchen | StR.E.1 |
| UC.E.2 | Einlagerern können Anschrift, Merkmale zum Lagerstandort, Lagerbedingungen, Anzahl an freie Stellplätze einsehen.  | StR.E.2 |
| UC.E.3 | Die Suchergebnisse zeigen den Einlagerer die angebotene Services mit den entsprechenden Konditionen, die vor Ort angeboten wird.   | StR.E.2 |
| UC.E.4 | 	Standortdetails und individuelles Angebot beim Lagerhalter anfragen | StR.E.3 |
| UC.E.5 | Einlagerungsangebot annehmen oder ablehnen | StR.E.4 |
| UC.E.6 | Ersatz- und Zubehörteile von Ersatzteilhändlern für das Fahrzeug anzeigen | StR.E.5 |
| UC.E.7 | Termine zur Fahrzeugannahme und Fahrzeugrückgabe mit dem Lagerhalter vereinbaren | StR.E.6 |
| UC.E.8 | Zusätzliche Einlagerungsservices von Lagerhalter buchen | StR.E.7 |
| UC.E.9 | Ersatz- oder Zubehörteil reservieren | StR.EA.3 |

### 1.3 Werkstatt

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.W.1 |  Ein Werkstattinhaber erstellt ein Konto und hinterlegt Informationen zu der Werkstatt und Unternehmen. | StR.W.1 |
| UC.W.2 | Angebotenes Leistungen und Spezialisierungen angeben und verwalten | StR.W.2 |
| UC.W.3 | Reparaturanfragen von Lagerhatern einsehen und bearbeiten. | StR.W.3 |
| UC.W.4 | Mit dem Lagerhalter Termine für angefragte Reparatur- und Wartungsarbeiten vereinbaren. | StR.W.3, StR.L.7 |


### 1.4 Ersatzteilanbieter

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.EA.1 | Ein Ersatzteilhändler erstellt ein Konto als  Oldtimer / Youngtimer und hinterlegt die Unternehmensinformationen. | StR.EA.1 |
| UC.EA.2 | Unternehmensinformationen einstellen | StR.EA.1 |
| UC.EA.3 | Ersatz- oder Zubehörteil anbieten | StR.EA.2 |
| UC.EA.4 | Ersatz- oder Zubehörteil aus Angebot löschen | StR.EA.2 |
| UC.EA.5 | Reservierungen für angebotene Artikel einsehen und bearbeiten. Dieser Use Case ist aus Anbietersicht sinnvoll, wird aber nicht ausdrücklich als eigene Funktion beschrieben. | StR.EA.3 |


