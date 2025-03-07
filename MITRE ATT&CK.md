# MITRE ATT&CK Framework: A SOC Analyst’s Guide

## 1. Introduction to MITRE ATT&CK
MITRE ATT&CK is a globally accessible framework detailing adversary tactics, techniques, and procedures (TTPs). It helps SOC analysts detect, analyze, and respond to cyber threats. Unlike the Cyber Kill Chain, ATT&CK provides a more granular, real-world representation of attack behaviors.

## 2. Structure of MITRE ATT&CK
- **Tactics:** Goals behind attacks (e.g., Initial Access, Lateral Movement)
- **Techniques:** Methods attackers use to achieve tactics
- **Procedures:** Specific implementations by threat actors
- **Groups & Software:** Mapping adversary behaviors

## 3. Understanding ATT&CK Matrices
- **Enterprise Matrix:** Covers Windows, Linux, macOS
- **Cloud Matrix:** Attacks on AWS, Azure, GCP
- **Mobile Matrix:** Threats to iOS, Android
- **ICS Matrix:** Attacks on Industrial Control Systems

## 4. MITRE ATT&CK Tactics & Techniques (Enterprise Matrix)
- **Reconnaissance:** OSINT, scanning, phishing
- **Resource Development:** Setting up malicious tools, C2 servers
- **Initial Access:** Phishing, credential stuffing, exploits
- **Execution:** PowerShell, scripts, macros
- **Persistence:** Backdoors, registry modifications
- **Privilege Escalation:** Exploiting vulnerabilities
- **Defense Evasion:** Disabling logs, obfuscation
- **Credential Access:** Mimikatz, keylogging
- **Discovery:** Network mapping, user enumeration
- **Lateral Movement:** Pass-the-hash, RDP hijacking
- **Collection:** Data capture, screenshots
- **Exfiltration & Impact:** Data theft, ransomware

## 5. How SOC Analysts Use MITRE ATT&CK
- **Threat Intelligence Mapping:** Identifying adversary tactics
- **SIEM & EDR Rule Creation:** Mapping attack techniques to alerts
- **Incident Response:** Responding effectively to cyber threats
- **Purple Teaming:** Collaborating with Red Teams to enhance detection

## 6. Tools & Resources to Learn MITRE ATT&CK
- **MITRE ATT&CK Navigator:** Threat mapping tool
- **Atomic Red Team:** Simulating ATT&CK techniques
- **Sigma Rules:** Writing detection rules
- **SIEM Platforms (Elastic Security, Splunk, Sentinel):** Monitoring ATT&CK techniques

Understanding and leveraging MITRE ATT&CK enhances a SOC Analyst’s ability to detect and mitigate cyber threats effectively.

