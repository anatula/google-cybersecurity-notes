# 1/9 Foundations of Cybersecurity course

## 1. Welcome to the exciting world of cybersecurity module

This certificate program:

- is composed of 9 courses.
- Each course  is broken into modules.
- Must complete all the courses.
- Pass all graded assignments in all 9 courses of the certificate program. Each graded assignment is part of a cumulative graded score for the course, and the passing grade for each course is 80%. 

Threat actor = any person or group who presents a securiy risk

Cybersecurity: practise of ensuring 
- C = confidentiality (requiring complex password)
- I = Integrity
- A = Availability
 of information by protecting:
- networks
- devices
- people
- data 
from:
- unauthorized access
- criminal exploitation

Benefits of security:

- protects against *internal* (current or former employees, external vendors or trusted partners, often accidental clicking a compromised link) and *external* threats (someone outside of the org. trying to gain access to network or devices, intentionally abusing systems) -> help org mitigate or reduce the impact of threats like this.

- ensure org meets regulatory complience or laws or guidelines that require the implementation of specific security standards -> avoid fines, audits and upholding ethical obligation to protect users.

- mantains and improve bussiness productivity: by establishing a plan for business continuity, security teams allow to do their jobs even in case of data breach

- being security conscious can reduce expenses associated with risk, such as recovering from data loss, operational downtime and fines

- mantaining brand trust: if services or customer data can lower trust, hurt the brand, less revenue 

A *playbook* is a list of how to go through a certain detection and what the analyst needs to look at in order to investigate those incidents.

*SIEM* Security Information and Events Management tools, identify and analyze security threats, risks and vulnerabilities. A SIEM tool might alert you that an unknown user has access the system. SIEM tools collect and analyze **log data, or records of events** such as unusual login behavior, and support analysts’ ability to monitor critical activities in an organization.

*IDS* Intusion detection systems to **monitor system activity and alerts** for possible intrusions. You might use an IDS to monitor networks for signs of malicious activity, like unauthorized access to a network.

IDS = inspects live network traffic for attack patterns (signatures). Alerts on suspicious packets. IDS signature != than PKI cryptographic proof of identity/integrity, it's an attack pattern (e.g., "/etc/passwd" in a URL). Example [Snort](https://www.snort.org/), [Suricata](https://suricata.io/)

Snort is a "network packet sniffer" that inspects network traffic and carefully examines each packet to find any suspicious irregularities or potentially harmful payloads. Furthermore, Snort is used not only as a packet sniffer similar to tcpdump, but it is also used as a packet logger that is useful for network traffic debugging and as a network intrusion detection and prevention system.

![](https://www.zenarmor.com/docs/what-is-snort-architecture.png)

SIEM = collects & correlates logs from many sources (servers, apps, IDS) for long-term security analysis. Splunk, Sentinel, [Wazuh](https://wazuh.com/) (open source)

![](https://www.splunk.com/content/dam/splunk-blogs/images/media_1359d700a02acc7f7bf6ead71876e4af4c7ed076f.svg)

IDS detects attacks at the network layer (packets)
SIEM ingests IDS alerts + server logs + firewall logs → correlates them
APM gives performance data — useful to both DevOps (latency) and Security (attack impact)
Observability tools (Prometheus, ELK) become SIEMs only after adding security rules & threat intel

Open Source Combinations
- Snort (IDS) + Wazuh (SIEM) — industry standard
- Suricata (IDS) + ELK Stack — modern, scalable
- Full observability + security stack: Prometheus (metrics) + Loki (logs) + Grafana (UI) + Snort (IDS)

## 2. The evolution of cybersecurity module
## 3. Protect agains threats, risks and vulnerabilities module
## 4. Cybersecurity tools and programming languages module