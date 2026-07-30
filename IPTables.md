# Firewall Configuration

## Allow SSH

```bash
sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT
```

## Block HTTP

```bash
sudo iptables -A INPUT -p tcp --dport 80 -j DROP
```

## Display Rules

```bash
sudo iptables -L
```

## Analysis

The firewall rules demonstrate basic traffic filtering by permitting administrative access while restricting selected services.
