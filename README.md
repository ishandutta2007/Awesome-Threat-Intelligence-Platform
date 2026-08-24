# Awesome-Threat-Intelligence-Platform

## Top Threat Intelligence Platforms (TIP) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cyber Threat Intelligence Management, IOC/TTP Structuring, Sharing, Enrichment, Knowledge Graphs & Analyst Workflows*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Threat Intelligence Platforms (TIPs)**. These systems collect, structure, store, enrich, correlate, and share cyber threat intelligence — from indicators of compromise (IOCs) to adversary TTPs, campaigns, and strategic context — so security teams can operationalize intelligence across detection, hunting, and response.



**Examples** include Recorded Future, Anomali, Mandiant Threat Intelligence / Mandiant Advantage, CrowdStrike Falcon Intelligence, SOCRadar, Intel 471, Flashpoint, ThreatConnect, Cyware, EclecticIQ, ThreatQuotient, and OpenCTI (the category leaders and major open platform).



**Open-source emphasis**: The open-source TIP ecosystem is mature and widely adopted. **OpenCTI** and **MISP** are the two dominant platforms, complemented by supporting tools for observables, sharing, and enrichment. This section is heavily expanded with these and related projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Recorded Future](https://www.recordedfuture.com/)**  

  Leading intelligence cloud that continuously collects and analyzes open, dark-web, and technical sources to deliver risk scores, curated intelligence, and actionable insights.



- **[Anomali (ThreatStream)](https://www.anomali.com/)**  

  Enterprise TIP focused on high-volume IOC management, automated feed ingestion, confidence scoring, and integration with SIEM/EDR/SOAR.



- **[Mandiant Threat Intelligence / Mandiant Advantage](https://www.mandiant.com/)**  

  Frontline intelligence and platform capabilities from Mandiant (Google Cloud), strong on adversary tracking, incident context, and strategic/tactical reporting.



- **[CrowdStrike Falcon Intelligence](https://www.crowdstrike.com/)**  

  Threat intelligence integrated with the Falcon platform, providing adversary insights, IOC enrichment, and automated scoring tied to endpoint telemetry.



- **[SOCRadar](https://socradar.io/)**  

  Extended threat intelligence platform covering digital risk protection, dark-web monitoring, and operational intelligence for organizations of various sizes.



- **[Intel 471](https://intel471.com/)**  

  Adversary-centric intelligence focused on cybercrime actors, infrastructure, and underground ecosystems.



- **[Flashpoint](https://flashpoint.io/)**  

  Threat intelligence and risk data covering cyber, physical, and fraud threats drawn from deep and dark-web sources.



- **[ThreatConnect](https://threatconnect.com/)**  

  TIP with strong analyst workflow, intelligence lifecycle management, and native playbook/automation capabilities.



- **[Cyware](https://www.cyware.com/)**  

  Threat intelligence and security orchestration platform emphasizing sharing, collaboration, and automated operationalization of intelligence.



- **[EclecticIQ](https://www.eclecticiq.com/)**  

  Intelligence-driven security platform and TIP focused on structured intelligence management and analyst productivity.



- **[ThreatQuotient (ThreatQ)](https://www.threatq.com/)**  

  Threat intelligence platform centered on prioritization, scoring, and integrating intelligence into security operations workflows.



## Open-Source GitHub Projects

- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  

  Leading open-source Cyber Threat Intelligence platform built on STIX 2.1. Structures, stores, visualizes, and connects technical and non-technical threat knowledge with a rich connector ecosystem and GraphQL API. Community Edition is fully open; Enterprise Edition adds advanced features.



- **[MISP](https://github.com/MISP/MISP)**  

  The most widely deployed open-source threat intelligence and sharing platform. Excellent for collecting, storing, correlating, and distributing indicators and threat events with strong community sharing communities and galaxy/taxonomy support.



- **[OpenCTI Connectors](https://github.com/OpenCTI-Platform/connectors)**  

  Official and community connectors that import/export intelligence between OpenCTI and dozens of sources (MISP, MITRE ATT&CK, VirusTotal, AlienVault OTX, commercial feeds, SIEMs, etc.).



- **[Yeti](https://github.com/)**  

  Open-source observables and indicators management platform designed for fast IOC triage, enrichment, and analyst-friendly workflows.



- **[TheHive + Cortex](https://github.com/TheHive-Project)**  

  Open-source security incident response platform frequently paired with TIPs for case management and observable enrichment.



- **[MITRE ATT&CK datasets and STIX exports](https://github.com/mitre/cti)**  

  Foundational open knowledge base of adversary tactics, techniques, and procedures that most TIPs ingest.



- **[STIX/TAXII open implementations and libraries](https://github.com/)**  

  Reference libraries and tools for producing, consuming, and transporting structured threat intelligence.



- **[Abuse.ch, CIRCL, and public feed tooling](https://github.com/)**  

  Open tooling and pipelines for ingesting high-quality public threat feeds into MISP, OpenCTI, or custom platforms.



- **[Threat intelligence sharing and community instances](https://github.com/)**  

  Projects and documentation supporting trusted MISP or OpenCTI sharing communities (ISACs, national CERTs, etc.).



- **[Custom enrichment and scoring engines](https://github.com/)**  

  Open scripts and services that score, deduplicate, or contextualize indicators before or after they enter a TIP.



### Additional Strong Open-Source Options

- TAXII servers and clients for standardized intelligence exchange.

- Jupyter / notebook environments for exploratory analysis of TIP data.

- Graph databases and visualization tools used alongside OpenCTI’s knowledge graph.

- Detection-as-code repositories that consume structured intelligence from TIPs.

- Integration examples connecting OpenCTI/MISP to Elastic, Wazuh, Splunk, or TheHive.



**Frameworks for building custom systems**: Deploy **OpenCTI** as the central knowledge graph and analyst workbench (STIX-native), use **MISP** for high-volume indicator sharing and community exchange, and connect both via official connectors. Enrich with public and commercial feeds, push relevant indicators to SIEMs/EDRs, and manage investigations in TheHive. This combination provides a complete, self-hosted TIP capability with full data ownership, strong standards compliance, and a vibrant community — at the cost of operational effort for maintenance, connector management, and content curation.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Threat intelligence platforms handle sensitive security data and influence detection and response decisions. Open-source TIPs offer excellent transparency and control but require proper access controls, data-quality processes, and integration work. Intelligence is only as useful as the processes and people that operationalize it.

- Always respect sharing agreements, TLP markings, and legal constraints when exchanging threat intelligence.



---

**Made for threat intelligence analysts, SOC teams, and detection engineers building intelligence-driven security programs.**

Let's make structured, actionable threat intelligence more open, shareable, and operational.
