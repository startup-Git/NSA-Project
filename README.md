# Campus Network using Cisco Packet Tracer

## Introduction
This project demonstrates a **Campus Network** design using **Cisco Packet Tracer**. The network consists of multiple VLANs, routers, switches, and wireless access points to simulate a real-world campus environment.

## Features
- **VLAN Segmentation** for different departments (e.g., Admin, Faculty, Students, Guests)
- **Inter-VLAN Routing** using Layer 3 Switch or Router-on-a-stick
- **DHCP Server** for automatic IP allocation
- **Wireless Access Points (WAP)** for Wi-Fi-enabled areas
- **Firewall and ACLs** for security management
- **Static & Dynamic Routing** for efficient network communication

## Network Topology
- **Core Layer**: Main router(s) connecting all campus buildings
- **Distribution Layer**: Layer 3 switches managing VLANs
- **Access Layer**: Switches & APs for end devices (PCs, Laptops, Printers, etc.)
- **Servers**: DHCP, DNS, Web, File servers

## Requirements
- **Cisco Packet Tracer** (Latest version recommended)
- Basic knowledge of networking (IP addressing, VLANs, Routing, ACLs)

## Setup Instructions
1. Open **Cisco Packet Tracer**.
2. Load the provided `.pkt` file (Campus Network topology).
3. Configure VLANs and Inter-VLAN Routing.
4. Setup DHCP and other network services.
5. Test connectivity using `ping` and `tracert` commands.

## Troubleshooting
- **No Connectivity?** Ensure VLANs are correctly assigned.
- **DHCP Issues?** Verify the DHCP server configuration.
- **Routing Problems?** Check routing tables and gateway settings.

## Future Enhancements
- Implement **Spanning Tree Protocol (STP)** for loop prevention.
- Add **Network Security Policies** (Firewall, IPS, IDS).
- Introduce **IPv6 support** for future scalability.

## Author
Developed by: **[Your Name]**

## License
This project is licensed under the MIT License.

