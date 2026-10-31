Multi-Branch Enterprise Network Using VLANs and OSPF

Project Overview

Designed and implemented a multi-branch enterprise network using Cisco Packet Tracer, connecting three office branches: Chennai, Coimbatore, and Bangalore.

The network uses VLANs to separate departments and OSPF dynamic routing to enable communication between branches.

Technologies Used
Cisco Packet Tracer
VLAN (Virtual LAN)
Inter-VLAN Routing
Router-on-a-Stick
OSPF Dynamic Routing
OSPF Area 0
IPv4 Addressing

Network Topology
The enterprise network consists of three branches:
1. Chennai – R1
2. Coimbatore – R2
3. Bangalore – R3

Each branch contains:
One Router
One Layer 2 Switch
Three PCs
Three Department VLANs

VLAN Configuration
VLAN ID   | Department
VLAN 10   | IT
VLAN 20   | HR
VLAN 30   | SALES

IP Addressing Scheme

Branch    | IT              | HR              | SALES
Chennai   | 192.168.10.0/24 | 192.168.20.0/24 | 192.168.30.0/24
Coimbatore| 192.168.110.0/24| 192.168.120.0/24| 192.168.130.0/24
Bangalore | 192.168.210.0/24| 192.168.220.0/24| 192.168.230.0/24

Routing Configuration
Configured Router-on-a-Stick for inter-VLAN communication.
Configured OSPF Process ID 1.
Used OSPF Area 0 across all three routers.
Established OSPF neighbor relationships.
Advertised department networks and router-to-router networks.

Network Testing
The following tests were performed:
Verified VLAN configuration.
Verified trunk ports.
Checked OSPF neighbor relationships.
Verified routing tables.
Tested communication between different branches.
Tested communication between different VLANs.
Simulated router link failure and recovery.

Key Learning Outcomes
Understanding VLAN segmentation.
Configuring trunk ports.
Implementing inter-VLAN routing.
Configuring OSPF dynamic routing.
Troubleshooting network connectivity.
Understanding OSPF neighbor relationships and route propagation.

