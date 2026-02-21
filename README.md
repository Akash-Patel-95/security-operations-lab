# 🛡 Security Operations Lab

This repository documents my hands-on security monitoring, detection engineering, and vulnerability management work performed in a structured lab environment.

The purpose of this lab is to simulate Security Operations Center (SOC) workflows and strengthen practical skills in log analysis, alert investigation, endpoint monitoring, and network-based detection.

All implementations are built, tested, and documented using enterprise-style standards.

---

## 🎯 Objective

To develop practical SOC L1 skills through:

- Centralized log monitoring
- Endpoint security analysis
- Network intrusion detection
- Vulnerability scanning & remediation review
- Threat enrichment using external intelligence sources
- Alert validation and investigation workflow simulation

---

## 🔎 Lab Projects

### 1️⃣ SIEM Deployment & Endpoint Monitoring
- Deployed Wazuh SIEM on a virtualized environment
- Installed agents on:
  - Linux servers
  - Personal endpoints
  - Virtual infrastructure
- Monitored:
  - Authentication logs
  - File integrity changes
  - Process activity
  - System events
- Integrated VirusTotal API for file hash enrichment
- Validated detection pipeline using EICAR test signature

---

### 2️⃣ Network Intrusion Detection (Planned / In Progress)
- Deploying Suricata IDS in a segmented VLAN environment
- Enabling EVE JSON log output
- Forwarding logs to SIEM
- Simulating:
  - Port scans (Nmap)
  - Brute force attempts
  - Suspicious traffic patterns
- Analyzing generated alerts for false positives and tuning

---

### 3️⃣ Vulnerability Management Lab
- Deployed Nessus vulnerability scanner
- Conducted internal network scans
- Categorized findings by severity
- Reviewed remediation recommendations
- Documented risk exposure and prioritization approach

---

## 🏗 Lab Environment Overview

- Virtualization Platform: Proxmox VE
- Network Segmentation via VLANs
- Firewall enforcement at gateway
- Centralized SIEM logging
- Secure remote access through encrypted tunnel
- Local DNS filtering & monitoring

---

## 🧠 Skills Demonstrated

- SIEM deployment & configuration
- Log analysis fundamentals
- Endpoint monitoring concepts
- IDS log interpretation
- Basic alert triage workflow
- Vulnerability assessment review
- Threat intelligence enrichment
- Network segmentation awareness
- Documentation & structured reporting

---

## 📈 Career Focus

This lab supports my development toward:

- SOC Analyst (L1/L2)
- Security Operations
- Detection Engineering (entry-level)

I focus on building foundational security operations skills through practical implementation and disciplined documentation.
