# 🌐 DNS Lookup & Traceroute Tool — Python Network Utility

A Python-based **network diagnostic tool** that performs **DNS resolution**, **traceroutes**, and **latency (ping) checks** using Python’s built-in `socket` module and the powerful `scapy` library. Useful for networking students, sysadmins, and developers.

---

## 📝 Description

This tool enables users to:

- Resolve domain names to IP addresses
- Trace the route packets take to a destination
- Measure latency at each hop
- Diagnose network delays or failures

Designed as a **command-line utility**, it’s cross-platform and doesn’t require a web interface or internet APIs.

---

## ✨ Features

- 🧭 **DNS Lookup** — resolve hostnames to IP addresses
- 🛰️ **Traceroute** — identify the network path to a domain/IP
- 📡 **Ping/Latency Check** — measure round-trip time
- 🧪 **Built-in error handling** for invalid hosts or unreachable networks
- 🖥️ CLI-based, lightweight, and portable

---

## 💻 Technologies Used

- **Python 3.x**
- `socket` — for DNS resolution and low-level networking
- `scapy` — for traceroute and packet manipulation
- `os` / `subprocess` — for platform-specific pings (if used)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/dns-traceroute-tool.git
cd dns-traceroute-tool
