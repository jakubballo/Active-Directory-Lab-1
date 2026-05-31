# Windows Server 2022 Installation

## Ziel

Installation eines Windows Server 2022 als Domain Controller für eine Testumgebung.

## Verwendete Software

- VirtualBox
- Windows Server 2022 Evaluation
- Windows 11 25H2

## VM-Konfiguration

| Einstellung | Wert |
|------------|------|
| Name | DC01 |
| RAM | 8 GB |
| CPU | 2 Kerne |
| Festplatte | 80 GB |
| Netzwerk | NAT + Host-Only |

## Serverkonfiguration

### Computername

DC01

### Netzwerk

| Einstellung | Wert |
|------------|------|
| IP-Adresse | 192.168.100.10 |
| Subnetzmaske | 255.255.255.0 |
| DNS | 192.168.100.10 |

## Ergebnis

Der Windows Server wurde erfolgreich installiert und für die weitere Active-Directory-Konfiguration vorbereitet.