# Rishabh Sharma — Security Engineering · Detection & Response · SecOps

Master of Cyber Security (UTS, 2026). I build hands-on labs and automation that
mirror real enterprise detection and response — SIEM pipelines, homelab telemetry,
and LLM-assisted triage — then document them so the work is reproducible, not just claimed.

📍 Sydney, Australia · full working rights
🔗 [rish-infosec.co](https://rish-infosec.co) · ✉️ rishabhh.infosec@gmail.com

---

## Featured Projects

### 🤖 ai-soc-analyst — Automated Tier-1 SOC Triage
Automates Tier-1 alert triage end-to-end.
- **Enrichment:** AbuseIPDB + VirusTotal reputation lookups on observables
- **Validation:** maps and validates alerts against **MITRE ATT&CK**
- **LLM triage:** Claude API integration with anti-hallucination guardrails to produce structured verdicts
- **SIEM:** Elasticsearch/Kibana ingesting **Sysmon + Winlogbeat** from a Windows DC
`Python` · `Elasticsearch` · `Claude API` · `MITRE ATT&CK` · `Sysmon`

### 🔎 ai-ops-rca-engine — AIOps Root-Cause Analysis *(in progress)*
Ingests homelab telemetry, correlates events across a network topology, and uses an
LLM to produce **ranked root-cause hypotheses**.
- Multi-node homelab (`log-server`, `V1`, `dc01`) across two subnets
- **Beats** telemetry (Filebeat, Metricbeat, Winlogbeat) over a dedicated management plane
- Modular Python ingestion + correlation pipeline
`Python` · `Elasticsearch` · `Beats` · `LLM correlation`

---

## Infrastructure & Networking Labs

### Enterprise ELK SIEM + Active Directory Homelab
Centralised logging/SIEM with ELK; detection validation against generated test events;
hardened services with iptables and systemd. Windows Server AD DS / DNS / DHCP / GPO.

### Routed Multi-Site Network Lab
VMware + Debian + FRR. **OSPF**, 802.1Q VLAN segmentation, inter-VLAN routing, and
ACL-style firewall policy with end-to-end reachability testing and a documented test plan.

### Enterprise Network Design (Cisco IOS)
Multi-site IPv4 **VLSM** design with static/default routing + **OSPFv2**, VLANs / trunking /
router-on-a-stick, and edge **NAT/PAT** with ISP failover validation.

---

## Skills

**Detection & Response** — alert triage, SIEM design, log analysis, MITRE ATT&CK, detection validation, security hardening
**SIEM / Telemetry** — Elasticsearch, Logstash, Kibana, Beats (Filebeat/Metricbeat/Winlogbeat), Sysmon, Winlogbeat
**Networking** — TCP/IP, VLSM subnetting, OSPF/OSPFv2, VLANs, 802.1Q, inter-VLAN routing, NAT/PAT, segmentation
**Systems** — Linux (Debian/Ubuntu), systemd, iptables, SSH/SFTP · Windows Server AD DS / DNS / DHCP / GPO
**Automation** — Python, Bash, PowerShell, Ansible · Git · VMware
**Offensive (internship exposure)** — web app pentesting, Burp Suite, nmap

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://linkedin.com/in/rishabh-sharma-482a4321a)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github)](https://github.com/SecurelyClueless)
[![Hack The Box](https://img.shields.io/badge/Hack%20The%20Box-black?logo=hackthebox&logoColor=green)](https://app.hackthebox.com/profile/SecurelyClueless)
