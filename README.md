ServeIQ Phase 2 – Blau-Design mit Audiofeedback

Installieren: Alle Dateien direkt ins Hauptverzeichnis des GitHub-Pages-Testrepositories hochladen.

Audio: service-ascending.wav = kurzer tiefer zu mittlerem Zweiton bei Normaler Service (keine Punktvergabe). point-double.wav = bereits freigegebener Doppelton bei genau einem abgeschlossenen Ballwechsel (Ass, Fehler, Punkt Heim/Gast). Der Ton wird nach einer erfolgreichen Spielsituation abgespielt; Punkt zurück/vor und offener Service abbrechen bleiben ohne Ton.

Unter Einstellungen: Ein/Aus, Lautstärke und Hörprobe. Audio-Einstellungen werden browserlokal unabhängig von der Spielstandspeicherung gespeichert.

Splash-Screen und Logos sind byte-identisch zur Blue-Theme-Basis. Spielereignislogik unverändert. Vor produktivem Einsatz die App auf dem Zielgerät und im Browser testen.


## Update November 2026 – Teams, Sätze, Navigation
- Teams: Entfernter redundanter Kader-Speichern-Button; Einzeländerungen werden sofort persistent gespeichert, kurzer Hinweis «✓ Gespeichert» (2 Sekunden).
- Live-Game: Entfernte Buttons «Spiel abbrechen» und «Seite korrigieren» inklusive ihrer UI-Handler. Die Auswertung alter Spielereignisse (SIDE) bleibt für die Kompatibilität erhalten.
- Satzvorbereitung 2–4: Automatische Service- und Seitenzuordnung wie bisher; redundanten Hinweis entfernt.
- Satz 5: Erster Service und Seite müssen vor Satzbeginn gewählt werden. Automatischer einmaliger Seitenwechsel nach 8 Punkten; Satzgewinn ab 15 Punkten, mindestens zwei Punkte Differenz.
- «Punkt vor» nur bei verfügbarer Rücknahme aktiv; nach neuer Aktion wird die Vorwärts-Historie verworfen.
- SPLASH und Tondateien unverändert.
