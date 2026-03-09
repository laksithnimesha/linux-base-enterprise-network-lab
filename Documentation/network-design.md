
# Network Design

## Network Range

Internal Network:

192.168.10.0/24

Subnet Mask:

255.255.255.0

---

## Server IP Address Allocation

| Device | Role | IP |
|------|------|------|
| Firewall | Gateway | 192.168.10.1 |
| DNS Server | Name Resolution | 192.168.10.10 |
| Web Server | Website Hosting | 192.168.10.20 |
| Database Server | Application Database | 192.168.10.30 |
| File Server | Network File Storage | 192.168.10.40 |
| Client | Testing Machine | 192.168.10.100 |

---

## Network Traffic Flow

Client → DNS Server → Web Server → Database Server

Client → File Server (SMB)

---

## DNS Domain

Internal domain used:

technova.local

Example DNS records:

web.technova.local → 192.168.10.20

db.technova.local → 192.168.10.30
