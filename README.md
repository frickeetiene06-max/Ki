# Etiene's KI — komplette lokale Projektversion

## Start
1. Node.js 20+ installieren.
2. `npm install`
3. `.env.example` nach `.env` kopieren.
4. `OPENAI_API_KEY=...` eintragen.
5. `npm start`
6. `http://localhost:3000` öffnen.

## Enthalten
- Chat-basierter Bot-Builder
- Sprachenauswahl
- Projektdateien werden persistent unter `data/projects` gespeichert
- KI kann vorhandene Dateien weiterentwickeln
- Discord Bot Token für die laufende Sitzung
- `npm install` für generierte JavaScript/TypeScript-Projekte
- `pip install -r requirements.txt` für Python-Projekte
- Bot starten/stoppen
- Projekt als ZIP exportieren
- keine klassische Code-Editor-Oberfläche

## Wichtig
Das ist eine funktionsfähige, selbst hostbare End-to-End-App, aber kein gehärteter Multi-Tenant-SaaS-Dienst.
Die generierte Bot-Anwendung wird auf demselben Rechner/Server ausgeführt und hat dessen normale Prozessrechte.
Für öffentliches Hosting sollten Bot-Prozesse in isolierten Containern laufen, Tokens verschlüsselt gespeichert werden,
Authentifizierung/Rate-Limits vorhanden sein und Ressourcenlimits gesetzt werden.
