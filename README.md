<div align="center">

```
 ██████╗ ██╗  ██╗██████╗  ██████╗ ███╗   ███╗ █████╗ ██████╗ 
██╔═████╗╚██╗██╔╝╚════██╗██╔═══██╗████╗ ████║██╔══██╗██╔══██╗
██║██╔██║ ╚███╔╝  █████╔╝██║   ██║██╔████╔██║███████║██║  ██║
████╔╝██║ ██╔██╗  ╚═══██╗██║   ██║██║╚██╔╝██║██╔══██║██║  ██║
╚██████╔╝██╔╝ ██╗██████╔╝╚██████╔╝██║ ╚═╝ ██║██║  ██║██████╔╝
 ╚═════╝ ╚═╝  ╚═╝╚═════╝  ╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═╝╚═════╝ 
```

### Ahmed Emad Nasr — SOC & DFIR Analyst

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3000&pause=800&color=00FF41&center=true&vCenter=true&width=680&lines=SOC+Analyst+%7C+Blue+Team+Operator;Incident+Response+%7C+DFIR+%7C+Malware+Analysis;Detection+Engineering+%7C+Threat+Hunting+%7C+GRC;eJPT+v2+%7C+CCNA+200-301+%7C+Top+1%25+TryHackMe;%22Detection+is+a+process%2C+not+a+product%22)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-emad/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-00FF41?style=for-the-badge&logo=githubpages&logoColor=black)](https://ahmedemad.dev)
[![Blog](https://img.shields.io/badge/Blog-Read-FF6B35?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@YOUR_HANDLE)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%201%25-CC0000?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/YOUR_HANDLE)
[![YouTube](https://img.shields.io/badge/YouTube-500%2B%20subs-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@YOUR_HANDLE)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmed.em.nasr@gmail.com)

</div>

---

## `> whoami`

```yaml
name        : Ahmed Emad Nasr
alias       : 0x3omda
role        : SOC Analyst · IR/DFIR Analyst · Cybersecurity Instructor
education   : B.Sc. CS — InfoSec & Digital Forensics, Benha University (GPA 3.78/4.0)
              Ranked 8th / 900 students
focus       : Blue Team · SOC Operations · Detection Engineering · DFIR · GRC
certs       : eJPT v2 (90%) · CCNA 200-301 · RH124 · CCEP · SOC L1+L2 (THM)
location    : Cairo, Egypt
open_to     : SOC Analyst (T1/T2) · Incident Response · Detection Engineering
```

I build detection labs, break them on purpose, then tune the rules until the noise
goes away. Most of what I do lives in the repos below — logs, rules, IOCs and writeups
included, not just screenshots.

---

## `> git log --author=0x3omda --oss`

> **Merged a custom Wazuh detection rule into [SOC Fortress](https://github.com/socfortress) — an open-source SOC project with 1.5k+ stars.**
> Rule contributed via PR, reviewed and merged upstream. → [View the PR](https://github.com/socfortress/Wazuh-Rules/pulls)

---

## `> ls -la /ops/projects/`

### 🛡️ Enterprise SOC Lab & Insider Threat Deception
`Wazuh` `Suricata` `Zeek` `Sysmon` `auditd` `YARA` `pfSense` `Python`

Full detection stack across 5+ endpoints, with a honeytoken-based insider threat layer on top.

- Simulated **50+ attacks** to validate rules → **95%+ true positive rate**
- Expanded detection coverage by **12%**; alerts surfaced in **under 60s**
- **100% detection rate** across 3 insider threat scenarios; cut false positives by **12 alerts/week**
- Python agent: hashes files → queries VirusTotal → auto-quarantines flagged samples

**[→ Repo](https://github.com/YOUR_USERNAME/REPO)** · **[→ Demo](#)**

---

### 🦠 Malware Analysis & Prevention Strategy
`YARA` `PEStudio` `CFF Explorer` `FakeNet-NG` `Process Hacker` `Isolated Sandbox`

- Analyzed **20+ samples** (5+ ransomware families) in an isolated lab; extracted actionable IOCs
- Dynamic analysis with FakeNet-NG + Process Hacker to map **C2 traffic behavior**
- Built a **PDF parser** that detects and extracts embedded JavaScript payloads — *18+ downloads*
- Fed IOCs back into Wazuh rules → **MTTD reduced by 25%**

**[→ Repo](https://github.com/YOUR_USERNAME/REPO)** · **[→ Demo](#)**

---

### ⚖️ VerifAI 360 — AI-Driven GRC Platform
`Python` `Streamlit` `ISO 27001` `NIST CSF` `PCI DSS` `GDPR`

- Dynamic risk scoring, automated gap detection and tailored remediation recommendations
- Automated control mapping across **150+ frameworks** → assessments **15% faster**

**[→ Repo](https://github.com/YOUR_USERNAME/REPO)** · **[→ Demo](#)**

---

### 🔎 Threat Intelligence Platform
`Python` `VirusTotal API` `Exploit-DB` `CLI`

- Python CLI aggregating IOCs and CVEs from multiple feeds into one lookup
- **10 stars on GitHub** — cuts manual enrichment time per investigation

**[→ Repo](https://github.com/YOUR_USERNAME/REPO)**

---

## `> cat /ops/defense_map.txt`

```
               ┌──────────────────────┐
               │   INCIDENT RESPONSE  │
               │      NIST 800-61     │
               └───────────┬──────────┘
                           │
   ┌────────────┐   ┌──────▼─────┐   ┌────────────────┐
   │    DFIR    │◄──┤  0x3OMDA   ├──►│MALWARE ANALYSIS│
   │ Volatility │   │ SOC / BLUE │   │ YARA·PEStudio  │
   │  Autopsy   │   │    TEAM    │   │     Sandbox    │
   └────────────┘   └──────┬─────┘   └────────────────┘
                           │
   ┌────────────┐   ┌──────▼─────┐   ┌────────────────┐
   │THREAT HUNT │◄──┤PURPLE TEAM ├──►│      GRC       │
   │SIEM·ATT&CK │   │ ART·ATT&CK │   │ ISO27001·NIST  │
   └────────────┘   └────────────┘   └────────────────┘
```

---

## `> cat /skills/arsenal.conf`

**SIEM & Monitoring**

![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat-square&logo=elastic&logoColor=white)
![ELK](https://img.shields.io/badge/ELK%20Stack-005571?style=flat-square&logo=elastic&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Security Onion](https://img.shields.io/badge/Security%20Onion-1C6B2A?style=flat-square&logo=linux&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-E34F26?style=flat-square)
![Zeek](https://img.shields.io/badge/Zeek-006DAD?style=flat-square)
![Sysmon](https://img.shields.io/badge/Sysmon-0078D4?style=flat-square&logo=windows&logoColor=white)

**DFIR & Malware Analysis**

![Volatility](https://img.shields.io/badge/Volatility-3C3C3D?style=flat-square)
![Autopsy](https://img.shields.io/badge/Autopsy-6A4C93?style=flat-square)
![YARA](https://img.shields.io/badge/YARA-FF6F00?style=flat-square)
![PEStudio](https://img.shields.io/badge/PEStudio-CC0000?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![FakeNet-NG](https://img.shields.io/badge/FakeNet--NG-444444?style=flat-square)
![MISP](https://img.shields.io/badge/MISP-003087?style=flat-square)
![TheHive](https://img.shields.io/badge/TheHive-F4B400?style=flat-square&logoColor=black)

**Purple Team & Offensive**

![ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-005571?style=flat-square)
![Atomic Red Team](https://img.shields.io/badge/Atomic%20Red%20Team-9900FF?style=flat-square)
![Metasploit](https://img.shields.io/badge/Metasploit-2596BE?style=flat-square)
![BloodHound](https://img.shields.io/badge/BloodHound-990000?style=flat-square)
![Nmap](https://img.shields.io/badge/Nmap-004880?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6F00?style=flat-square)

**Automation & Infrastructure**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white)

**GRC & Frameworks**

![ISO 27001](https://img.shields.io/badge/ISO%2027001-003366?style=flat-square)
![NIST CSF](https://img.shields.io/badge/NIST%20CSF-FF6F00?style=flat-square)
![NIST 800-61](https://img.shields.io/badge/NIST%20800--61-FF6F00?style=flat-square)
![PCI DSS](https://img.shields.io/badge/PCI%20DSS-004680?style=flat-square)
![CIS Benchmarks](https://img.shields.io/badge/CIS%20Benchmarks-6A4C93?style=flat-square)

---

## `> cat /certs/achievements.log`

| Year | Certification | Issuer | Result |
|:----:|:--------------|:-------|:-------|
| 2026 | eJPT v2 | INE | **90%** |
| 2026 | Certified Cybersecurity Educator Professional (CCEP) | Red Team Leaders | Active |
| 2026 | Red Hat System Administration I (RH124) | Red Hat | Active |
| 2025 | Information Security Analyst | DEPI | Active |
| 2025 | SOC Level 1 & SOC Level 2 Paths | TryHackMe | Active |
| 2025 | Malware Analysis Fundamentals | ITI Mahara-Tech | Active |
| 2025 | Cyber Threat Intelligence 101 | arcX | Active |
| 2025 | HCCDA-Tech Essentials | Huawei | Active |
| 2024 | CCNA 200-301 | Cisco | Active |

---

## `> cat /awards/trophies.txt`

```
🏆  Best Technical Instructor  — GDG, ranked 1st out of 250 instructors
🎓  Academic Excellence        — 8th / 900 in InfoSec & Digital Forensics
🔴  TryHackMe                  — Top 1% globally
🏅  ITI & CyberTalents CTF     — 44th / 450
🌍  HackTheBox University CTF  — 199th / 1,128 (Binary Badlands 2024)
💻  ECPC                       — Top 250 / 1,500 teams
🎥  YouTube channel            — 500+ subscribers · 60,000+ views
📝  Portfolio & blog           — 1,200+ organic visitors · 40+ writeups
⭐  DEPI Round 4               — Officially recognized Top Achiever
```

---

## `> htop --user=0x3omda`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&include_all_commits=true&count_private=true&theme=chartreuse-dark&hide_border=true" height="160" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=YOUR_USERNAME&layout=compact&langs_count=6&theme=chartreuse-dark&hide_border=true" height="160" alt="Top Languages" />
</div>

---

## `> uptime`

```
Currently   : Detection engineering · DFIR case studies · GRC automation
Next targets: BTL1 · SC-200 · CHFI · CEH
Active since: 2022
Status      : Learning every single day ↑
```

---

<div align="center">

**Looking for a SOC / IR analyst?** I'm open to junior & mid-level blue team roles.
📫 [ahmed.em.nasr@gmail.com](mailto:ahmed.em.nasr@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ahmed-emad/) · [Portfolio](https://ahmedemad.dev)

<img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=for-the-badge&color=00FF41&label=PROFILE+VIEWS" alt="Profile Views" />

</div>
