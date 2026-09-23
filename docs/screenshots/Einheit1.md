# Einheit 1 – Installation, Konfiguration, Architekturüberblick

## Installation

Node.js, npm und Ionic CLI wurden installiert und getestet.

## Datenbank

Die Datenbank `ITL1_uebungen` wurde in MySQL erstellt.

## Fragen

### 1. Was ist der Unterschied zwischen Capacitor und Cordova?

Capacitor ist die modernere Alternative zu Cordova und wird von Ionic unterstützt. Beide ermöglichen den Zugriff einer Web-App auf native Gerätefunktionen.

- Beide verbinden Web-Apps mit nativen Funktionen.
- Capacitor ist der modernere Ansatz.
- Cordova ist älter.

### 2. Was macht ein ORM wie Sequelize, und wofür braucht man zusätzlich die sequelize-cli?

Sequelize verbindet JavaScript mit einer Datenbank und erleichtert den Zugriff auf Daten.
sequelize-cli wird für Befehle wie Migrationen und das Erstellen von Modellen verwendet.

- Sequelize ist ein ORM.
- Es hilft, SQL nicht komplett selbst schreiben zu müssen.

### 3. Was unterscheidet `npm install` von `npx` beim Ausführen eines Pakets?

npm install installiert ein Paket.
npx führt ein Paket bzw. einen Befehl aus, ohne es global installieren zu müssen.


### 4. Was ist REST, und warum passt das Konzept zu einer Client-Server-Architektur wie Ionic-App und Node-Backend?

REST ist ein Konzept für die Kommunikation zwischen Client und Server über HTTP. Die Ionic-App sendet z. B. GET, POST, PUT oder DELETE an das Node-Backend.
