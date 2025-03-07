# NIST Cybersecurity Framework (CSF)

## What is NIST CSF?
A structured framework for managing cybersecurity risks, widely used in SOC operations for threat detection, incident response, and compliance.

- Risk-Based & Flexible (Not compliance-driven like ISO 27001)
- 5 Core Functions (Identify, Protect, Detect, Respond, Recover)
- Used in SOC for SIEM, Threat Hunting & Incident Handling

## 5 Core Functions & SOC Analyst Role

### 1. Identify (Know Your Assets & Risks)
- Maintain asset inventory (hardware, software, data).
- Perform risk assessments & vulnerability scans.
- Classify critical business assets & dependencies.

### 2. Protect (Implement Security Measures)
- Apply access controls, MFA, & least privilege.
- Use encryption, DLP, endpoint security.
- Conduct security awareness training.

### 3. Detect (Monitor & Identify Threats)
- Set up SIEM (Splunk, ELK, Sentinel) for log analysis.
- Use IDS/IPS, EDR, & anomaly detection.
- Implement threat intelligence & behavioral monitoring.

### 4. Respond (React to Incidents)
- Follow Incident Response (IR) Playbooks (Preparation, Containment, Eradication, Recovery).
- Conduct malware analysis, digital forensics.
- Automate responses using SOAR tools.

### 5. Recover (Post-Incident Actions)
- Execute disaster recovery & system restoration.
- Perform lessons learned sessions & update defenses.
- Improve SOC detection rules based on past incidents.

## Implementation Tiers (Maturity Levels)

### Tier 1 (Partial) – Basic, Ad-Hoc Security
- No formal cybersecurity process; mostly reactive.
- Minimal risk awareness; security is not a priority.
- Example: A startup with no dedicated security team.

### Tier 2 (Risk-Informed) – Some Security Measures
- Some risk management, but not consistently applied.
- Security policies exist but are not strictly enforced.
- Example: A company with a basic firewall & antivirus but no full SOC.

### Tier 3 (Repeatable) – Well-Defined Security Processes
- Security policies & procedures are documented and followed.
- Regular monitoring, incident response, and vulnerability management.
- Example: A SOC that actively monitors threats & responds based on playbooks.

### Tier 4 (Adaptive) – Advanced, Real-Time Security
- Proactive security with real-time threat intelligence.
- AI/automation-based detection & response (e.g., XDR, SOAR).
- Example: A mature SOC using automated threat hunting & AI-driven analysis.
