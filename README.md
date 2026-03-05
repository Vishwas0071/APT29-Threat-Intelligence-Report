# Threat Intelligence Report — APT29 (Cozy Bear)

## Overview
This is an independently researched threat intelligence report profiling APT29 — also known as Cozy Bear and Midnight Blizzard — a nation-state threat actor attributed to Russia's Foreign Intelligence Service (SVR). All information in this report is sourced from publicly available OSINT including MITRE ATT&CK, CISA advisories, Mandiant reports, and NCSC UK publications.

**TLP: WHITE — No distribution restrictions. Safe to share publicly.**

## What This Report Covers

### 1. Threat Actor Profile
- Full attribution details and confidence level
- Active since, primary motivation, target sectors
- Geographic targeting pattern
- Sophistication assessment

### 2. TTPs — MITRE ATT&CK Mapping
| Tactic | Technique | Description |
|--------|-----------|-------------|
| Initial Access | T1566.002 — Spearphishing Link | Highly targeted phishing emails |
| Initial Access | T1195.002 — Supply Chain Compromise | SolarWinds build pipeline compromise |
| Execution | T1059.001 — PowerShell | Fileless execution via encoded commands |
| Defense Evasion | T1102 — Web Service as C2 | Dropbox, OneDrive used as C2 channels |
| Credential Access | T1003.001 — LSASS Memory | Custom credential dumping tools |
| Exfiltration | T1048.002 — Encrypted Exfiltration | HTTPS exfiltration to cloud infrastructure |

### 3. Notable Operations Analysed
- **SolarWinds Supply Chain Attack (2020)** — 18,000 organisations compromised
- **COVID-19 Vaccine Research Theft (2020)** — Oxford, AstraZeneca, EMA targeted
- **DNC Hack (2016)** — Political intelligence collection

### 4. Indicators of Compromise (IOCs)
- Historical C2 domains and IP addresses
- File hashes (SHA256) for known malware samples
- Behavioural indicators for detection

### 5. Defensive Recommendations
- Detection controls (PowerShell logging, UEBA, DNS monitoring)
- Preventive controls (MFA, Zero Trust, supply chain security)
- IR considerations for nation-state intrusions

## Sources Used
- MITRE ATT&CK — APT29 Group Profile (attack.mitre.org/groups/G0016)
- CISA Advisory AA21-148A
- Mandiant — UNC2452 / SUNBURST Analysis
- NCSC UK — APT29 COVID-19 vaccine research advisory
- Microsoft MSTIC — Midnight Blizzard profile
- FireEye — SolarWinds supply chain compromise report

## Skills Demonstrated
- Threat intelligence research and analysis
- MITRE ATT&CK framework proficiency
- IOC identification and documentation
- Threat actor profiling methodology
- TLP classification and report formatting
- Defensive recommendation development

## About Me
**Vishwas M H** | B.Tech Computer Science & Engineering  
Former .NET Full Stack Developer | Transitioning to Cybersecurity  
Actively preparing for MSc Cybersecurity (Ireland, 2026 intake)  
📧 Connect with me on [www.linkedin.com/in/vishwas-m-h-6830bb1b9]
