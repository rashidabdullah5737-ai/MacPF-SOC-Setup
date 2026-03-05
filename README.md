# MacPF-SOC-Setup
Advanced PF firewall configuration for macOS, designed for security-conscious users. Features include:

- 🌐 Threat intelligence blocklists (~50k+ malicious IPs)
- 🔐 SSH brute-force protection with SSHGuard
- 🌍 Optional GeoIP filtering
- 📜 Logging of blocked connections and attacks
- 🔎 Real-time attack monitoring via pflog0

## Installation

1. Copy the PF configuration file:
```bash
sudo cp pf.conf /etc/pf.conf
