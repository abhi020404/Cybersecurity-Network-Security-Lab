# 🔐 Cybersecurity Network Security Lab

## Overview

This repository documents practical cybersecurity laboratory exercises performed in an authorized virtual lab environment using Kali Linux and Metasploitable 2.

The project demonstrates:

- Network reconnaissance using Nmap
- Vulnerability assessment using OpenVAS
- Packet analysis using Wireshark
- Basic firewall configuration using iptables

---

# Lab Environment

| Component | Description |
|-----------|-------------|
| Attacker Machine | Kali Linux 2024 |
| Target Machine | Metasploitable 2 |
| Virtualization | Oracle VirtualBox |
| Network | Host-Only |

---

# Tools Used

- Nmap
- Wireshark
- OpenVAS
- iptables
- Linux Terminal

---

# Modules

## 1. Network Scanning

Performed:

- TCP SYN Scan
- UDP Scan
- Service Version Detection
- Operating System Detection

Commands:

```bash
sudo nmap -sS <TARGET-IP>
sudo nmap -sU <TARGET-IP>
sudo nmap -sV <TARGET-IP>
sudo nmap -O <TARGET-IP>
```

---

## 2. Vulnerability Assessment

Performed using:

- OpenVAS

Severity Categories

- Critical
- High
- Medium
- Low

---

## 3. Packet Analysis

Captured:

- ICMP
- HTTP
- FTP
- DNS
- TCP

Wireshark Filters

```text
http
ftp
dns
icmp
tcp
```

---

## 4. Firewall

Created firewall rules using iptables.

Example

```bash
sudo iptables -A INPUT -p tcp --dport 80 -j DROP
```

---

# Learning Outcomes

- Network Enumeration
- Service Detection
- Vulnerability Analysis
- Packet Inspection
- Firewall Configuration

---

# Disclaimer

This project was completed in an authorized educational laboratory using intentionally vulnerable virtual machines. All testing was performed in an isolated environment.
