# 🔎 Subdomain Enumeration Tool (Python)

This is a simple, multithreaded Python script designed to discover valid subdomains for a target domain using a wordlist. It attempts HTTP connections to each subdomain and logs those that respond.

---

## ✅ Features

- Fast multithreaded enumeration
- Uses `requests` for live HTTP probing
- Automatically saves discovered subdomains to a file
- Uses `threading.Lock()` for thread-safe list updates

---

## 🛠 Requirements

- Python 3.6+
- `requests` module

Install dependencies:
```bash
pip install requests
