# Scalable-Enterprise-Network-Infrastructure-Design

<img width="1607" height="785" alt="Screenshot 2026-03-30 005059" src="https://github.com/user-attachments/assets/416d580f-aeb9-4f5b-b593-c4d314b4eef6" />

Enterprise Network Infrastructure Design - Cisco Packet Tracer
📌 Project Overview
This project demonstrates a scalable, hierarchical network architecture designed for a Small-to-Medium Enterprise (SME). The topology is built using Cisco Packet Tracer and focuses on implementing core networking principles such as Layer 2/3 switching, VLAN segmentation, and inter-device connectivity.

🏗️ Topology Architecture
The design follows a structured approach to ensure redundancy and efficient traffic management:

Core/Distribution Layer: Utilizes a 3560-24PS Multi-layer Switch to handle Inter-VLAN routing and core traffic.

Access Layer: Consists of 2960 Series Switches connecting various end-user departments.

Routing: Integrated Cisco 2901 Routers for gateway connectivity and external network simulation.

End-Devices: Includes a mix of PCs, Laptops, Printers, and a dedicated Server-PT for centralized services.

🛠️ Technical Implementation
VLAN Segmentation: Logically separated departments to reduce broadcast domains and enhance security.

Inter-VLAN Routing: Configured SVI (Switch Virtual Interfaces) on the Layer 3 switch.

IP Addressing: Systematic IPv4 addressing scheme (Static/DHCP).

Interface Management: Optimized port configurations using interface range and switchport security basics.
