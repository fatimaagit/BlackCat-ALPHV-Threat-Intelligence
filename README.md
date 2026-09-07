# BlackCat-ALPHV-Threat-Intelligence
Threat intelligence and adversary analysis of BlackCat/ALPHV ransomware using MITRE ATT&amp;CK, CISA reporting, IOC analysis, and attack-chain mapping.

## Overview

This project analyzes **BlackCat/ALPHV ransomware** to understand its attack methods and identify opportunities for defenders to detect and mitigate its activity.

The research uses **MITRE ATT&CK, CISA reporting, IOC analysis, and attack-chain mapping**.

### Research Question

> How does BlackCat/ALPHV conduct attacks against organizations, and what defensive measures can organizations use to detect and mitigate its activity?

---

## Attack Chain

**Initial Access → Account Compromise → Remote Access → Credential & Privilege Abuse → Defense Evasion → Ransomware Impact**

The attack chain maps BlackCat/ALPHV activity from gaining access to the final ransomware impact.

---

## IOC Analysis

Analyzed **5 IOCs** from CISA reporting:

* **2 IP addresses** — C2 and remote-access infrastructure
* **3 SHA-256 hashes** — ALPHV encryptor, antivirus-tools-killer, and Cobalt Strike Beacon

The IOC analysis focuses on identifying how these indicators can be used for defensive investigation and detection.

---

## MITRE ATT&CK Techniques

| Technique                 | ID        |
| ------------------------- | --------- |
| Access Token Manipulation | T1134     |
| Windows Command Shell     | T1059.003 |
| Inhibit System Recovery   | T1490     |
| Phishing for Information  | T1598     |
| Compromise Accounts       | T1586     |

---

## Defensive Focus

* Detect unusual authentication and account activity
* Monitor privilege and access-token changes
* Investigate remote-access and command-line activity
* Protect backup and recovery systems
* Search for known IOCs and correlate related activity

---

## Skills

**Threat Intelligence · MITRE ATT&CK · IOC Analysis · TTP Analysis · Adversary Analysis · Attack Chain Mapping · Defensive Detection · Cybersecurity Reporting**

---

## Sources

* CISA — BlackCat Ransomware Advisory (AA23-353A)
* MITRE ATT&CK — BlackCat/ALPHV
* CommTel — IOC defensive guidance
