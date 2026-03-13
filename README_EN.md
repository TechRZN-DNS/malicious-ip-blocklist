# Malicious IP Blocklist (Converted by Jörg Berns)

[Klicke hier für die deutsche Version](README_DE.md)

This repository provides a specialized IP blocklist based on the security data provided by **Marius Bogdan Lixandru**.

## 🔄 Daily Updates
Security is a dynamic process. Therefore, I **manually update this list every day** to ensure that the latest malicious IPs identified by Marius Hosting are quickly integrated into your system.

*Note: Please remember to set the update interval in your AdGuard or Pi-hole settings to "Daily" to benefit from these fresh updates.*

## 🛡️ Source & Credits
The primary source of this data is:
👉 **[https://mariushosting.com](https://mariushosting.com)**

Marius Bogdan Lixandru does outstanding work in identifying malicious IPs for Synology systems. Since his original lists are formatted specifically for the Synology Firewall, I, **Jörg Berns**, have created this converted version to make it universally compatible.

## 🚀 Why use this converted list?
While 60,000 individual IP rules might overwhelm a standard NAS firewall (like UGREEN or Synology) on a system level, this list is optimized for use as a **DNS or IP blocklist** within specialized ad and tracking filters.

**Recommended for use as an additional layer in:**
* **AdGuard Home** (DNS Blocklist)
* **Pi-hole** (Adlist / Blacklist)
* **Technitium DNS Server** (Block List)

## 🔗 How to use
Copy this Raw link into your AdGuard, Pi-hole, or Technitium settings:
`https://raw.githubusercontent.com/SmokingBull/malicious-ip-blocklist/main/deny-ip-list.txt`

---
**Note:** A big thank you to Marius for providing the data at [mariushosting.com](https://mariushosting.com). Please support his work!
