# Bösartige IP Sperrliste (Umgewandelt von Jörg Berns)

[Click here for the English version](README.md)

Dieses Repository bietet eine spezialisierte IP-Blockliste, basierend auf den Sicherheitsdaten von **Marius Bogdan Lixandru**.

## 🔄 Tägliche Aktualisierungen
Sicherheit ist ein dynamischer Prozess. Daher wird diese Liste von mir **jeden Tag händisch aktualisiert**, um sicherzustellen, dass die neuesten von Marius Hosting identifizierten bösartigen IPs zeitnah in dein System übernommen werden.

*Hinweis: Bitte stelle in deinem AdGuard oder Pi-hole das Update-Intervall ebenfalls auf "Täglich", um von den frischen Daten zu profitieren.*

## 🛡️ Quelle & Anerkennung
Die primäre Quelle dieser Daten ist: 
👉 **[https://mariushosting.com](https://mariushosting.com)**

Marius Bogdan Lixandru leistet hervorragende Arbeit bei der Identifizierung schädlicher IPs für Synology-Systeme. Da seine Listen im Original für die Synology-Firewall formatiert sind, habe ich, **Jörg Berns**, diese Version erstellt, um sie universell nutzbar zu machen.

## 🚀 Warum diese konvertierte Liste?
Während 60.000 IP-Regeln eine Standard-NAS-Firewall (wie die von UGREEN oder Synology) auf Systemebene überlasten könnten, ist diese Liste als **DNS- oder IP-Blockliste** für spezialisierte Werbe- und Trackingfilter optimiert.

**Empfohlene Nutzung als Ergänzung in:**
* **AdGuard Home** (DNS-Sperrliste)
* **Pi-hole** (Adlist / Blacklist)
* **Technitium DNS Server** (Block List)

## 🔗 Einbindung
Kopiere diesen Raw-Link in dein AdGuard, Pi-hole oder Technitium:
`https://raw.githubusercontent.com/SmokingBull/malicious-ip-blocklist/main/deny-ip-list.txt`

---
**Hinweis:** Ein großes Dankeschön an Marius für die Bereitstellung der Daten auf [mariushosting.com](https://mariushosting.com). Supportet seine Arbeit!
