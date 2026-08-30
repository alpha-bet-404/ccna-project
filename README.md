<div align="center">
  <h1>🌐 Multi-Site Enterprise Network Security & Architecture Simulation</h1>
  <p><i>Designing & Hardening Enterprise Network Infrastructure via Cisco Packet Tracer.</i></p>

  <a href="https://mega.nz/embed/UJQDmJTa#bC_HQA4OccEbBRbavnJ0YXNAdIM3k_g6YwJoN0DxjMg" target="_blank">
    <img src="https://img.shields.io/badge/▶️_Watch_POC_Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch Demo"/>
  </a>
</div>

---

## 📋 Executive Summary
This project demonstrates the design, deployment, and validation of a multi-site enterprise network infrastructure built in **Cisco Packet Tracer**. Developed alongside Cybersecurity and Penetration Testing learning paths, the core objective is to simulate an enterprise topology connected via an ISP backbone, focusing on **Network Micro-Segmentation**, **Traffic Isolation**, and **Core Infrastructure Hardening**.

Understanding data flow, packet traversal, and routing architecture is foundational for both threat hunting (Blue Team) and exploiting infrastructure vulnerabilities (Red Team).

---

## 🔒 Key Architectural & Security Features

* **Network Micro-Segmentation (VLANs):** Logical traffic separation to reduce internal broadcast domains, enforce trust boundaries, and mitigate **Lateral Movement** risks.
* **Routed WAN & ISP Backbone Simulation:** Configured inter-site routing (Static & Dynamic Protocols) to simulate realistic multi-branch WAN connectivity and edge security gateways.
* **Core Infrastructure Services:**
  * **DHCP Deployment:** Automated dynamic IP allocation configured with scope parameters to streamline identity management.
  * **DNS Resolution Boundaries:** Centralized DNS implementation to resolve internal and external domain assets (`google.com`).
* **VoIP Telephony Integration:** Dedicated Voice VLAN deployment prioritizing Real-Time Transport Protocol (RTP) traffic and isolating voice streams from standard data vectors.
* **Traffic Inspection & Verification:** End-to-end ICMP tracking, path validation via `traceroute`, and packet-level inspection to verify access control limits.

---

## 🛠️ Technologies & Protocols

| Category | Components & Protocols |
| :--- | :--- |
| **Simulation Platform** | Cisco Packet Tracer |
| **Hardware Emulation** | Cisco Enterprise Routers & Catalyst Layer 2/3 Switches |
| **Switching & Security** | VLANs, 802.1Q Trunking, Inter-VLAN Routing (Router-on-a-Stick / SVI) |
| **Network Services** | DHCP, DNS, IP Telephony (VoIP) |
| **Routing Protocols** | Static Routing, Dynamic Routing (RIP/OSPF Fundamentals) |
| **Analysis Tools** | ICMP (`ping`), `traceroute`, Packet Inspection |

---

## 🎯 Learning Objectives & Security Takeaways

This simulation provided hands-on validation for core engineering and security concepts:

1. **Packet Traversal & Flow Analysis:** Deep dive into how packets are encapsulated, routed, and decapsulated across Layer 2 and Layer 3 boundaries.
2. **Attack Surface Reduction (ASR):** Analyzing how micro-segmentation limits the blast radius of potential network breaches and insider threats.
3. **Infrastructure Troubleshooting:** Diagnosing configuration flaws, routing loops, and service misconfigurations using CLI diagnostic utilities.
4. **Foundational Prep:** Aligning practical network architecture skills with CCNA and Cisco CyberOps/Security frameworks.

---

## 🧪 Project Outcome & Validation

* Successfully established cross-site communication across WAN links while maintaining departmental VLAN boundaries.
* Verified proper DNS resolution and dynamic IP addressing across endpoints.
* Executed functional VoIP call signaling and verified media stream routing between IP phones.

---
**Maintained by:** ALPHA-BET  
**Focus:** Offensive & Defensive Network Security Architecture  
**Date:** July 2026
