Hotel Management Network Design (Cisco Packet Tracer)

A simulated network infrastructure designed for a multi-floor hotel, built and tested in Cisco Packet Tracer. The project focuses on segmenting traffic between guests, staff, and critical services while ensuring scalability and security.

Problem Statement

Hotels need reliable, secure, and scalable networks to support guest connectivity, staff operations, and administrative systems — without compromising data security or guest privacy. This project designs a network that:

Separates guest and staff/administrative traffic
Supports high-speed connectivity across guest rooms, conference rooms, and public areas
Enforces access control between network segments
Scales for future expansion (additional rooms, facilities, emerging technologies)
Network Design

The topology spans three floors and includes routers, switches, wireless access points, and end devices (PCs, laptops, smartphones, tablets), with the following key implementations:

VLAN Segmentation — separates staff, guest, and security traffic into isolated broadcast domains
OSPF (Open Shortest Path First) — dynamic routing protocol used between routers for efficient, scalable data flow
DHCP — automatic IP address assignment across all connected devices per floor
Access Control Lists (ACLs) — enforce security policies and restrict traffic between segments
Implementation Steps
Built the topology using routers, switches, and access points across three floors
Assigned devices (PCs, laptops, smartphones, tablets) to their respective floor/segment
Configured DHCP on routers/access points for automatic IP assignment
Verified DHCP-assigned IPs via command prompt on end devices
Connected wireless devices (laptops, smartphones, tablets) to their respective access points
Validated inter-device connectivity and traffic segmentation across the topology
Tools & Technologies
Cisco Packet Tracer
VLAN
OSPF
ACL
DHCP
Files
HotelManagement.pkt — Packet Tracer project file (open with Cisco Packet Tracer to view/edit the live topology)
Hotel_Network_Design_Report.docx — Full project report: problem statement, design methodology, configuration steps, and results
Future Scope
Integration of AI-based hotel management systems and 5G connectivity
Energy-efficient networking equipment for sustainability
Centralized network management for multi-property hotel chains

------

Shivani Jella

--
