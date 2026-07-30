# Service Version Detection

## Command

```bash
sudo nmap -sV <TARGET-IP>
```

## Findings

| Port | Service | Version |
|------|----------|----------|
|21|FTP|vsftpd 2.3.4|
|22|SSH|OpenSSH|
|80|Apache|2.2.8|
|3306|MySQL|5.0|

## Analysis

Several services were outdated and known to contain vulnerabilities. Service version detection is valuable for prioritizing software updates and remediation.
