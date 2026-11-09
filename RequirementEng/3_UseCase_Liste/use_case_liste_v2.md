
# Use-Case-Liste


### Allgemeine Use Case

| Use-Case-ID | Use Case | Referenz |
|---|---|---|
| UC.A.1 | Benutzer registrieren | StR.L.1 , StR.W.1 , StR.EA.1 |
| UC.A.2 | Benutzer anmelden | StR.L.1 , StR.W.1 , StR.EA.1 |


### 1.1 Lagerhalter

| Use-Case-ID | Use Case | Beschreibung | Referenz |
|---|---|---|---|
| UC.L.2 |Lagerstandort verwalten | Standort, Anschrift (Adresse des Lagerstandort) und Einlagerungskosten erfassen und pflegen.  | StR.L.1 |
| UC.L.3 | Lagerbedingungen verwalten | Servicezeiten und Lagerungsbedingungen festlegen, erfassen und verwalten.| StR.L.1 |
| UC.L.4 | Einlagerungsservices verwalten | Verschiedene Einlagerungsservices anbieten und verwalten | StR.L.2 |
| UC.L.5 | Stellplatzkapazitäten verwalten | Verfügbare Stellplätze nach Kategorie angeben und aktualisieren| StR.L.3 |
| UC.L.6 | Spezialisierte Fahrzeugmarken verwalten | Spezialisierung auf Fahrzeugmarken aus einer vorgegebenen Liste festlegen. | StR.L.4 |
| UC.L.7 | Fahrbereitschaft und Wartungsstand aktualisieren | Aktuelle Informationen zur Fahrbereitschaft und zum Wartungszustand eines eingelagerten Fahrzeugs bereitstellen | StR.L.5 |
| UC.L.8 | Reparatur- oder Wartungsanfrage erstellen | Eine Anfrage für Reparaturen oder Wartungsarbeiten an eine registrierte Werkstatt in der Nähe senden. | StR.L.6, StR.W.3 |
| UC.L.9  | Werkstatttermin vereinbaren | Einen Termin für die Reparatur - oder Wartungsarbeiten mit einer Werkstatt vereinbaren. | StR.L.7 |


### 1.2 Einlagerer

| Use-Case-ID | Use Case | Beschreibung | Referenz |
|---|---|---|---|
| UC.E.1 | Stellplätze suchen | Geeignete Stellplätze in unterstützten deutschen Großstädten suchen | StR.E.1 |
| UC.E.2 | Standortdetails anzeigen | Einlagerern können Anschrift, Merkmale zum Lagerstandort, Lagerbedingungen, Anzahl an freie Stellplätze einsehen. | StR.E.2 |
| UC.E.3 | Suchergebnisse anzeigen | Die Suchergebnisse zeigen den Einlagerer die angebotene Services mit den entsprechenden Konditionen, die vor Ort angeboten wird.   | StR.E.2 |
| UC.E.4 | Anfrage an Lagerhalter stellen |	Standortdetails und individuelles Angebot beim Lagerhalter anfragen | StR.E.3 |
| UC.E.5 | Angebot annehmen oder ablehnen | Einlagerungsangebot annehmen oder ablehnen | StR.E.4 |
| UC.E.6 | Ersatz- und Zubehörteile anzeigen | Ersatz- und Zubehörteile von Ersatzteilhändlern für das Fahrzeug anzeigen | StR.E.5 |
| UC.E.7 | Fahrzeugübergabe und -rückgabe terminieren | Termine zur Fahrzeugannahme und Fahrzeugrückgabe mit dem Lagerhalter vereinbaren | StR.E.6 |
| UC.E.8 | Zusätzliche Services buchen | Zusätzliche Einlagerungsservices von Lagerhalter buchen | StR.E.7 |
| UC.E.9 | Ersatz- oder Zubehörteil reservieren | Ersatz- oder Zubehörteil reservieren | StR.EA.3 |

### 1.3 Werkstatt

| Use-Case-ID | Use Case | Beschreibung | Referenz |
|---|---|---|---|
| UC.W.2 | Leistungsangebot verwalten | Angebotene Leistungen und Spezialisierungen angeben und verwalten | StR.W.2 |
| UC.W.3 | Reparaturanfragen empfangen und bearbeiten | Reparaturanfragen von Lagerhaltern einsehen und bearbeiten. | StR.W.3 |
| UC.W.4 | Werkstatttermine abstimmen | Mit dem Lagerhalter Termine für angefragte Reparatur- und Wartungsarbeiten vereinbaren. | StR.W.3, StR.L.7 |


### 1.4 Ersatzteilanbieter

| Use-Case-ID | Use Case | Beschreibung | Referenz |
|---|---|---|---|
| UC.EA.2 |  Unternehmensinformationen einstellen | Der Ersatzteilanbierter kann sich registrieren| StR.EA.1 |
| UC.EA.3 | Ersatz- oder Zubehörteil anbieten | Verfügbare Ersatz- oder Zubehörteile werden angeboten | StR.EA.2 |
| UC.EA.4 | Ersatz- oder Zubehörteil aus Angebot löschen | Nicht verfügbare Ersatz- oder Zubehörteile werden nicht mehr angeboten | StR.EA.2 |
| UC.EA.5 | Artikelreservierungen verwalten | Reservierungen für angebotene Artikel einsehen und bearbeiten. Dieser Use Case ist aus Anbietersicht sinnvoll, wird aber nicht ausdrücklich als eigene Funktion beschrieben. | StR.EA.3 |


