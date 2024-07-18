
# Campus Network for University

## Overview
This project involves planning, designing, and prototyping the network topology for University's network using Cisco Packet Tracer. The network spans two campuses, including various buildings with specific networking requirements.

## Requirements

### Network Topology
- **Main Campus**:
  - **Building A**: Administrative staff in the departments of management, HR, and finance. PCs are distributed in the building offices, expected to share some networking equipment. The Faculty of Business is also situated in this building.
  - **Building B**: Faculty of Engineering and Computing, and Faculty of Art and Design.
  - **Building C**: Students' labs and IT department. The IT department hosts the University Web server and other servers, including an email server hosted externally on the cloud.
- **Smaller Campus**:
  - Faculty of Health and Sciences (staff and students' labs situated on separate floors).

### Configuration Requirements
- **Core Devices and End Devices**:
  - Provide end-to-end connectivity and access to the internal servers and the external server.
  - Each department/faculty is expected to be on its own separate IP network.
  - Switches should be configured with appropriate VLANs and security settings.
  - **RIPv2** will be used to provide routing for the routers in the internal network and static routing for the external server.
  - Devices in Building A will acquire dynamic IP addresses from a router-based DHCP server.


## Getting Started
To explore this project, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/Cisco-Packet-Tracer-Project.git
    ```
2. **Open the .pkt File**:
    - Open Cisco Packet Tracer.
    - Open the `MINI PROJECT CISCO.pkt` file located in the cloned repository.





