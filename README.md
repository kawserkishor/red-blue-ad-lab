# 🛡️ Hybrid Active Directory Lab – Red vs Blue Simulation

## 🎯 Objective
Simulate real-world attacks and corresponding defensive detections in an enterprise-grade Active Directory (AD) environment using both offensive and defensive tooling.

## 🧱 Lab Architecture
- Windows Server (AD Domain Controller)
- Windows 10 Client
- Kali Linux (Attacker)
- pfSense Firewall
- Suricata IDS
- Wazuh SIEM + Sysmon for host monitoring

## ⚔️ Red Team Simulations
- LLMNR Poisoning
- Pass-the-Hash (PTH)
- Kerberoasting
- GPO Abuse
- Credential Dumping (Mimikatz, CrackMapExec)

## 🛡️ Blue Team Configurations
- Sysmon event collection (Event ID 1, 10, 11, 4688, etc.)
- Wazuh log forwarding + rules
- Suricata alerting for external intrusions
- Sigma rules mapped to MITRE ATT&CK

## 📸 Screenshots
See `/screenshots` for environment setup, attack execution, and alert validation.

## 📂 Folder Structure
- /screenshots    # Setup and attack evidence
- /rules          # Custom Sigma or Wazuh rules
- /reports        # Attack documentation + detection findings

## ✅ Deliverables
- Sigma rule set (.yml)
- Detection logs (.evtx/.json)
- Incident timeline report (PDF)

## 📝 License
MIT
