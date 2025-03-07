# Cyber Kill Chain: A SOC Analyst’s Cheat Sheet

## 1. Introduction to Cyber Kill Chain
The Cyber Kill Chain, developed by Lockheed Martin, is a framework that maps the stages of a cyberattack. SOC analysts use it to detect, analyze, and respond to threats.

## 2. Stages of the Cyber Kill Chain & SOC Response
### **1. Reconnaissance (Information Gathering)**
- **Attacker Actions:** Scanning, OSINT, Shodan, Nmap
- **SOC Detection:** Monitor network scans, analyze logs for anomalies

### **2. Weaponization (Creating Malicious Payloads)**
- **Attacker Actions:** Malware creation, phishing attachments, exploit kits
- **SOC Detection:** Threat intelligence feeds, sandbox analysis, signature-based detection

### **3. Delivery (Deploying the Payload)**
- **Attacker Actions:** Phishing emails, drive-by downloads, infected USBs
- **SOC Detection:** Email security tools, SIEM alerts, sandbox execution

### **4. Exploitation (Executing the Exploit)**
- **Attacker Actions:** Exploiting vulnerabilities, privilege escalation
- **SOC Detection:** IDS/IPS alerts, vulnerability scans, system log analysis

### **5. Installation (Malware or Backdoor Deployment)**
- **Attacker Actions:** Rootkits, persistence mechanisms (registry changes, scheduled tasks)
- **SOC Detection:** EDR monitoring, registry analysis, autorun detection

### **6. Command & Control (C2) (Remote Control of the System)**
- **Attacker Actions:** DNS tunneling, beaconing to C2 servers
- **SOC Detection:** Snort, Suricata, Wireshark (monitoring abnormal outbound traffic)

### **7. Actions on Objectives (Exfiltration, Lateral Movement, etc.)**
- **Attacker Actions:** Data theft, ransomware deployment, system destruction
- **SOC Detection:** File integrity monitoring, login anomalies, network traffic analysis

## 3. Cyber Kill Chain vs. MITRE ATT&CK
- **Cyber Kill Chain:** Linear attack model focused on the attack lifecycle.
- **MITRE ATT&CK:** Matrix of Tactics, Techniques, and Procedures (TTPs) used for threat-hunting and adversary mapping.

## 4. SOC Analyst’s Role in Breaking the Kill Chain
- **Security Tools:** SIEM, IDS/IPS, EDR, Firewalls
- **Monitoring & Detection:** Log analysis, alert correlation, anomaly detection
- **Incident Response:** Containment, mitigation, and threat eradication

Using the Cyber Kill Chain, SOC analysts can proactively defend against cyber threats and break the attack lifecycle before damage occurs.

