# Pyramid of Pain

## Overview
The **Pyramid of Pain** is a cybersecurity framework developed by David J. Bianco that illustrates the impact of blocking different types of indicators of compromise (IOCs) on adversaries. It helps defenders prioritize threat intelligence and detection efforts to maximize disruption to attackers.

## Structure of the Pyramid of Pain
The pyramid consists of six levels, each representing a different type of IOC. As defenders move up the pyramid, disrupting these indicators becomes more impactful for security teams and more difficult for adversaries to bypass.

## Levels of the Pyramid of Pain

### 1. Hash Values (Trivial)
- **Description**: Cryptographic hashes of malicious files (e.g., MD5, SHA-256).
- **Pain Level**: Low.
- **Why It's Easy for Attackers**: Attackers can easily modify a file to generate a new hash.
- **Defender Action**: Blocking hashes is quick but has limited long-term impact.

### 2. IP Addresses (Easy)
- **Description**: IP addresses associated with malicious activity.
- **Pain Level**: Low to moderate.
- **Why It's Easy for Attackers**: Attackers can quickly switch to new IP addresses.
- **Defender Action**: Blocking IPs can disrupt attacks temporarily but is not a long-term solution.

### 3. Domain Names (Simple)
- **Description**: Malicious domain names used for command-and-control (C2) or phishing.
- **Pain Level**: Moderate.
- **Why It's Easy for Attackers**: Attackers can register new domains or use domain generation algorithms (DGAs).
- **Defender Action**: Blocking domains can slow down attackers but is not foolproof.

### 4. Network Artifacts (Annoying)
- **Description**: Patterns in network traffic, such as specific HTTP headers or URIs.
- **Pain Level**: Moderate to high.
- **Why It's Harder for Attackers**: Changing network artifacts may require reconfiguring tools or infrastructure.
- **Defender Action**: Detecting and blocking network artifacts can significantly disrupt operations.

### 5. Host Artifacts (Distressing)
- **Description**: Indicators on a host system, such as registry keys, file paths, or running processes.
- **Pain Level**: High.
- **Why It's Harder for Attackers**: Modifying host artifacts may require rewriting malware or re-engineering tools.
- **Defender Action**: Detecting and removing host artifacts can force attackers to invest significant time and resources.

### 6. TTPs (Devastating)
- **Description**: The adversary's tactics, techniques, and procedures (TTPs) (e.g., exploitation methods, persistence mechanisms).
- **Pain Level**: Very high.
- **Why It's Hardest for Attackers**: Changing TTPs requires retraining, re-tooling, or rethinking their entire approach.
- **Defender Action**: Understanding and disrupting TTPs can completely derail an adversary's campaign.

## Key Takeaways
- **Focus on Higher Levels**: Detecting and disrupting TTPs and host artifacts causes the most pain for attackers.
- **Balance Effort and Impact**: Blocking hashes and IPs is easy but has limited long-term value. Combining these with higher-level actions maximizes effectiveness.
- **Threat Intelligence**: Use the Pyramid of Pain to guide threat intelligence collection, focusing on IOCs that have the greatest impact.

## Practical Applications
### 1. Incident Response
- Prioritize actions that disrupt TTPs and host artifacts to maximize impact.

### 2. Threat Hunting
- Hunt for higher-level IOCs, such as network and host artifacts, to identify advanced threats.

### 3. Security Tooling
- Configure tools to detect and respond to higher-level IOCs, such as TTPs and host artifacts.

### 4. Adversary Emulation
- Simulate attacks to test defenses against higher-level IOCs and improve detection capabilities.

## Example Scenario: Ransomware Attack
### Actions Taken by Defenders:
- **Hash Values**: Block the ransomware file’s hash, but the attacker can easily modify the file.
- **IP Addresses**: Block the C2 server’s IP, but the attacker can switch to a new IP.
- **Domain Names**: Block the malicious domain, but the attacker can register a new one.
- **Network Artifacts**: Detect and block the ransomware’s unique HTTP headers, forcing the attacker to reconfigure their tools.
- **Host Artifacts**: Identify and remove the ransomware’s persistence mechanism, making it harder for the attacker to maintain access.
- **TTPs**: Understand the attacker’s exploitation method and patch the vulnerability, completely disrupting their campaign.

By focusing on higher levels of the Pyramid of Pain, defenders can make it significantly harder for adversaries to achieve their objectives.

