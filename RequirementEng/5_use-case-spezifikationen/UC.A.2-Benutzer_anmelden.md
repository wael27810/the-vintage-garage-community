
# Use-Case-Spezifikation

## UC.A.2-Benutzer_anmelden

### 1. Kurzbeschreibung

| Abschnitt | Inhalt |
|---|---|
| Use-Case-ID | UC.A.2 |
| Name | Benutzer_anmelden |
| Primärer Akteur | Lagerhalter, Werkstattinhaber, Ersatzteilanbieter |
| Weitere Akteure | - |
| Stakeholder-Ziel(e) | Der Benutzer möchte sich anmelden, um seine Kontofunktionen nutzen zu können. |
| Auslösendes Ereignis (Trigger) | Der Benutzer möchte sich anmelden und wählt die Funktion Anmelden |
| Beschreibung | Ein registrierter Benutzer authentifiziert sich mit seinen Zugangsdaten an der VintageCar-Plattform. |
| Beziehung zu anderen Use Cases | - |

### 2. Vorbedingungen

- Für den Benutzer ist Registriert und hat ein Benutzerkonto.
- Das System ist Verfügbar

### 3. Nachbedingungen

- Das Benutzer ist erfolgreich angemeldet.
- Der Benutzer hat Zugriff auf die Funktionen, die seiner Rolle zugeordnet sind.

### 4. Hauptszenario

1. Der Benutzer startet die Anmeldung, indem er auf den Button "Anmelden" klickt
2. Das System zeigt das Anmeldeformular an
3. Der Benutzer trägt seine Anmeldedaten ein.
4. Der Benutzer bestätigt die Anmeldung.
5. Das System überprüft die Anmeldedaten
6. Das System authentifiziert den Benutzer und meldet ihn an.
7. Das System bestätigt die erfolgreiche Anmeldung zurück

### 5. Alternativszenarien
3a. Der Benutzer nutzt gespeicherte Anmeldedaten.
- 3a1. Der Benutzer wählt seine gespeicherten Daten aus.
- 3a2. Das System füllt das Anmeldeformular automatisch aus.
- 3a3. Weiter mit Schritt 4 .


### 6. Ausnahmeszenarien
5a. Die eingegebenen Anmeldedaten sind falsch oder unvollständig.
- 5a1. Das System lehnt die Anmeldung ab und zeigt eine Fehlermeldung an.
- 5a2. Der Benutzer korrigiert seine Anmeldedaten.
- 5a3. Weiter mit Schritt 4.

### 7. Spezielle Anforderungen

- Zugang nach mehreren fehlgeschlagenen Anmeldeversuchen vorübergehend sperren
- Passwörter nicht im Klartext anzeigen und speichern
- Allgemeine Fehlermeldung anzeigen, ohne zu nennen, ob E-Mail-Adresse oder Passwort falsch ist

