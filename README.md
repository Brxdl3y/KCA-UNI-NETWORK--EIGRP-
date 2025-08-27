KCA University Enterprise Network Design

Project Overview

This project follows a pragmatic approach towards the simulation of a modern enterprise network designed for **KCA University**.
The goal was to build a secure, scalable, and resilient topology that connects multiple departments, ensures seamless communication, and enforces security at the routing level.

🔹 Built on Cisco Packet Tracer
🔹 Implements industry-grade routing & security best practices
🔹 Reflects real-world enterprise networking challenges


Topology Design

Departments & Core Components

Technology Dept. – Router R1 + PC1

Financial Dept. – PC2 via Multilayer Switch

Business Dept. – Router R4 + PC3

Education Dept. – Router R3

Administration Core – Router R2 (acts as backbone control)

Datacenter – Router R5 (central services)

ISP Provider – Cloud connection for internet access


⚙️ Key Technical Features

🔹 Routing & Redundancy

EIGRP (Enhanced Interior Gateway Routing Protocol)

Fast convergence and efficient path selection

Summarization applied for routing table optimization

Redundancy Links

Triangular core between R2, R4, and R5 for fault tolerance

Ensures alternative paths during link failures


🔹 Security Hardening

MD5 Authentication on every router and switch – protects against rogue routing updates

Passive Interfaces – LAN-facing ports silenced to minimize unnecessary traffic

Controlled ISP Edge – only R4 permitted to exchange traffic with external provider


🔹 Network Optimization

Subnetting (VLSM) – IP space efficiently divided per department

Hierarchical Design – Core, Distribution, Access layers clearly separated

Traffic Segmentation – Different subnets for each department improve security & manageability


🔹 Scalability & Future-Readiness

Design supports easy expansion (new departments, VLANs, or services)

Datacenter (R5) acts as hub for centralized services (DNS, storage, authentication)

Ready for migration to OSPF or BGP in larger deployments


Learning Outcomes & Competencies

From this project I demonstrated and strengthened:

Routing Protocols (EIGRP, future-proofing with OSPF/BGP)

Routing Security (MD5 authentication, passive interfaces)

Subnetting & IP Design (VLSM, departmental allocation)

Enterprise Design Principles (hierarchical layers, redundancy)

Network Simulation & Troubleshooting using Cisco CLI


Why This Project Matters

This isn’t just a Packet Tracer exercise — it’s a blueprint of how a real organization would design its network:
✔️ Secure (protected routing, minimized attack vectors)
✔️ Scalable (future-ready with structured subnetting & hierarchy)
✔️ Resilient (redundancy in the core, datacenter hub)
✔️ Efficient (optimized routing & reduced unnecessary traffic)


How to Use

Open the **.pkt** file in Cisco Packet Tracer

Start all devices and verify connectivity with ping and tracert

Review router configurations inside the **command.txt** folder