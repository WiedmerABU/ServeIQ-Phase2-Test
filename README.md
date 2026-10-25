# ServeIQ Phase 2 – Update Matchkader und Live-Game

Testversion auf Basis der vorhandenen Phase-2-Designversion. Alle Dateien direkt im Root eines separaten GitHub-Pages-Repositories hochladen.

## Anpassungen
- Matchkader-Kacheln mit Nummer, Vorname und ausgeschriebener Position
- Dunkelblauer Counter und sanft pulsierender hellblauer Servicerahmen
- Grün: Ass, Normaler Service, Punkt VBC Interlaken; rot: Servicefehler, Punkt Gegner
- Vier neutrale Funktionsbuttons bleiben vorhanden
- Neuer Button **Aktuelle Aufstellung**, dessen Anzeige die aktive Rotations- und Wechselhistorie aus dem laufenden Spiel übernimmt und mit «Zurück» ohne Änderung zum Spiel führt

## Testen
Punkte, Seitenwechsel, Auswechslungen, Undo/Redo, Satzwechsel, Datenpersistenz und Aufstellungsanzeige in einer separaten Kopie prüfen. Die bisherige GitHub-Version nicht überschreiben.

## Update: vier Verbesserungen
- Splash-Screen bei jedem Laden/Öffnen der Web-App, nicht beim Tabwechsel; Teams und Spiele bleiben gespeichert.
- Matchkader-Spielerinnenkacheln kompakter (3 Spalten am Smartphone; 4 auf breiteren Geräten).
- Gegner-Punktebuttons, egal in welchem Ballwechsel-Modus, hellrot wie der Servicefehler; eigene Punkte hellgrün.
- Bei neuem Satz-/Matchgewinn durch VBC Interlaken 3 Sekunden überlagerndes Konfetti von oben nach unten über dem *gesamten* Bildschirm; keine Konfetti-Wiederholung bei erneutem Öffnen einer Ergebnisansicht.


## Konfetti im Stil des Referenzvideos
- 135 schmale, teilweise gebogene Papierstreifen in Blau und Türkis; keine Icons oder Emojis.
- Fällt ungefähr 3 Sekunden von oben nach unten transparent über die gesamte App.
- Animation erscheint nur bei Satzgewinn von VBC Interlaken; die bestehende Spiel-/Statistiklogik bleibt unverändert.
