# Insurance-Network-Infrastructure

# Overview
This project showcases a secure and scalable network infrastructure designed for an insurance company. The network is structured to facilitate seamless communication between various departments while ensuring data security, efficient traffic management, and network redundancy.

# Features
1. VLAN Segmentation: Department-wise VLANs to ensure secure and isolated communication.
2. Routing & Switching: Implemented multi-layer switching and dynamic/static routing.
3. Security Measures: Firewall rules, access control lists (ACLs), and encryption to safeguard sensitive data.
4. Redundancy & Failover: Multiple routers and switches to ensure high availability.
5. Wireless Access Points: Secure guest and employee Wi-Fi networks with authentication.
6. Server Integration: DHCP, Email, and HTTP servers for efficient resource management.
   
# Network Topology
The network includes:
1. First Floor: Customer Service (VLAN 10), Guest VLAN (VLAN 70)
2. Second Floor: Claims Processing (VLAN 20), Policy Management (VLAN 30)
3. Third Floor: Underwriting (VLAN 40), Reinsurance Broker (VLAN 50)
4. Fourth Floor: IT Department (VLAN 60), Core Servers (DHCP, Email, HTTP)
   
# Technologies Used
1. Cisco Packet Tracer for simulation
2. Routers & Layer 3 Switches for dynamic routing
3. VLANs & Access Points for segmentation and secure wireless access
4. Servers (DHCP, Email, HTTP) for network services
