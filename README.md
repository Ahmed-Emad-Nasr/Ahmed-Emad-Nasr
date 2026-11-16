<div align="center">

<img src="profile.webp" alt="Ahmed Emad Nasr (0x3omda)" width="600" />

### Ahmed Emad Nasr — Information Security Officer

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3000&pause=800&color=00FF41&center=true&vCenter=true&width=680&lines=Information+Security+Officer;SOC+%7C+Incident+Response+%7C+DFIR;Malware+Analysis+%7C+Detection+Engineering;GRC+%7C+IAM+%7C+Data+Security;Cybersecurity+Instructor+%E2%80%94+AMIT+%26+NTI;eJPT+v2+%7C+CCNA+200-301+%7C+Top+1%25+TryHackMe;%22Detection+is+a+process%2C+not+a+product%22)](https://ahmed-emad-nasr.github.io/)

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-00FF41?style=for-the-badge&logo=githubpages&logoColor=black)](https://ahmed-emad-nasr.github.io/)
[![Blog](https://img.shields.io/badge/Blog-82_cases-FF6B35?style=for-the-badge&logo=readdotcv&logoColor=white)](https://ahmed-emad-nasr.github.io/blog)
[![Teaching](https://img.shields.io/badge/Teaching-160h_diploma-00A6B2?style=for-the-badge&logo=googleclassroom&logoColor=white)](https://ahmed-emad-nasr.github.io/teaching)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-emad-nasr/)
<br/>
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%201%25-CC0000?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Ahmed.Emad.Nasr)
[![CyberDefenders](https://img.shields.io/badge/CyberDefenders-Profile-1F6FEB?style=for-the-badge&logo=letsencrypt&logoColor=white)](https://cyberdefenders.org/p/ahmed.em.nasr)
[![YouTube](https://img.shields.io/badge/YouTube-500%2B%20subs-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@AhmedEmad-0x3omda)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmed.em.nasr@gmail.com)

</div>

---

## `> whoami`

```yaml
name        : Ahmed Emad Nasr
alias       : 0x3omda
role        : Information Security Officer — GRC · SOC · IR/DFIR · Malware Analysis · IAM
teaching    : Cybersecurity Instructor @ AMIT Learning & NTI (160-hour SOC diploma)
education   : B.Sc. CS — InfoSec & Digital Forensics, Benha University (GPA 3.78/4.0)
              Ranked 8th / 900 students
certs       : eJPT v2 (90%) · CCNA 200-301 · RH124 · CCEP · SOC L1+L2 (THM)
location    : Cairo, Egypt
open_to     : Information Security roles — SOC (T1/T2) · Incident Response · Detection Engineering · GRC
```

I build detection labs, break them on purpose, then tune the rules until the noise
goes away. Every case is written up on [**my blog**](https://ahmed-emad-nasr.github.io/blog) —
logs, rules, IOCs and the full report, not just screenshots.

---

## `> tail -n 5 /blog/feed.xml`

<!-- The list between the two markers is refreshed every day by
     .github/workflows/blog-posts.yml from the blog's RSS feed. -->
<!-- BLOG-POST-LIST:START -->
- [SOC L1 Alert Triage Walkthrough (SIEM Prioritization, VirusTotal OSINT & LummaStealer Detection)](https://ahmed-emad-nasr.github.io/blog/soc-l1-alert-triage) <sub>Nov 2026</sub>
- [IR Timeline Analysis Walkthrough (Plaso, Log2Timeline, Pinfo, Psort & Timesketch)](https://ahmed-emad-nasr.github.io/blog/ir-timeline-analysis) <sub>Nov 2026</sub>
- [Threat Intelligence for SOC Walkthrough (Kibana, Uncoder.io, Sigma & ElastAlert)](https://ahmed-emad-nasr.github.io/blog/threat-intelligence-for-soc) <sub>Nov 2026</sub>
- [Vulnerability Scanning Tools Walkthrough (Nmap, Nikto & OpenVAS)](https://ahmed-emad-nasr.github.io/blog/vulnerability-scanning-tools) <sub>Oct 2026</sub>
- [2FA Simple Bypass](https://ahmed-emad-nasr.github.io/blog/2fa-simple-bypass) <sub>Oct 2026</sub>
<!-- BLOG-POST-LIST:END -->

➜ **[All 82 cases](https://ahmed-emad-nasr.github.io/blog)** · searchable by tool, tactic and platform, mapped to MITRE ATT&CK.

---

## `> git log --author=0x3omda --oss`

> **Merged a custom Wazuh detection rule into [SOC Fortress](https://github.com/socfortress) — an open-source SOC project with 1.5k+ stars.**
> Rule contributed via PR, reviewed and merged upstream. → [View the ruleset](https://github.com/socfortress/Wazuh-Rules)

---

## `> ls -la /ops/projects/`

### 🛡️ Enterprise SOC Lab & Insider Threat Deception
`Wazuh` `Suricata` `Zeek` `Sysmon` `auditd` `YARA` `pfSense` `Python`

Full detection stack across 5+ endpoints, with a honeytoken-based insider threat layer on top.

- Simulated **50+ attacks** to validate rules → **95%+ true positive rate**
- Expanded detection coverage by **12%**; alerts surfaced in **under 60s**
- **100% detection rate** across 3 insider threat scenarios; cut false positives by **12 alerts/week**
- Python agent: hashes files → queries VirusTotal → auto-quarantines flagged samples

**[→ SOC lab repo](https://github.com/Ahmed-Emad-Nasr/SOC-Environment)** · **[→ Insider threat repo](https://github.com/Ahmed-Emad-Nasr/insider-threat-detection-deception)** · **[→ Case study](https://ahmed-emad-nasr.github.io/blog/soc-env-depi-r3-project)**

---

### 🦠 Malware Analysis & Prevention Strategy
`YARA` `PEStudio` `CFF Explorer` `FakeNet-NG` `Process Hacker` `Isolated Sandbox`

- Analyzed **20+ samples** (5+ ransomware families) in an isolated lab; extracted actionable IOCs
- Dynamic analysis with FakeNet-NG + Process Hacker to map **C2 traffic behavior**
- Built a **PDF parser** that detects and extracts embedded JavaScript payloads — *18+ downloads*
- Fed IOCs back into Wazuh rules → **MTTD reduced by 25%**

**[→ Repo](https://github.com/Ahmed-Emad-Nasr/Malware-Analysis-and-Prevention-Strategy)** · **[→ PDF parser](https://github.com/Ahmed-Emad-Nasr/3omda-PDFparser-tool)** · **[→ Case study](https://ahmed-emad-nasr.github.io/blog/depi-r4-project)**

---

### ⚖️ VerifAI 360 — AI-Driven GRC Platform
`Python` `Streamlit` `ISO 27001` `NIST CSF` `PCI DSS` `GDPR`

- Dynamic risk scoring, automated gap detection and tailored remediation recommendations
- Automated control mapping across **150+ frameworks** → assessments **15% faster**

**[→ Repo](https://github.com/Ahmed-Emad-Nasr/VerifAI360-Compliance-Framwork)** · **[→ Demo video](https://youtu.be/G-Ys6VuV91g)**

---

### 🔎 Threat Intelligence Platform
`Python` `VirusTotal API` `Exploit-DB` `CLI`

- Python CLI aggregating IOCs and CVEs from multiple feeds into one lookup
- **10 stars on GitHub** — cuts manual enrichment time per investigation

**[→ Repo](https://github.com/Ahmed-Emad-Nasr/Threat-Intelligence-Tool)** · **[→ Demo video](https://youtu.be/u_hezaAwnmM)**

➜ **[Every project](https://ahmed-emad-nasr.github.io/#projects)** on the portfolio, with screenshots and results.

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

## `> cat /teaching/now.txt`

```
AMIT Learning        Cybersecurity Instructor     160-hour track: CCNA → Linux → Security+ → SANS → SIEM
NTI                  Cybersecurity Instructor     42+ students · 85%+ pass rate · 120+ lab hours
GDG                  Best Technical Instructor    1st of 250 instructors · 35+ sessions · 10+ CTF challenges
YouTube              @AhmedEmad-0x3omda           500+ subscribers · 60,000+ views
```

➜ **[The full diploma, module by module, and what my students wrote](https://ahmed-emad-nasr.github.io/teaching)** · [بالعربي](https://ahmed-emad-nasr.github.io/ar/teaching)

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

➜ **[The original certificates](https://ahmed-emad-nasr.github.io/gallery)**

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
📝  Portfolio & blog           — 1,200+ organic visitors · 82 case studies
⭐  DEPI Round 4               — Officially recognized Top Achiever
```

---

## `> htop --user=0x3omda`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ahmed-Emad-Nasr&show_icons=true&include_all_commits=true&count_private=true&theme=chartreuse-dark&hide_border=true" height="160" alt="GitHub stats of Ahmed-Emad-Nasr" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Ahmed-Emad-Nasr&layout=compact&langs_count=6&theme=chartreuse-dark&hide_border=true" height="160" alt="Top languages of Ahmed-Emad-Nasr" />
</div>

---

## `> uptime`

```
Currently   : Detection engineering · DFIR case studies · GRC automation · teaching at AMIT & NTI
Next targets: BTL1 · SC-200 · CHFI · CEH
Active since: 2022
Status      : Learning every single day ↑
```

---

<div align="center">

**Hiring for information security?** I'm open to SOC, incident response, detection engineering and GRC roles.
**Need training for your team?** The diploma, or any module of it — [request a training](mailto:ahmed.em.nasr@gmail.com?subject=Cybersecurity%20training%20request).

📫 [ahmed.em.nasr@gmail.com](mailto:ahmed.em.nasr@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ahmed-emad-nasr/) · [Portfolio](https://ahmed-emad-nasr.github.io/) · [Blog](https://ahmed-emad-nasr.github.io/blog)

<img src="https://komarev.com/ghpvc/?username=Ahmed-Emad-Nasr&style=for-the-badge&color=00FF41&label=PROFILE+VIEWS" alt="Profile views" />

</div>
