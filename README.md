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

Hands-on detection engineering lab focused on collecting Windows security telemetry, developing detection logic, and validating security detections from a SOC analyst perspective.

**Highlights**
- Built a Windows-based detection engineering environment using Splunk Cloud and a Windows 10 endpoint
- Investigated Windows Security Event IDs including 4624, 4625, 4688, and 4698
- Analyzed authentication activity, failed logons, process creation, PowerShell execution, and scheduled task creation
- Developed Splunk Processing Language (SPL) queries for security event investigation and detection
- Created 4 Sigma detection rules covering credential access, execution, and persistence
- Validated detections using controlled security activity and documented detection outcomes
- Applied telemetry-driven detection engineering by selecting detection scenarios based on verified log availability
- Mapped detection coverage to 3 MITRE ATT&CK techniques and sub-techniques
- Organized detection rules, SPL queries, validation reports, MITRE ATT&CK mapping, and technical evidence
- Documented the complete detection engineering process through day-by-day technical reports

**SOC Skills:** Splunk Cloud · Windows Event Analysis · SIEM Log Ingestion · Detection Engineering · Sigma Rules · SPL Query Development · Authentication Monitoring · Process Monitoring · Persistence Detection · Threat Detection · MITRE ATT&CK · SOC Investigation

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
