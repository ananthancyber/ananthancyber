# Ananthan D

### SOC / Blue Team Cybersecurity | Detection Engineering | Security Monitoring & Investigation

B.Tech Information Technology graduate building hands-on experience in **SOC operations, SIEM, threat detection, log analysis, Active Directory security, and security automation** through practical security labs.

My work focuses on the defensive workflow:

**Attack Simulation → Telemetry → Detection → Investigation → MITRE ATT&CK → Reporting**

I build security labs to understand not only how attacks occur, but how defenders can **detect, investigate, correlate, and document them.**

---

## Featured Cybersecurity Projects

## 🛡️ [Active Directory Attack & Detection Lab](https://github.com/ananthancyber/Project-03-AD-Attack-Detection-Lab)

**Windows Server 2022 · Active Directory · Wazuh · Sysmon · BloodHound · MITRE ATT&CK**

End-to-end Active Directory security lab built to simulate attack activity and investigate the resulting Windows telemetry from a SOC analyst perspective.

**Highlights**
- Built an isolated Active Directory environment with a Windows Server 2022 Domain Controller and Windows 10 domain endpoint
- Configured Windows Security auditing, Sysmon, and Wazuh telemetry collection
- Simulated and investigated Kerberoasting, AS-REP Roasting, Pass-the-Hash, DCSync, NTLM authentication anomalies, and SMB lateral authentication
- Developed behavioral detection logic around Windows Security Events including `4624`, `4662`, `4768`, `4769`, and `4776`
- Used BloodHound for Active Directory attack-path analysis and remediation validation
- Correlated endpoint and Domain Controller telemetry during SOC-style investigations
- Mapped observed attack activity to MITRE ATT&CK
- Produced attack documentation, detection specifications, investigation reports, and supporting evidence

**SOC Skills:** Active Directory Security · Windows Event Analysis · Detection Engineering · Authentication Analysis · Event Correlation · MITRE ATT&CK · Investigation

---

## 🤖 [AI SOC Log Triage Assistant](https://github.com/ananthancyber/ai-soc-log-triage-assistant)

**Python · Wazuh · Ollama · Qwen 2.5 · FAISS · Streamlit · pytest**

Local AI-assisted SOC triage pipeline designed to transform exported Wazuh alerts into structured investigation reports while keeping security data on the local system.

**Highlights**
- Parses Wazuh alert JSON/JSONL and extracts investigation-relevant fields
- Uses Retrieval-Augmented Generation with FAISS semantic search
- Runs local LLM inference through Ollama using Qwen 2.5
- Uses local `nomic-embed-text` embeddings for knowledge retrieval
- Grounds analysis in a cybersecurity knowledge base before generating reports
- Uses evidence-constrained prompting with an explicit **"Insufficient evidence"** fallback for unsupported MITRE ATT&CK attribution
- Provides a Streamlit interface for alert upload, analysis, report viewing, and download
- Includes pytest coverage for core parsing, prompt construction, and report-generation functionality

**SOC + AI Skills:** Alert Triage · Log Analysis · Security Automation · RAG · Local LLMs · MITRE ATT&CK-Aware Analysis · Python

> **Scope:** This project analyzes exported Wazuh alerts locally. It is not presented as a live Wazuh API/SIEM integration.

---

## 🔍 [Wazuh Blue Team Detection Lab](https://github.com/ananthancyber/wazuh-blue-team-detection-lab)

**Wazuh 4.14.6 · Ubuntu · Docker · Docker Compose · Kali Linux**

Blue Team home lab built to understand how security telemetry moves from endpoint activity to SIEM detection and analyst investigation.

**Highlights**
- Deployed a containerized Wazuh SIEM/XDR environment using Docker Compose
- Configured endpoint monitoring and security-event collection
- Implemented File Integrity Monitoring
- Investigated SSH authentication activity and security alerts
- Developed custom Wazuh detection rules using `local_rules.xml`
- Implemented rule inheritance and frequency/timeframe correlation logic
- Explored and manually validated Wazuh Active Response
- Documented investigations, detection logic, troubleshooting, and supporting evidence

**SOC Skills:** SIEM · Wazuh · Detection Rules · Log Analysis · File Integrity Monitoring · Security Monitoring · Linux Security

---

## 🛡️ [Detection Engineering Lab](https://github.com/ananthancyber/detection-engineering-lab)

**Splunk Cloud · Sigma · SPL · Windows Security Logs · Splunk Universal Forwarder · MITRE ATT&CK**

Hands-on detection engineering lab focused on collecting Windows security telemetry, developing, validating, and investigating security detections from a SOC analyst perspective.

### Highlights
- Built a Windows-based detection engineering environment using Splunk Cloud and a Windows 10 endpoint
- Analyzed Windows Security Event IDs including 4624, 4625, 4672, 4688, 4698, 4732, and 4799
- Developed **8 primary detection scenarios** covering authentication, execution, persistence, privilege activity, and Windows discovery
- Created **11 Sigma detection rules/files** including event-based and correlation-based detection logic
- Developed **8 Splunk Processing Language (SPL) queries** for security event investigation and detection
- Validated detections using controlled security activity, baseline analysis, event correlation, and documented evidence
- Applied telemetry-driven detection engineering by selecting and refining detection scenarios based on verified log availability
- Mapped detection coverage to **6 MITRE ATT&CK techniques and sub-techniques**
- Performed SOC investigation workflow including alert triage, timeline reconstruction, process context, authentication context, and analyst disposition
- Organized **8 validation reports, MITRE ATT&CK coverage, screenshots, detection rules, SPL queries, and day-by-day technical documentation**

**SOC Skills:** Splunk Cloud · Windows Event Analysis · SIEM Log Ingestion · Detection Engineering · Sigma Rules · SPL Query Development · Authentication Monitoring · Process Monitoring · Persistence Detection · Privilege Activity Monitoring · Windows Discovery · MITRE ATT&CK · SOC Investigation

---
---

## ☁️ [Microsoft Cloud SOC, EDR & Threat Hunting Lab](https://github.com/ananthancyber/Project-05-Microsoft-Cloud-SOC)

**Microsoft Sentinel · Microsoft Defender for Endpoint · Microsoft Defender XDR · Entra ID · Log Analytics · KQL · Azure · MITRE ATT&CK**

Hands-on Microsoft cloud SOC lab focused on building and operating a practical security monitoring environment covering **SIEM, EDR, identity telemetry, detection engineering, threat hunting, incident investigation, and response**.

### Highlights

- Built a Microsoft cloud SOC environment using **Microsoft Sentinel and Azure Log Analytics**
- Configured a dedicated Azure resource group and centralized security workspace in **Central India**
- Activated and configured **Microsoft Sentinel** with its trial environment
- Onboarded a **Windows 10 endpoint to Microsoft Defender for Endpoint**
- Verified endpoint onboarding, device visibility, health, and security telemetry availability
- Integrated the **Microsoft Defender unified SecOps experience** for security monitoring and investigation
- Established the telemetry architecture from **endpoint → EDR → SIEM → SOC analyst**
- Reviewed and validated Microsoft Sentinel data connector configuration before enabling additional telemetry sources
- Designed the lab for **controlled detection engineering and threat-hunting validation**
- Planned KQL-based investigation workflows across **authentication, endpoint, correlation, and threat-hunting use cases**
- Documented infrastructure, telemetry flow, validation steps, evidence, and SOC architecture using reproducible technical documentation
- Applied **MITRE ATT&CK** as the framework for mapping future detections and investigations

**SOC Skills:** Microsoft Sentinel · Microsoft Defender for Endpoint · Defender XDR · Entra ID · Log Analytics · KQL · SIEM · EDR · Detection Engineering · Threat Hunting · Incident Investigation · Security Monitoring · MITRE ATT&CK · Cloud Security

---
## Technical Focus

| Area | Hands-on Experience |
|---|---|
| **SIEM & Monitoring** | Wazuh SIEM/XDR, security-event monitoring, alert investigation |
| **Detection Engineering** | Wazuh custom rules, correlation logic, behavioral detection, detection validation |
| **Windows & AD Security** | Active Directory, Windows Security Events, Sysmon, Kerberos, NTLM, authentication analysis |
| **Linux Security** | Ubuntu, Kali Linux, Linux logs, SSH authentication monitoring |
| **SOC Investigation** | Alert triage, log analysis, event correlation, baseline comparison, evidence-driven reporting |
| **Threat Frameworks** | MITRE ATT&CK mapping |
| **Security Automation** | Python, local RAG pipelines, AI-assisted alert triage |
| **Networking** | TCP/IP, DNS, packet analysis, network reconnaissance |
| **Infrastructure** | Docker, Docker Compose, VMware Workstation, Git |
| **Security Tools** | Wazuh, Sysmon, BloodHound, Nmap, Wireshark, Burp Suite |

---

## Certifications & Practical Learning

- **Microsoft — Cybersecurity Threat Vectors and Mitigation** — Coursera, July 2026
- **IBM — Introduction to Cybersecurity Essentials**
- **TryHackMe — Pre Security Learning Path**
- **Hack The Box** — hands-on enumeration and security labs
- **PortSwigger Web Security Academy** — web security labs

---

## Currently Developing

Deepening my knowledge in:

`SOC Operations` · `Detection Engineering` · `Windows Security` · `Active Directory Security` · `SIEM Investigation` · `Threat Detection` · `Security Automation`

---

## Career Focus

Seeking entry-level opportunities in:

**SOC Analysis · Cybersecurity Analysis · Blue Team Security · Security Operations · Junior Security Engineering**

My goal is to contribute to security teams where I can continue developing practical experience in **monitoring, detection, investigation, incident analysis, and defensive security engineering.**

---

## Connect

[LinkedIn](https://www.linkedin.com/in/ananthan-d-ab295321b) · [GitHub](https://github.com/ananthancyber) · [Email](mailto:ananthan.cyber@gmail.com)

---
