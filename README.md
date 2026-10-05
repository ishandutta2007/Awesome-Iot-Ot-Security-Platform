# Awesome-Iot-Ot-Security-Platform

# Top IoT/OT Security Platform Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Industrial Control Systems (ICS), Operational Technology Visibility, Asset Discovery, Threat Detection & Cyber-Physical Security*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **IoT/OT Security**. These solutions provide asset discovery, network visibility, threat detection, vulnerability management, and risk prioritization for operational technology, industrial control systems, IoT devices, and cyber-physical environments.

**Examples** include Microsoft Defender for IoT, Claroty, Nozomi Networks, Armis, Forescout Technologies, Tenable OT Security, SCADAfence, Cisco Cyber Vision, Dragos Platform, and Palo Alto IoT Security (the category leaders).

**Open-source emphasis**: Full-featured, passive OT asset discovery and ICS-native threat detection platforms are dominated by commercial vendors. Strong open-source building blocks exist—**Zeek**, **Suricata**, **Malcolm**, modern **GrassMarlin**/MarlinSpike successors, and ICS protocol parsers. This section expands those while remaining realistic about the commercial gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Microsoft Defender for IoT](https://www.microsoft.com/en-us/security/business/endpoint-security/microsoft-defender-iot)**  
  Microsoft’s agentless OT/IoT security solution providing asset discovery, vulnerability assessment, and threat detection integrated with Microsoft Defender XDR and Sentinel.

- **[Claroty](https://claroty.com/)**  
  Leading cyber-physical systems security platform covering OT, IoT, IoMT, and building management systems with deep visibility and risk management.

- **[Nozomi Networks](https://www.nozominetworks.com/)**  
  OT and IoT security platform specializing in industrial environments—strong asset visibility, anomaly detection, and scalable architecture for distributed sites.

- **[Armis](https://www.armis.com/)**  
  Agentless asset intelligence and security platform for IT, IoT, OT, and medical devices with extensive device fingerprinting and risk prioritization.

- **[Forescout Technologies](https://www.forescout.com/)**  
  Network visibility and access control platform that extends strongly into IoT and OT device discovery and policy enforcement.

- **[Tenable OT Security](https://www.tenable.com/products/tenable-ot)**  
  Tenable’s operational technology security offering focused on asset inventory, vulnerability management, and risk reduction in industrial environments.

- **[SCADAfence](https://www.scadafence.com/)**  
  OT and IoT security platform providing continuous monitoring, asset discovery, and threat detection for industrial networks.

- **[Cisco Cyber Vision](https://www.cisco.com/c/en/us/products/security/cyber-vision/index.html)**  
  Cisco’s OT security solution that provides visibility into industrial assets and integrates with the broader Cisco security portfolio.

- **[Dragos Platform](https://www.dragos.com/)**  
  Industrial cybersecurity platform with deep ICS threat intelligence, detection, and incident response capabilities for critical infrastructure.

- **[Palo Alto IoT Security](https://www.paloaltonetworks.com/network-security/iot-security)**  
  Palo Alto Networks solution for discovering, profiling, and securing IoT and OT devices within the broader Zero Trust and firewall ecosystem.

## Open-Source GitHub Projects
- **[Zeek](https://github.com/zeek/zeek)**  
  Powerful open-source network security monitoring framework widely used for passive visibility and behavioral analysis, including OT environments with protocol parsers.

- **[Suricata](https://github.com/OISF/suricata)**  
  High-performance open-source network IDS/IPS and network security monitoring engine frequently deployed for OT traffic inspection.

- **[Malcolm](https://github.com/idaholab/Malcolm)**  
  Open-source network traffic analysis tool suite built around Zeek and Suricata, designed to simplify deployment and visualization for OT/ICS monitoring.

- **[MarlinSpike / modern GrassMarlin successors](https://grassmarlin.com/)**  
  Maintained open-source evolution of the classic GrassMarlin concept—passive OT/ICS topology mapping and asset discovery from packet captures.

- **[OT/ICS protocol parsers for Zeek (ICSNPP and community packages)](https://github.com/DINA-community/ot-parsers)**  
  Collections of industrial protocol parsers (Modbus, S7, DNP3, IEC 61850, OPC UA, etc.) that extend Zeek for OT visibility.

- **[Wazuh](https://github.com/wazuh/wazuh)**  
  Open-source security monitoring platform that can be adapted for endpoint and log-based visibility in hybrid IT/OT environments.

- **[Snort](https://github.com/snort3/snort3)**  
  Classic open-source intrusion detection system still used in many industrial and research monitoring setups.

- **[Documentation and Zeek / Malcolm OT deployment guides](https://zeek.org/)**  
  Resources for safely deploying passive monitoring in industrial networks and interpreting ICS traffic.

- **[Passive asset discovery and PCAP analysis tools](https://github.com/)**  
  Community scripts and frameworks for extracting device inventories and communication patterns from OT network captures.

- **[Detection content for ICS protocols (Sigma, Suricata rules)](https://github.com/SigmaHQ/sigma)**  
  Open detection rules targeting industrial protocols and known OT attack techniques.

### Additional Strong Open-Source Options
- Building passive visibility stacks with **Zeek + Suricata + Malcolm**.
- Using modern **GrassMarlin**-style tools for offline topology and asset mapping from PCAPs.
- Extending Zeek with industrial protocol parsers for deeper OT understanding.
- Accepting that continuous, production-grade OT asset inventories, ICS-specific threat intelligence, automated risk scoring, and vendor-supported industrial protocol coverage still favor commercial platforms (Claroty, Nozomi, Dragos, Armis, Microsoft Defender for IoT, etc.).
- Focusing open-source efforts on visibility, detection engineering, and research rather than full replacement of commercial OT security platforms.

**Frameworks for building custom systems**: Deploy passive taps → run Zeek/Suricata with OT parsers → visualize and store with Malcolm or similar → feed alerts into open SIEM (Wazuh) → enrich with threat intel. Suitable for research, smaller sites, or supplementing commercial tools. Critical infrastructure and large industrial environments typically rely on commercial OT security platforms for support and depth.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- OT/ICS environments are safety- and availability-critical. Passive monitoring is strongly preferred; active scanning can disrupt operations. Open-source tools require careful deployment and expertise. This list is not operational or safety advice.

---
**Made for OT security teams, industrial defenders, and open security tooling advocates.**
Let's keep cyber-physical systems visible, protected, and as open as practical.
