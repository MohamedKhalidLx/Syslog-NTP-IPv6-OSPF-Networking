# Configure Cisco Routers for Syslog, NTP, and SSH Operations

## Overview
This lab involves configuring multiple Cisco routers with key functionalities like OSPF, IPv4 and IPv6 addressing, NTP, Syslog, and SSH for network management and security. The lab is structured to implement best practices in networking and security configuration.
![image](https://github.com/user-attachments/assets/9a413f77-77bd-4ac9-afad-485c3b4bf95e)


## Topology
The network topology includes multiple routers, switches, servers, and client devices with IPv4 and IPv6 addressing schemes. OSPF is used as the routing protocol, while Syslog and NTP ensure proper logging and time synchronization. SSH is used for secure remote access.
![Network Topology](test.pdf)

## Objectives
1. Configure IPv4 and IPv6 addressing on routers and end devices.
2. Set up OSPF for dynamic routing in both IPv4 and IPv6 networks.
3. Configure Syslog for remote logging of router events.
4. Implement NTP for time synchronization between network devices.
5. Enable SSH for secure management of the routers.

## Devices and Interfaces
- **Router 1 (R1)**: Interfaces S0/1/0 and G0/0/1
- **Router 2 (R2)**: Interfaces S0/1/0 and S0/1/1
- **Router 3 (R3)**: Interfaces S0/1/0 and G0/0/1
- **Servers**: NTP, Syslog
- **End Devices**: PCs connected via switches

## Configuration File
- **Configuration file**:Find all configurations in the [Configuration File](Configuration%20File.txt).

## Steps
1. Configure IP addresses and OSPF routing on the routers.
2. Set up NTP to synchronize the routers' clocks with the NTP server.
3. Configure Syslog to send logging information to the Syslog server.
4. Enable SSH for remote access management.
5. Test connectivity and verify configurations.

## Tools Used
- Cisco Packet Tracer.

## Contact
For any questions or feedback, please reach out to:
- **Name**: Mohamed Khaled Mahmoud Sayed
- **Email**: Mo7ammad244@gmail.com

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
