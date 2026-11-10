# BMS Enterprise Network

Standortübergreifendes Unternehmensnetzwerk für die BMS Infrastruktur GmbH, umgesetzt in Cisco Packet Tracer.

Das Netzwerk verbindet den Hauptstandort Berlin mit der Niederlassung München. Die Infrastruktur wird in 18 aufeinander aufbauenden Projektphasen geplant, implementiert, geprüft und dokumentiert.

## Projektziel

Aufbau einer einheitlichen, skalierbaren und abgesicherten Netzwerkinfrastruktur mit folgenden Schwerpunkten:

- IPv4- und IPv6-Adressierung
- VLANs und Inter-VLAN-Routing
- Spanning Tree und EtherChannel
- Statisches Routing und OSPF
- DHCP, DNS, NTP und Syslog
- NAT und PAT
- Access Control Lists
- SSH und Layer-2-Security
- Wireless LAN
- Monitoring und Troubleshooting
- Netzwerkautomatisierung und APIs

## Standorte

| Standort | Funktion | Adressbereich |
|---|---|---|
| Berlin | Hauptstandort und zentrale Dienste | `10.10.0.0/16` |
| München | Niederlassung | `10.20.0.0/16` |
| WAN | Standortverbindungen | `10.255.0.0/24` |

## Projektstand

| Phase | Thema | Status |
|---:|---|---|
| 01 | [Netzwerkgrundlagen](labs/01-netzwerkgrundlagen.md) | Abgeschlossen |
| 02 | Ethernet, MAC-Adressen, ARP und Switching | Offen |
| 03 | IPv4-Adressierung und Subnetting | Offen |
| 04 | IPv6-Adressierung und Neighbor Discovery | Offen |
| 05 | Cisco IOS und Geräte-Grundkonfiguration | Offen |
| 06 | VLANs und Trunking | Offen |
| 07 | Inter-VLAN-Routing | Offen |
| 08 | Spanning Tree und EtherChannel | Offen |
| 09 | Statisches Routing und Default Routes | Offen |
| 10 | OSPFv2 und OSPFv3 | Offen |
| 11 | DHCP, DNS, NTP und IP-Services | Offen |
| 12 | NAT und PAT | Offen |
| 13 | Access Control Lists | Offen |
| 14 | Netzwerksicherheit und Layer-2-Security | Offen |
| 15 | WLAN und Wireless-Security | Offen |
| 16 | Netzwerkmanagement und Troubleshooting | Offen |
| 17 | Automatisierung, APIs, JSON und SDN | Offen |
| 18 | Gesamtabnahme | Offen |

## Struktur

```text
.
├── README.md
├── images/
├── labs/
│   └── 01-netzwerkgrundlagen.md
└── packet-tracer/
    └── bms-enterprise-network.pkt
```

## Dokumentation

Jede Projektphase wird in einer eigenen Markdown-Datei unter `labs/` dokumentiert. Technische Nachweise liegen unter `images/`. Die aktuelle Packet-Tracer-Datei befindet sich unter `packet-tracer/`.

Konfigurationen und Ergebnisse werden erst nach erfolgreicher Verifikation dokumentiert.

