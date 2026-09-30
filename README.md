# 🔎 Information Gathering (Reconnaissance)

![Status](https://img.shields.io/badge/status-completed-blue)
![Phase](https://img.shields.io/badge/phase-1%20of%20Ethical%20Hacking-red)
![Focus](https://img.shields.io/badge/focus-OSINT%20%7C%20Recon-orange)

## 📌 Definition

**Information Gathering** (a.k.a. Reconnaissance) is the **first phase of Ethical Hacking**, where an attacker collects details about a target *without attacking it directly*.

**Goal:** Understand the target's system, network, users, and security posture.

> ⚠️ **Ethical Rule:** Only test systems you own or have **written permission** to test. Unauthorized reconnaissance is illegal.

---

## 🎯 Why Information Gathering Matters

- Identifies weak points before exploitation
- Reduces attack time and noise
- Helps plan a targeted attack strategy
- Avoids unnecessary detection
- Essential for penetration testing & cyber investigations

---

## 🧭 Types of Information Gathering

### 🟢 Passive Information Gathering
**No direct contact with the target** · Low risk · Hard to detect

**Examples:**
- Google search / Google Dorks
- Social media analysis
- WHOIS lookup
- DNS records
- Job portals

**🛠 Tools:** Google Dorks · WHOIS · Maltego · Shodan · Recon-ng

---

### 🔴 Active Information Gathering
**Direct interaction with the target** · More accurate · Higher risk

**Examples:**
- Ping scan
- Port scanning
- Network mapping
- Banner grabbing

**🛠 Tools:** Nmap · Netcat · Angry IP Scanner · Wireshark

---

## 📊 Information Collected

| Category | Details |
|----------|---------|
| **Domain Info** | Domain name, registrar |
| **IP Address** | Public & private IPs |
| **Network** | Open ports, running services |
| **OS Details** | Linux, Windows, version |
| **Email Info** | Employee emails |
| **Technologies** | Web server, CMS |
| **Security** | Firewalls, IDS |

---

## 🛠 Techniques Used

### 1. Google Dorking
Advanced search queries to find sensitive data.

```
site:example.com filetype:pdf
```

### 2. WHOIS Enumeration
Finds domain ownership details.
**Information found:** owner name, email, phone, DNS servers.

### 3. DNS Enumeration
Reveals DNS records.
**Records:** `A` · `MX` · `NS` · `TXT`

### 4. Network Scanning
Identifies live hosts and services.

```bash
nmap -sS -sV <target_ip>
```

---

## 🧰 Tools Summary

| Tool | Purpose |
|------|---------|
| **Nmap** | Network scanning |
| **Maltego** | Relationship mapping |
| **Shodan** | Internet-connected devices |
| **Recon-ng** | Web reconnaissance |
| **Wireshark** | Packet analysis |
| **WHOIS** | Domain ownership lookup |

---

## 🕵️ Information Gathering in Cyber Crime Investigation

- Tracks IP location
- Identifies attack sources
- Correlates logs & traffic
- Supports digital forensics

---

## ⚖️ Legal & Ethical Considerations

- ✅ **Permission required**
- ❌ **Illegal without authorization**

> *"Only test systems you own or have written permission to test."*

---

## 🧪 Example Scenario

A company hires a penetration tester. Steps:

1. Google search the company (passive)
2. Find employee emails (passive)
3. Scan the network with Nmap (active)
4. Identify open ports (active)
5. Plan the attack strategy

---

## 📝 Exam-Oriented Short Notes

- Information Gathering = **Reconnaissance**
- **First phase** of ethical hacking
- **Passive** = no interaction
- **Active** = direct interaction
- **Google Dorks** = powerful OSINT
- **Nmap** = key scanning tool

---

## 📌 One-Line Definition

> Information Gathering is the process of collecting system, network, and user-related data about a target to identify potential security vulnerabilities.

---

## 📄 Project Files

- `Information Gathering Report .pdf` — full written report
- `Information Gathering Challenge.pdf` — challenge documentation

## 📚 References

- [OWASP: Information Gathering](https://owasp.org/www-community/OWASP_Testing_Guide)
- [Nmap Documentation](https://nmap.org/book/man.html)
- [Google Hacking Database (GHDB)](https://www.exploit-db.com/google-hacking-database)

## 👤 Author

**S. Sudharna** — Cybersecurity | Ethical Hacking  
GitHub: [@sudharnas](https://github.com/sudharnas)
