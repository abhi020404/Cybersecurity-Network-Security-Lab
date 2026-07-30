# TCP SYN Scan

## Objective

Discover open TCP ports on the target system.

## Command

```bash
sudo nmap -sS <TARGET-IP>
```

## Result

Open Ports

- FTP
- SSH
- Telnet
- HTTP
- MySQL
- PostgreSQL
- VNC

## Analysis

The SYN scan identified multiple listening services, indicating that the target exposes numerous network services. Such information helps administrators understand the system's attack surface.
