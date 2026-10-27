# Yudha Pratama

I am an undergraduate in Cyber Security Engineering focused on defensive security, Blue Team operations, and detection engineering.

Most of my time is spent in my homelab: testing detection logic against real-world attack techniques, parsing system telemetry, and building automated triage workflows.

---

### What I Do

* **Detection Engineering:** Researching threat actor behavior, authoring detection logic (Sigma, YARA), and mapping detections to the MITRE ATT&CK matrix.
* **Security Operations & Triage:** Analyzing host and network telemetry to investigate anomalous activity and triage security alerts.
* **Homelab Engineering:** Operating a multi-node Active Directory lab monitored by Wazuh XDR and ELK Stack, integrated with Shuffle SOAR for automated alert enrichment.

---

### Homelab Telemetry Pipeline

```text
[ Adversary Emulation / Endpoints ]
                 │
                 ▼
  Sysmon + Windows Event Logs + Zeek Network Data
                 │
                 ▼
        [ Wazuh XDR / ELK Stack ]  <──  Custom Sigma Rules
                 │
                 ▼
        [ Shuffle SOAR ]  ──>  Alert Enrichment & Incident Triage
```

---

### Security Stack

| Domain | Tools & Technologies |
| :--- | :--- |
| **SIEM & Log Analytics** | Wazuh XDR, Elastic Stack (ELK), Splunk, Kibana |
| **Network Visibility** | Zeek, Suricata, Wireshark, Cisco |
| **Detection & Telemetry** | Sysmon, Sigma Rules, YARA, MITRE ATT&CK |
| **DFIR & Triage** | Volatility 3, Autopsy, CyberChef |
| **SOAR & Threat Intel** | Shuffle SOAR, TheHive, MISP, OpenCTI |
| **Scripting & Automation** | Python, Bash, PowerShell |

---

### Active Focus & Hands-on Practice

* **Platforms:** Active on [LetsDefend](https://letsdefend.io) and [TryHackMe](https://tryhackme.com) (Sherlocks / SOC Analyst Path) investigating alert scenarios, memory artifacts, and PCAP files.
* **Current Lab Milestone:** Writing custom Sigma detections for Active Directory persistence techniques and tuning Wazuh alert rules to minimize false positives.

---

### Featured Repositories

* **[homelab-soc-infrastructure](https://github.com/yudhadevsec)**: Architecture documentation and setup notes for my Active Directory, Wazuh, and ELK pipeline.
* **[detection-rules](https://github.com/yudhadevsec)**: Curated repository of custom Sigma and YARA rules tested against simulated lab attacks.
* **[incident-investigations](https://github.com/yudhadevsec)**: Case studies and walkthroughs of alert investigations, packet captures, and memory analysis.

---

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=red)](https://tryhackme.com/p/yudhadevsec)
[![Email](https://img.shields.io/badge/Email-181717?style=flat-square&logo=gmail&logoColor=white)](mailto:yudhadevsec@gmail.com)
