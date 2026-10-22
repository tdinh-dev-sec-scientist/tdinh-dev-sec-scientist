<h1 align="center">Hi, I'm Truong Dinh (Daniel) 👋</h1> <p align="center"> <b>Cybersecurity Student @ University of South Florida</b> · Detection Engineering · Network Security · Security Research </p> <p align="center"> <a href="https://linkedin.com/in/tdinh123"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a> <a href="https://truongd-portfolio.netlify.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=00C7B7" alt="Portfolio"/></a> <a href="mailto:ddinh1@usf.edu"><img src="https://img.shields.io/badge/Email-ddinh1@usf.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a> <a href="https://doi.org/10.5281/zenodo.23029268"><img src="https://img.shields.io/badge/Preprint-Zenodo-1682D4?style=for-the-badge&logo=zenodo&logoColor=white" alt="Preprint"/></a> </p>
🛡️ About Me

I'm a B.S. Cybersecurity student at the University of South Florida (GPA 4.0/4.0, expected May 2028) focused on detection engineering and network security. I like taking an attacker technique, reproducing it in a lab, and turning it into detection logic that is tested, measured, and low-noise.

🎓 CompTIA Security+ (SY0-701) · Google Cybersecurity Professional Certificate
📘 Working toward HTB Certified Defensive Security Analyst (CDSA) — exam Dec 2026
🔬 Published preprint on IPv6 covert-channel detection — 🏆 2nd Place, STEM, APSU Research Symposium; selected for TN Posters at the Capitol
💼 Seeking cybersecurity internships (SOC, detection engineering, security engineering)
🧰 Tech Stack

Languages

<p> <img src="https://skillicons.dev/icons?i=python,bash,powershell,c,java,mysql&perline=8" alt="Languages"/> </p>

Cloud, DevOps & Systems

<p> <img src="https://skillicons.dev/icons?i=aws,docker,githubactions,linux,kali,ubuntu,windows,postgres,flask,git&perline=10" alt="Cloud and Systems"/> </p>

Security Tooling

<p> <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white"/> <img src="https://img.shields.io/badge/Wazuh-3858E9?style=for-the-badge&logo=wazuh&logoColor=white"/> <img src="https://img.shields.io/badge/Suricata-EF8B00?style=for-the-badge"/> <img src="https://img.shields.io/badge/Sysmon-0078D4?style=for-the-badge&logo=windows&logoColor=white"/> <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white"/> <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge"/> <img src="https://img.shields.io/badge/Scapy-2C3E50?style=for-the-badge"/> <img src="https://img.shields.io/badge/OPNsense-D94F00?style=for-the-badge&logo=opnsense&logoColor=white"/> <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"/> <img src="https://img.shields.io/badge/Atomic_Red_Team-B22222?style=for-the-badge"/> </p>

Frameworks & Data Science

<p> <img src="https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=for-the-badge"/> <img src="https://img.shields.io/badge/CIS_Benchmarks-1F4E79?style=for-the-badge"/> <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/> </p>
📌 Featured Projects
🖥️ NetWatch SOC — Network Detection & Response Platform

Python PostgreSQL Flask Docker Suricata Splunk

Python IDS with byte-signature DPI for 21 protocols and 18 detectors mapped to 16 MITRE ATT&CK techniques
Detected 6/6 held-out attacks vs. Suricata ET Open's 3/6, at 1.0 vs. 26.7 false alerts per host-hour
Replayed 31M labeled packets (CSE-CIC-IDS2018); fixing 5 logic bugs cut false positives from 375 → 1.1 per host-hour
Alert-to-incident correlation (75% reduction) streamed to Splunk via HEC; 392 tests in GitHub Actions CI
🧪 Wazuh Detection Engineering Lab — Home SOC

Wazuh Sysmon Active Directory OPNsense Suricata Atomic Red Team

Segmented 5-VM SOC (OPNsense/Suricata, Server 2025 DC, Windows 11, Wazuh, Kali) with Sysmon and 4688/4104 logging via GPO
Emulated 15 attacks across 18 ATT&CK techniques; wrote 23 custom rules that closed 11 detection gaps
Every rule gated by 78 engine test cases against a live Wazuh manager on each push
🔐 AWS Access Auditor — Cloud Security Posture Automation

Python Boto3 AWS pytest

Read-only auditor with 14 IAM/S3/CloudTrail rules (wildcard policies, missing MFA, stale keys, public buckets)
Mapped CIS AWS Foundations into 11 enforceable controls; ships a least-privilege policy that passes its own check
🔎 BOTSv3 Incident Response Investigation

Splunk SPL Sysmon AWS CloudTrail

Hunted a multi-stage intrusion across 5 Windows/AWS log sources; extracted 8 IOCs and mapped 13 ATT&CK techniques with per-stage SPL detections
🕵️ The Invisible Tunnel — IPv6 Covert Channel Research

Scapy scikit-learn TensorFlow

Proof-of-concept IPv6 C2 channel in Destination Options padding that evaded BPF, Snort, and DPI in a controlled testbed
Stateless RFC 8200 rule with 0 false positives on 1M real MAWI IPv6 packets
📄 Read the preprint
📊 GitHub Stats
<p align="center"> <img height="165" src="https://github-readme-stats.vercel.app/api?username=tdinh-dev-sec-scientist&show_icons=true&hide_border=true&theme=github_dark" alt="GitHub Stats"/> <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tdinh-dev-sec-scientist&layout=compact&hide_border=true&theme=github_dark" alt="Top Languages"/> </p>
🌱 Currently
Preparing for the HTB CDSA exam (HTB Academy SOC Analyst path) and working through HTB Sherlocks
Expanding detection coverage in the Wazuh lab
Practicing data structures & algorithms for technical interviews
<p align="center"><i>"Find what's hidden. Build what detects it."</i> 🛡️</p>
