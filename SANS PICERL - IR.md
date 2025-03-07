# SANS PICERL Incident Response Framework Cheat Sheet

SANS PICERL is a structured Incident Response (IR) framework used by SOC Analysts to detect, respond to, and recover from security incidents.

## 1. PICERL Lifecycle (6 Phases)

### 1. Preparation – Strengthening security before an attack
- Define Incident Response (IR) team & responsibilities
- Implement security tools (SIEM, IDS, EDR)
- Create & test IR playbooks, conduct security training

### 2. Identification – Detecting suspicious activity
- Monitor logs (SIEM, firewall, endpoint alerts)
- Use threat intelligence & MITRE ATT&CK for analysis
- Classify incident severity (Low, Medium, High, Critical)

### 3. Containment – Stopping the attack from spreading
- Isolate compromised systems (Network segmentation)
- Disable affected accounts & reset credentials
- Block malicious IPs, domains, and executables

### 4. Eradication – Removing the threat completely
- Identify & delete malware or persistence mechanisms
- Patch exploited vulnerabilities
- Perform forensic analysis to ensure full removal

### 5. Recovery – Restoring normal operations
- Restore systems from clean backups
- Monitor for signs of reinfection
- Validate security controls before full deployment

### 6. Lessons Learned – Improving future security
- Conduct a post-incident review (What went wrong? What worked?)
- Update SIEM rules & detection use cases
- Train SOC team to improve response times

## 2. SOC Use Cases & IR Actions

- **Phishing Attack** → Analyze email headers, sandbox attachments
- **Ransomware** → Isolate host, check encryption activity, restore from backup
- **Brute-Force Attack** → Detect excessive login attempts, enforce MFA
- **Data Breach** → Investigate unusual outbound traffic, check exfiltrated files
- **Insider Threat** → Monitor privileged access logs, check unusual behavior

## 3. Essential SOC Tools for PICERL

- **SIEM** → Splunk, ELK, Sentinel (Log monitoring)
- **EDR** → CrowdStrike, Velociraptor (Endpoint detection)
- **Threat Intel** → VirusTotal, MISP (IoC & malware analysis)
- **Forensics** → Autopsy, Volatility (Memory & disk investigation)
- **Packet Analysis** → Wireshark, Zeek (Network traffic monitoring)

