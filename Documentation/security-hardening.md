# Security Hardening

Security was implemented to protect the infrastructure from unauthorized access.

---

## Firewall (UFW)

Firewall rules applied to restrict network access.

Example rules:

SSH access allowed

HTTP access allowed

Database access restricted to web server

---

## Fail2Ban

Fail2Ban protects against brute force attacks.

Features:

- SSH attack detection
- Automatic IP banning
- Log monitoring

---

## SSH Hardening

Security improvements applied to SSH configuration.

Changes made:

PermitRootLogin disabled

MaxAuthTries set to 3

This prevents unauthorized login attempts.

---

## Network Isolation

Servers are placed inside an internal network:

192.168.10.0/24

Only necessary ports are open.

---

## Security Outcome

- Reduced attack surface
- Protected SSH access
- Controlled service communication
