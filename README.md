# DNS-Bind9---wilders.lan

 DNS Bind9 - wilders.lan

## Configuration
- Serveur : Debian 13 Trixie
- IP serveur DNS : 172.16.10.4
- Zone : wilders.lan

## Enregistrements
| Nom | Type | Valeur |
|-----|------|--------|
| jarvis | A | 172.16.10.3 |
| www | A | 172.16.10.3 |
| web | CNAME | www.wilders.lan |

## Tests
Validés depuis Windows Server (172.16.10.3) avec nslookup


<img width="770" height="219" alt="fichier db wilders lan" src="https://github.com/user-attachments/assets/b4c8deac-c039-498f-a778-48415eea4dcb" />
