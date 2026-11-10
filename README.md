<!-- Truong Dinh's GitHub profile -->

<h1 align="center">Hi, I'm Truong Dinh 👋</h1>

<p align="center">
  <strong>Cybersecurity student at the University of South Florida</strong><br/>
  Detection Engineering · Cloud Security · Network Security Research
</p>

<p align="center">
  <a href="https://linkedin.com/in/tdinh123"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://truongdinh.dev"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:ddinh1@usf.edu"><img src="https://img.shields.io/badge/Email-ddinh1%40usf.edu-374151?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://doi.org/10.5281/zenodo.23029268"><img src="https://img.shields.io/badge/IPv6%20Research-Zenodo-1682D4?style=for-the-badge&logo=zenodo&logoColor=white" alt="IPv6 research preprint"/></a>
</p>

---

## 🛡️ About

I'm pursuing a **B.S. in Cybersecurity at USF** with a **4.0 GPA** (expected May 2028). I build detection systems, replay real traffic, and test whether security controls catch the behaviors they claim to catch.

- **Focus:** detection engineering, SOC workflows, cloud security, and network defense
- **Certifications:** CompTIA Security+ (SY0-701) and Google Cybersecurity Professional Certificate
- **Programs:** HTB SOC Analyst Job-Role Path; Bellini Mentorship Program inaugural cohort
- **Competition:** perfect score in the solo Dragos CTF 2026, competing against 1,000+ teams in ICS/OT forensics
- **Research:** 2nd Place, STEM, APSU Research Symposium; selected to present at Tennessee Posters at the Capitol
- **CDSA:** completed the 7-day practical exam and report in November 2026; result pending
- **Open to cybersecurity internships** in SOC, detection engineering, and security engineering

## 🧪 Featured Projects

### [NetWatch SOC](https://github.com/tdinh-dev-sec-scientist/Netwatch_SOC) · Network detection and response
`Python` `PostgreSQL` `Flask` `Docker` `Suricata` `Splunk`

- Detected **6/6 held-out attacks** in CSE-CIC-IDS2018 traffic; Suricata ET Open detected 3/6.
- Built byte-signature DPI for **21 protocols** and 18 detectors mapped to 16 MITRE ATT&CK techniques.
- Replayed 31M labeled packets and fixed five detection bugs, reducing false alerts from **375 to 1.1 per host-hour** without threshold tuning.
- Correlated alerts into incidents, reducing alert volume by **75%**.

### [Vorrin](https://github.com/tdinh-dev-sec-scientist/Vorrin) · AWS security auditing and guardrails
`Python` `AWS` `Terraform` `OPA/Rego` `GitHub Actions` `Amazon Bedrock`

- Built a read-only auditor with **14 IAM, S3, and CloudTrail checks**, including 11 mapped to CIS AWS Foundations.
- Validated all rules against **98 labeled fixtures** with zero missed findings and zero false positives.
- Deployed scheduled scans through a read-only cross-account role; release evidence is SHA-256 bound.
- Shipped an invited-user analyst on Bedrock with constrained outputs, citation allow-lists, Guardrails, and prompt-injection evaluations.
- [Explore the fixture-backed demo console](https://tdinh-dev-sec-scientist.github.io/Vorrin/console/).

### [Wazuh Detection Engineering Lab](https://github.com/tdinh-dev-sec-scientist/wazuh-detection-engineering-lab) · Home SOC
`Wazuh` `Sysmon` `Active Directory` `OPNsense` `Suricata` `Atomic Red Team`

- Built a segmented **5-VM SOC** and emulated 15 attacks across MITRE ATT&CK techniques.
- Wrote **23 custom rules** that closed 11 gaps in default detection coverage.
- Gated rule changes with **78 engine test cases** against a live Wazuh manager.

### [The Invisible Tunnel](https://github.com/tdinh-dev-sec-scientist/Ipv6-eh-c2-detection) · IPv6 covert-channel research
`Python` `Scapy` `scikit-learn` `TensorFlow`

- Built a proof-of-concept IPv6 command-and-control channel in Destination Options padding that evaded BPF, Snort, and DPI in a controlled testbed.
- Wrote a stateless RFC 8200 detection rule with **zero false positives on 1M real MAWI IPv6 packets**.
- [Read the Zenodo preprint](https://doi.org/10.5281/zenodo.23029268).

### [BOTSv3 Incident Response Investigation](https://github.com/tdinh-dev-sec-scientist/botsv3-soc-investigation)
`Splunk` `SPL` `Sysmon` `AWS CloudTrail`

- Investigated **2.8M events**, extracted eight IOCs, mapped 13 ATT&CK techniques, and wrote five detection queries.

## 🎓 Experience

**Undergraduate Security Researcher, Austin Peay State University** · Dec 2025 to Aug 2026  
Researched IPv6 covert-channel detection with Dr. James Church; published a Zenodo preprint and presented the work through Tennessee Posters at the Capitol.

**Computer Science Teaching Assistant, Austin Peay State University** · Jan 2026 to May 2026  
Helped 30+ students with Java debugging, object-oriented programming, and data structures through office hours, lab grading, and study guides.

**Peer Leader, Honors Program, Austin Peay State University** · Jul 2025 to Dec 2025  
Led 15 course sessions, mentored 30 students one-on-one, and published 16 weekly cybersecurity-awareness posts.

## 🧰 Technical Skills

**Detection and SOC:** Wazuh, Splunk/SPL, Suricata, Sysmon, MITRE ATT&CK, Atomic Red Team, incident response  
**Cloud and DevSecOps:** AWS, Boto3, Terraform, Docker, GitHub Actions, OPA/Rego, Cosign, Syft/Grype  
**Systems and networking:** Active Directory, Linux, OPNsense, VMware, TCP/IP, IPv6, Wireshark, Scapy, Nmap  
**Languages and data:** Python, Bash, PowerShell, SQL, C, Java, pandas, scikit-learn, TensorFlow

## 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=tdinh-dev-sec-scientist&show_icons=true&hide_border=true&theme=github_dark" alt="GitHub statistics"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tdinh-dev-sec-scientist&layout=compact&langs_count=6&hide_border=true&theme=github_dark" alt="Most used programming languages"/>
</p>

---

<p align="center"><i>Build detections. Test them against evidence.</i> 🛡️</p>
