# ServeIQ Phase 2 – Update 26.10.2026

Technische Testversion basierend auf der vorherigen Phase-2-Version.

## Änderungen
- Home/Teams: genehmigter Info-Text zu Ass, normalem Service, Servicefehler, Counter, Statistiken.
- Teams: laufende Spiele und Spielerstellen-Button bleiben entfernt.
- Neues Spiel: Button «+ Spiel erstellen» immer oben, darunter bei Bedarf «Laufende Spiele» (Öffnen, Löschen) und «Entwürfe» (Entwurf fortsetzen).
- Aufstellung: die Beschriftung «Auslaufzone» entfernt, blaue Zone bleibt.
- Auswählbare Spielerinnen-Kacheln kompakter auf Smartphone, mit Nummer, Vorname und Rolle.
- Libera im Auswahlraster rosa, separat auf Libera-Ablageplatz ziehbar/tippbar; sechs reguläre Rotationsslots unverändert. Auch in der nächsten Satzaufstellung.
- Splash-Screen bei jedem frischen Öffnen der Webseite, ohne die gespeicherten Teams, Spiele und Entwürfe zu löschen.
- Lokales Splash-Screen-Bild als eigene PNG-Datei beigelegt.

## GitHub Pages
Alle Dateien im ZIP in das Stammverzeichnis des Repositories `ServeIQ-Phase2-Test` hochladen, vorhandene Dateien überschreiben. `index.html` muss im Stammverzeichnis bleiben. Nach Update Seite neu laden (Strg+F5).

## Testhinweise
Vor Produktion alle Aktionen auf Smartphone und Browser prüfen: Entwurf fortsetzen, Libera setzen und entfernen, Aufstellungswechsel, Servicepunkte, Rotation und Archiv. JavaScript-Syntaxprüfung ist kein vollständiger Browser-Test.

## Neue Änderung – Karten «Neues Spiel»
- «Laufende Spiele»: Mannschaften und Datum, ohne Satz, Punkte, Satzstand und redundante Statusbeschriftung.
- «Entwürfe»: Mannschaften und Datum, ohne redundante Labels oder Hinweistext.
- Beide Bereiche: identisch grosse Buttons in zwei Spalten; Entwürfe mit «Entwurf fortsetzen» und «Löschen» inklusive Sicherheitsbestätigung.
- Splash-Screen-Bild und übrige Funktionen sind unverändert aus der vorigen Testversion übernommen.
