
# Use-Case-Spezifikation

## UC.A.1-Benutzer_regestrieren

### 1. Kurzbeschreibung

| Abschnitt | Inhalt |
|---|---|
| Use-Case-ID | UC.A.1 |
| Name | Benutzer_regestrieren |
| Primärer Akteur | Lagerhalter, Werkstattinhaber, Ersatzteilanbieter |
| Weitere Akteure | - |
| Stakeholder-Ziel(e) | Benutzerkonto erstellen für die Verwaltung der Dienstleistungen |
| Auslösendes Ereignis (Trigger) | Der Benutzer möchte eine Bnutzerkoto anlegen und wählt Registrieren |
| Beschreibung | Ein Benutzer registriert sich auf der VintageCar-Plattform und legt ein Benutzerkonto passend zu seiner Rolle an. |
| Beziehung zu anderen Use Cases | - |

### 2. Vorbedingungen

- Für den Benutzer existiert noch kein Benutzerkonto.
- Das System ist Verfügbar

### 3. Nachbedingungen

- Das Benutzerkonto wurde erfolgreich mit der entsprechenden Rolle erstellt.
- Die Registrierungsdaten sind im System gespeichert

### 4. Hauptszenario

1. Der Benutzer startet die Registrierung, indem er auf den Button „Registrieren“ klickt
2. Das System zeigt die Regestrierungsformular an
3. Der Benutzer trägt seine Registrierungsdaten ein.
4. Der Benutzer gibt seine Rolle ein.
5. Das System überprüft die Eingaben
6. Das System legt ein Benutzerkonto mit der gewählten Rolle an 
7. Das System meldet die erfolgreiche Registrierung zurück

### 5. Alternativszenarien

- 4a. Der Benutzer ändert seine Eingaben, bevor er sie absendet.
  - 4a1. Der Benutzer passt die bereits eingetragenen Registrierungsdaten an.
  - 4a2. Das System übernimmt die Änderungen.
  - 4a3. Weiter mit Schritt 5 Hauptszenario.

### 6. Ausnahmeszenarien

- 5a. Die eingegebenen Registrierungsdaten sind ungültig oder unvollständig.

  - 5a1. Das System erkennt die ungültigen oder fehlenden Eingaben.
  - 5a2. Das System zeigt die entsprechenden Fehlermeldungen an.
  - 5a3. Der Benutzer korrigiert die fehlerhaften Eingaben.
  - Weiter mit Schritt 5 im Hauptszenario.

### 7. Spezielle Anforderungen

- Registrierungsdaten solen nur für berechtigte Nutzer zugänglich sein
- Passwörter sollen als Hash gespeichert werden 
- Bei ungültigen Eingaben verständliche Meldungen anzeigen
- Pflichtfelder eindeutig kennzeichnen

