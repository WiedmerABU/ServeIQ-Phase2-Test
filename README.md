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


## Phase 2 – Teams und gemeinsames Spielfeld (26.10.2026)
- Teams: Bereich «Laufende Spiele» und Button «Spiel erstellen» entfernt. Laufende Spiele und Entwürfe sind weiterhin in «Neues Spiel».
- Startaufstellung Satz 1 und Sätze 2–5: gleiche Spielfeldgrafik wie die read-only Ansicht «Aktuelle Aufstellung» im Live-Game.
- Gemeinsame Renderer-Funktion `lineupCourtShell`; interaktive Positions-Buttons und gespeicherte Rotations-/Statistiklogik unverändert.
- GitHub Pages: vier Dateien direkt ins Repository-Hauptverzeichnis hochladen.
- Vor Einsatz den Ablauf Teams → Neues Spiel → Matchkader → Aufstellung → Live-Game → Aktuelle Aufstellung sowie Satzwechsel prüfen.
