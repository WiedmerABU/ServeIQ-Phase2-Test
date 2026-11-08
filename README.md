# ServeIQ Phase 2 – Elevated Flat Design (Testversion)

Basis: ServeIQ Phase 2 Live-Game V7 Integration. Die App verwendet unverändert deren Spiellogik und Datenspeicherung.

## Design
Alle Hauptscreens Teams, Neues Spiel/Matchkader/Startaufstellung, Live-Game inkl. fokussierter Punkteentscheidung und Archiv/Statistik haben eine konsistente **Elevated Flat** Gestaltung: klare Farbflächen, schlichte Kanten, dezente Schatten, leicht plastische Buttons, konsistente Karten. Formulare, Dialoge, Kader, Spielfeld und Navigation sind einbezogen.

## Unverändert
Originaldateien `splash-screen.png`, `club-logo.png`, `serveiq-logo.png` wurden unverändert übernommen. Keine Änderung an Event-Engine, Satzregeln, Rotation, Service-Statistik, Speicherroutine oder Screen-Aktionen.

## Prüfung
Bitte auf Smartphone Teams, Neues Spiel, Aufstellung, Live-Game und Archiv durchtesten. In derselben Browserinstanz bleiben lokale Spielstände erhalten. Testrepository benutzen, bevor die produktive Version ersetzt wird.


## Live-Game – einziehbare Navigation (Update)

Nur auf Live-Game, Aktuelle Aufstellung und Statistik, die vom Live-Game aus geöffnet wurde:
- Standardmässig eingeklappt; 27px Griff bleibt sichtbar.
- Tippen auf Griff öffnet/schliesst die Leiste, Hochziehen am Griff öffnet sie.
- Scrollen nach unten blendet sie ein; Scrollen nach oben blendet sie aus.
- Nach sieben Sekunden ohne Bedienung wird die Leiste wieder eingeklappt (solange kein Dialog offen ist).
- Auf Teams, Neues Spiel und der normalen Archivansicht bleibt die Navigation unverändert sichtbar.
- Der Vollbildschirm zur Punkteentscheidung bleibt ohne Navigation.

Keine Anpassung der Volleyball- oder Statistiklogik, der Speicherdaten oder Splash-Grafik.
