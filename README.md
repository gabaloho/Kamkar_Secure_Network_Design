# Kamkar_Secure_Network_Design
This project involves designing a secure and scalable network for a client moving to a new office. The network is built using Cisco Packet Tracer and adheres to best practices for network security, segmentation, and manageability.
Network Description: The network is designed to support the operations of all company departments and provides access to corporate resources, as well as secure connectivity to external resources via the Internet.
Key Functions:
Ensuring data transmission between departments (Management, Study, Production, Support).
Organizing access to servers and services (e.g., DNS, DHCP, iSCSI).
Ensuring network security through the use of VLANs, ACLs, and network segmentation (DMZ).
Managing and monitoring the network to maintain its uninterrupted operation.
Documentation Date: October 24, 2024
Responsible Persons: Mattieu Gedeon, Gabriel Aloho, Kseniia Tanekem.
2. Network Topology

Network Structure Description:
The network is built on a star topology using Cisco switches and routers.
The network core is the switch SW0, which is connected to the ISR4331 router for inter-VLAN routing and Internet access.
The network integrates several VLANs, providing segmentation by department (Management, Study, Production, Support, DMZ).
Servers are located in the DMZ for enhanced security.
Connection Type: Internal departments are connected through wired Ethernet connections. Core devices are connected via GigabitEthernet trunk ports.
3. Network Coverage Area

Physical Location: The network covers several company departments, each operating in a separate VLAN.
VLAN 10: Management Department.
VLAN 20: Study Department.
VLAN 30: Production Department.
VLAN 40 and VLAN 50: Support Department.
VLAN 60: Demilitarized Zone (DMZ) for servers.
4. Network Tasks and Goals

Main Network Tasks:
Maintaining high performance and stability of the network infrastructure.
Ensuring secure access to corporate and external resources.
Preventing unauthorized access through network segmentation (VLANs and DMZ).
Ensuring backup of critical data and equipment configurations.
Strategic Goals:
Network scalability for future expansion (adding new departments or users).
Continuous improvement of security through hardware updates and the introduction of new technologies (e.g., implementing VPN for remote access).
Ensuring high availability through the use of fault-tolerant equipment and backup links.
5. Description of Equipment Used

Cisco ISR4331 Router:
1 Router: Router 1
Cisco 2960-24TT Switches:
6 switches: SW1, SW2, SW3, SW4, SW4.1, SW4.2
Cisco 3650-24PS Switches:
2 switches: SW0, SW1.1.
Servers: 1 server: DNS/DHCP server, Application server, file server
Workstations:
43 PC
