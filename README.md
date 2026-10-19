# WireGuard & Pi-hole Setup

## 1. Was macht das Setup?
Ich nutze Pi-hole, um Werbung und Tracker in meinem gesamten Heimnetzwerk zentral zu blockieren. Über WireGuard baue ich einen sicheren VPN-Tunnel von meinem Smartphone in mein lokales Netzwerk auf. So surfe ich auch von unterwegs komplett werbefrei und kann sicher auf meine lokalen Dienste zugreifen.

## 2. Wie startet man es?
Ich passe zuerst die Passwörter und IP-Adressen in der `docker-compose.yml` an meine Umgebung an. Danach starte ich beide Container direkt über das Terminal:

```bash
docker-compose up -d
```
