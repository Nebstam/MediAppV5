# Medikamenten-App – Version 5 (Kapsel)

Offline-fähige PWA. Neu: frei wählbare Anzahl **1 bis 24 Einnahmen pro geplantem Tag** als Zahleneingabe; jede Einnahme hat eine eigene Uhrzeit und lässt sich unabhängig abhaken oder überspringen. Alle bisherigen Funktionen bleiben erhalten (Nach Bedarf, Intervalle, Verlauf, Backup).

## Installation auf iPhone
Entpackten **Inhalt** von `medikamenten-app/` ins Stammverzeichnis des bestehenden GitHub-Pages-Repositories hochladen; `index.html` muss im Stamm liegen. Danach GitHub-Pages-URL in Safari mit Internet öffnen, aktualisieren und Offline-Modus testen. Vor dem Update Backup aus der App exportieren.

## Hinweise
Die App gibt keine Dosierungsempfehlung. Maximale Einnahmehäufigkeit in der Oberfläche: 24 pro geplantem Tag. Bestehende lokale Daten bleiben unter demselben Speicherschlüssel. Automatische Web-Push-Erinnerungen sind nicht implementiert. Die native Capacitor-Erinnerung ist nur für täglich geplante Medikamente vorbereitet und muss vor App-Store-Einreichung auf iOS getestet werden.
