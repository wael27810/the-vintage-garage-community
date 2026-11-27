# 6. Ergänzende Spezifikationen 

### UC.F.1 Ungültige oder falsche Eingabe
Allgemein wird bei einer ungültigen oder falschen Eingabe wie folgt vorgegangen:

1. Das System erkennt bei der Prüfung der Eingabe, dass diese ungültig oder unvollständig ist.

2. Das System lehnt die Eingabe ab und verarbeitet sie nicht weiter.

3. Das System zeigt eine Fehlermeldung an, die den Fehler benennt (und betroffene Felder markiert).

4. Der Benutzer korrigiert seine Eingabe und bestätigt sie erneut.

5. Das System prüft die Eingabe erneut.

6. Ist die Eingabe nun gültig, setzt das System den Use-Case an der Stelle fort, an der die Prüfung stattgefunden hat. Ist sie ungültig geht es bei Schritt 2 weiter.
