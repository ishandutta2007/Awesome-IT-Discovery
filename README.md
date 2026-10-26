# Awesome-IT-Discovery

## Top IT Discovery Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Automated Asset Discovery, CMDB Population & Network Inventory*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **IT Discovery**. These tools enable IT teams to automatically scan, identify, and classify every component in their infrastructure—servers, network devices, cloud resources, applications, and endpoints—creating an accurate, continuously updated inventory that powers CMDB, asset management, security, and operations workflows.



**Examples** include ServiceNow Discovery, Lansweeper, Device42, Virima, BMC Helix Discovery, ManageEngine AssetExplorer, Qualys Cloud Platform, SolarWinds Network Discovery, UVexplorer, and Microsoft Defender for Endpoint (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted network scanning, software inventory, and cloud resource discovery—ideal for organizations building sovereign IT discovery infrastructure without per-node or per-asset licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Discovery](https://www.servicenow.com/)**  

  Continuous discovery application that scans, identifies, and classifies physical and logical infrastructure components to populate and maintain the CMDB; supports agentless (SSH, SNMP, WMI) and agent-based discovery, application fingerprinting via supervised ML, Application Dependency Mapping (ADM), and cloud discovery for AWS, Azure, GCP, IBM Cloud, Oracle Cloud, VMware, and Kubernetes .



- **[Lansweeper](https://www.lansweeper.com/)**  

  IT asset discovery platform covering IT, IoT, OT, and cloud assets; provides network discovery across IP ranges, AD targets, and Windows computers, cloud discovery for AWS, Azure, GCP, and Microsoft 365, agent-based discovery via IT Agent, and AI usage tracking .



- **[Device42](https://www.device42.com/)**  

  Agentless discovery and dependency mapping platform providing visibility into hybrid IT estates; v4.0.0 adds patch cable management, room layouts with heat maps for data center visualization, switch templates and port visualization, extended historical logging, and enhanced IP address management .



- **[Virima](https://virima.com/)**  

  ITAM/ITSM platform with intelligent asset discovery, CMDB automation, and dynamic service mapping; v6.1 expands discovery to Cisco, Juniper, standalone ESXi, Oracle databases, Nutanix, NetApp, HP MSA, and additional AWS/Azure services; adds MFA, mTLS, and SNMP v3 security enhancements .



- **[BMC Helix Discovery](https://www.bmc.com/)**  

  Agentless discovery platform built as an appliance for on-premises or SaaS deployment; uses Outposts for scanning isolated network segments, with all communication initiated from Outpost to the central appliance over HTTPS for security .



- **[ManageEngine AssetExplorer](https://www.manageengine.com/products/asset-explorer/)**  

  ITAM platform with cloud version offering multiple discovery methods, inventory management, usage tracking, procurement, and reporting; features visual workflow builder for lifecycle automation, CMDB sync rules for relationship mapping, and compliance management for license and contract tracking .



- **[Qualys Cloud Platform](https://www.qualys.com/)**  

  Security and compliance platform with unified asset inventory across on-premises, hybrid, and cloud environments; provides inside-out and outside-in visibility with business context, identifies EOL/EOS software and unmanaged assets, and quantifies cyber risk with TruRisk scoring .



- **[SolarWinds Network Discovery](https://www.solarwinds.com/)**  

  Network discovery and monitoring within the Orion Platform; supports SNMP polling for device statistics, topology data collection, and credential-based discovery for network devices, with configurable polling intervals and dynamic IP address handling .



- **[UVexplorer](https://www.paessler.com/)**  

  Network mapping and discovery tool (now part of Paessler PRTG) providing automated Layer 2 and Layer 3 topology maps from scheduled discoveries; adds dependency context, configuration backups, and change tracking between discovery runs .



- **[Microsoft Defender for Endpoint](https://www.microsoft.com/en-us/security/business/microsoft-defender-endpoint)**  

  Endpoint security platform with device and network discovery capabilities that find unmanaged endpoints and network devices to close visibility gaps; integrates discovery with vulnerability management, EDR, and automated investigation/response .



## Open-Source GitHub Projects



- **[LanLens](https://github.com/AlexRosbach/LanLens)**  

  Self-hosted network inventory and local network scanner with a clean web UI for documentation, security awareness, and CMDB/i-doit export workflows; discovers MAC/IP devices with vendor hints and online/offline state, builds device inventory with names, owners, locations, and services, supports DHCP/ARP/MAC/LLDP/CDP/STP/OSPF/SNMP awareness signals, and provides optional network topology maps with pan/zoom and CMDB export; Docker-deployable with no cloud dependency .



- **[takestock](https://pypi.org/project/takestock/)**  

  Offline-capable IT discovery and measurement tool that produces graded rows, coverage gaps, and a CBOM (CycloneDX bill of materials); supports passive collectors (DNS, certificate logs), active collectors (with explicit authorization), and ingest of existing exports; generates CMDB registers, IP address plans, and compliance conformance notes from observations .



- **[YALTF (Yet Another License Tool and Framework)](https://pkg.go.dev/github.com/yaltf/yaltf)**  

  Software license discovery tool developed by the International Committee of the Red Cross (ICRC); connects to remote systems via SSH to collect installed packages and their licenses across CentOS, Fedora, RHEL, Rocky, and OpenSUSE; outputs structured JSON with parallel scanning support .



- **[awsmap](https://pypi.org/project/awsmap/)**  

  AWS resource inventory and mapping tool with HTML, JSON, and CSV output; supports parallel scanning across 40+ AWS services including EC2, S3, RDS, Lambda, EKS, VPC, IAM, and more; features tag-based filtering, region selection, and interactive HTML reports with search and dark mode .



- **[seccart2 Network Discovery (sc2.scng.discovery)](https://pypi.org/project/seccart2/)**  

  Python-based network discovery module with SNMP connectivity testing, single device discovery, and recursive network crawling; supports configurable depth, domain suffix resolution, exclusion patterns, concurrency control, and JSON event output for automation integration .



### Additional Strong Open-Source Options



- **Nmap** — The foundational open-source network scanner; provides host discovery, port scanning, service/version detection, and OS fingerprinting; widely used as a discovery engine within larger IT management pipelines.

- **OpenVAS/Greenbone** — Open-source vulnerability scanner with asset discovery capabilities; identifies hosts and services during vulnerability assessments, feeding inventory data into security workflows.

- **Ansible Facts** — Built-in fact gathering for Linux/Windows hosts via Ansible; collects hardware, network, OS, and software information without additional agents, suitable for organizations already using Ansible for configuration management.



**Frameworks for building custom systems**: Combine **LanLens** for local network inventory with CMDB export, **takestock** for offline-capable discovery with compliance evidence generation, **awsmap** for cloud resource inventory, and **YALTF** for software license discovery across Linux fleets in a self-hosted IT discovery stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- IT discovery platforms handling infrastructure and asset data must comply with applicable security policies and regulations; active scanning requires explicit authorization on target networks.

- Self-hosted open-source solutions vary in scope—LanLens and awsmap cover specific domains (local network, AWS), while full enterprise discovery across hybrid environments typically requires commercial platforms.

- Verify license terms for commercial use; LanLens is open-source (check repository), takestock is a PyPI package, YALTF uses GPL-3.0, and awsmap is open-source .



---



**Made for IT asset managers, network administrators, CMDB administrators, and security operations teams.**  

Let's make IT discovery more open, accurate, and continuously visible.
