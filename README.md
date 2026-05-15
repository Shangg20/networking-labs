# networking-labs
A professional collection of Cisco Packet Tracer labs focused on enterprise-level network architecture, redundancy protocols, and scalable routing solutions. This repository documents my technical proficiency in designing, configuring, and troubleshooting complex network infrastructures.

## Introduction
"This repository serves as a technical portfolio of my networking expertise. It ranges from fundamental protocol implementations to a multi-site enterprise 'Capstone' project. Each lab includes full configuration files, topology diagrams, and technical documentation."

### Technical Skills Covered
#### Switching: VLANs, VTP, STP/RSTP, EtherChannel (LACP/PAgP), Inter-VLAN Routing (SVI & ROAS).

#### Routing: Static Routing, OSPF (Single & Multi-area), NAT/PAT, Default Routes.

#### Redundancy: HSRP (Gateway Redundancy), Port-Channeling.

#### Services: DHCP Server/Relay, ACLs (Standard/Extended), SSH/VTY Security.

### 3 Folder-Specific Descriptions
#### /01-InterVLAN-Routing
Objective: Demonstrates the segmentation of broadcast domains and the implementation of communication between isolated VLANs.

Key Highlights: Comparison between Legacy Router-on-a-Stick (ROAS) and modern Multilayer Switch (SVI) implementations.

#### /02-Redundancy-HSRP-STP
Objective: Focusing on High Availability (HA) and "Zero-Downtime" network design.

Key Highlights: Configuring HSRP for virtual gateway failover and optimizing Spanning Tree (STP) convergence to prevent loops while ensuring path redundancy.

#### /03-Major-Enterprise-Campus (The "Big One")
Objective: An end-to-end simulation of a multi-site enterprise network.

Key Highlights: This project integrates OSPF for dynamic routing across WAN links, HSRP for gateway resilience, EtherChannel for high-bandwidth trunking, and DHCP for automated IP management. It showcases a complete hierarchical design (Access, Distribution, and Core layers).
