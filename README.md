# Enterprise Network Troubleshooting – Multi-Router Topology

## 📌 Project Overview
This project focuses on troubleshooting and restoring connectivity in a **multi-router enterprise network topology** consisting of multiple access-layer LANs interconnected through a **redundant routed WAN core**.

The objective was to ensure that **all internal networks can reach each other**, as indicated in the topology requirements.

---

## 🌐 Network Topology Description
- Multiple access networks using private IP addressing (192.168.x.0/24)
- Access switches connected to edge routers serving end devices
- Core network formed by multiple routers interconnected using routed WAN subnets (64.50.x.0/24)
- Redundant routing paths to ensure alternate connectivity in case of link failure

---

## 🔍 Troubleshooting Objectives
- Ensure all LANs can communicate with each other end-to-end
- Identify and resolve routing failures between edge and core routers
- Verify correct gateway and subnet configuration for end devices
- Restore redundancy and alternate path connectivity

---

## 🧩 Issues Identified & Resolved
- Corrected **routing table misconfigurations** preventing reachability between LAN segments.
- Fixed **static routing issues** across core and edge routers.
- Verified WAN subnet addressing consistency between interconnected routers.
- Resolved incorrect **default gateway settings** on access networks.
- Ensured all routers had complete routes to all 192.168.x.0/24 networks.
- Validated successful ICMP connectivity between all end devices across different sites.

---

## 🛠 Tools Used
- Cisco Packet Tracer
- ICMP (ping) for connectivity testing
- Router CLI for routing verification and correction

---

## 🎯 Skills Demonstrated
- Layer 3 routing troubleshooting
- Static routing verification and correction
- Multi-router path analysis
- Enterprise network fault isolation
- End-to-end connectivity validation

---

## 📂 Project Files
- `Final Task - troubleshooting.pkt` — Cisco Packet Tracer topology and configurations

---

## 📎 Notes
This project simulates a real-world enterprise troubleshooting scenario where routing failures and misconfigurations must be identified and resolved to restore full network connectivity.
