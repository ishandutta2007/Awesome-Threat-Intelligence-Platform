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

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Recorded Future](https://www.recordedfuture.com/)** | Cloud-based Threat Intelligence Cloud delivering real-time adversary analysis, SecOps intelligence, vulnerability prioritization, and dark web tracking. | Starts at ~$25,000/year (entry-level module); enterprise packages range $100,000–$250,000+/year | **No permanent free tier**; offers a 30-day free trial for SIEM integrations & free Express browser extension for basic lookups |
| **[Anomali (ThreatStream)](https://www.anomali.com/)** | High-volume IOC lifecycle management, multi-source feed ingestion, machine learning scoring, and bi-directional SIEM/SOAR orchestration. | Starts at ~$15,000–$25,000/year for base feeds/seats; enterprise deployments average ~$93,000–$150,000/year | **No permanent free tier**; 14-to-30-day guided POC trial upon sales qualification with capped indicator ingestion |
| **[Mandiant Threat Intelligence](https://www.mandiant.com/)** | Frontline breach intelligence, adversary attribution, vulnerability intelligence, and strategic reporting powered by Google Cloud / Mandiant responders. | Starts at ~$40,000/year (Mandiant Advantage standard tier); enterprise suites scale higher based on seats | **Free Forever Tier** with limited access to curated actor summaries & public IOCs; 14-day trial for full premium intelligence (30-day trial for ASM) |
| **[CrowdStrike Falcon Intelligence](https://www.crowdstrike.com/)** | Threat intelligence unified with Falcon endpoint telemetry, automated sandbox malware detonation, IOC enrichment, and adversary profiles. | Starts at $99.99/device/year (Falcon Pro bundle, 5-device min. = $499.95/year); standalone intel modules start at ~$47/device/year | **No permanent free tier**; 15-day full-featured free trial (no credit card required, up to 100 endpoints) including integrated intel & automated sandbox detonations |
| **[SOCRadar](https://socradar.io/)** | Extended Threat Intelligence (XTI) combining external attack surface management (EASM), digital risk protection (DRP), and dark web monitoring. | Starts at $7,900/year (~$658/month for Essential tier; Business tier starts at $14,750/year) | **Free Forever Community Edition** with monthly search quota for Threat Investigation & 1 domain monitoring (up to 50 assets); 7-to-14-day free trial for Business tier |
| **[Intel 471](https://intel471.com/)** | Adversary-centric intelligence tracking cybercriminal underground networks, ransomware syndicates, infostealer logs, and actor infrastructure. | Starts at ~$44,200/year (£44,200/license/yr on UK Digital Marketplace; enterprise tiers average $60,000–$120,000/year) | **No permanent core free tier** (free SpiderFoot HX tier with 50 monthly scans); 30-day targeted trial / workshop access for threat hunting teams |
| **[Flashpoint](https://flashpoint.io/)** | Deep & dark web intelligence, illicit marketplace monitoring, compromised credentials, vulnerability intelligence, and physical security data. | Starts at ~$35,000–$50,000/year for single modules; Ignite Cyber Threat Intel packages on AWS Marketplace list at $80,000–$100,000/year (up to 5,000 users) | **No permanent free tier**; 14-to-30-day Proof-of-Concept (POC) trial available upon sales verification with limited query credits |
| **[ThreatConnect](https://threatconnect.com/)** | TIP and cyber risk orchestration platform uniting indicator aggregation, analyst investigations, playbook automation, and Cyber Risk Quantification (CRQ). | Starts at ~$25,000–$40,000/year for base CTI analyst tier; full TC Complete enterprise packages average $80,000–$150,000+/year | **No permanent free tier**; 30-day guided evaluation / POC environment available upon sales engagement with capped user seats |
| **[Cyware](https://www.cyware.com/)** | Collaborative threat exchange (CTIX) and security orchestration platform enabling bi-directional STIX/TAXII threat sharing and automated SecOps enrichment. | Starts at ~$30,000–$45,000/year for base CTIX platform; enterprise packages with orchestration (CSAP/CSOP) range $75,000–$120,000+/year | **No permanent free tier**; 14-to-30-day guided sandbox / POC trial provided upon sales qualification |
| **[EclecticIQ](https://www.eclecticiq.com/)** | STIX 2.x native intelligence platform featuring analyst workbench, graph-based data fusion, feed normalization, and dissemination into SIEM/EDR. | Starts at ~$35,000–$50,000/year for entry-level deployment; full enterprise instances average $75,000–$140,000/year | **No permanent platform free tier** (free Threat Scout browser extension for observable extraction); 30-day integration test / TIP Bundle trial upon request |
| **[ThreatQuotient (ThreatQ)](https://www.threatq.com/)** | Threat operations platform and data engine that scores, prioritizes, deduplicates, and operationalizes threat intelligence across SOC workflows. | Starts at ~$30,000–$45,000/year for baseline cloud instance with core integrations; enterprise tiers average $65,000–$110,000+/year without per-feed surcharges | **No permanent free tier**; 14-to-30-day guided Proof of Concept (POC) trial through vendor and partner channels |



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
