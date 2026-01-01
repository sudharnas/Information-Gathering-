Information Gathering (Reconnaissance)
1️⃣ Definition
Information Gathering is the first phase of Ethical Hacking where a hacker collects details about a target without attacking it directly.
🎯 Goal:
To understand the target’s system, network, users, and security posture.
2️⃣ Why Information Gathering is Important
Identifies weak points
Reduces attack time
Helps in planning attacks
Avoids unnecessary detection
Used in penetration testing & cyber investigations
3️⃣ Types of Information Gathering
🔹 1. Passive Information Gathering
✔ No direct contact with the target
✔ Low risk, hard to detect
Examples:
Google search
Social media analysis
WHOIS lookup
DNS records
Job portals
🛠 Tools:
Google Dorks
WHOIS
Maltego
Shodan
Recon-ng
🔹 2. Active Information Gathering
✔ Direct interaction with target
✔ More accurate but risky
Examples:
Ping scan
Port scanning
Network mapping
Banner grabbing
🛠 Tools:
Nmap
Netcat
Angry IP Scanner
Wireshark
4️⃣ Information Collected
Category
Details
Domain Info
Domain name, registrar
IP Address
Public & private IPs
Network
Open ports, services
OS Details
Linux, Windows, version
Email Info
Employee emails
Technologies
Web server, CMS
Security
Firewalls, IDS
5️⃣ Techniques Used
🔸 Google Dorking
Advanced search queries to find sensitive data.
Example:
Copy code

site:example.com filetype:pdf
🔸 WHOIS Enumeration
Finds domain ownership details.
Information Found:
Owner name
Email
Phone
DNS servers
🔸 DNS Enumeration
Reveals DNS records.
Records:
A
MX
NS
TXT
🔸 Network Scanning
Identifies live hosts and services.
Example Nmap Command:
Copy code

nmap -sS -sV target_ip
6️⃣ Tools Summary
Tool
Purpose
Nmap
Network scanning
Maltego
Relationship mapping
Shodan
Internet-connected devices
Recon-ng
Web reconnaissance
Wireshark
Packet analysis
7️⃣ Information Gathering in Cyber Crime Investigation
Tracks IP location
Identifies attack sources
Correlates logs & traffic
Supports digital forensics
8️⃣ Legal & Ethical Considerations ⚠️
✔ Permission required
❌ Illegal without authorization
Ethical Rule:
“Only test systems you own or have written permission to test.”
9️⃣ Example Scenario
A company hires a penetration tester.
Steps:
Google search company
Find employee emails
Scan network with Nmap
Identify open ports
Plan attack strategy
🔟 Exam-Oriented Short Notes
Information Gathering = Reconnaissance
First phase of ethical hacking
Passive = No interaction
Active = Direct interaction
Google Dorks = Powerful OSINT
Nmap = Key scanning tool
📌 One-Line Definition 
Information Gathering is the process of collecting system, network, and user-related data about a target to identify potential security vulnerabilities.
