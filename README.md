# Zero-Trust-Network

## Objective

The goal of this project is to build a secure home network using Ubiquiti UniFi equipment while applying Zero Trust security principles commonly used in enterprise environments.

This project focuses on moving away from a traditional flat network by implementing VLAN segmentation, firewall rules, device isolation, and network monitoring. Each network will have its own purpose, with access between networks restricted to only what is necessary.

Throughout this project, I'll be documenting the network design, configurations, security policies, testing, and challenges I encounter along the way.

The overall objective is to gain hands-on experience with network security, firewall management, and Zero Trust architecture while building a more secure and manageable home network.

### Skills Learned

- Network Segmentation: Configuring VLANs and separating trusted devices, IoT devices, guest networks, and management infrastructure.

- Firewall Configuration: Creating and managing firewall rules to control traffic between VLANs and restrict unauthorized access.

- Zero Trust Architecture: Applying least-privilege access, default-deny policies, and network isolation principles.

- Network Security: Hardening network infrastructure, reducing attack surfaces, and limiting lateral movement.

- TCP/IP Networking: Working with IP addressing, subnetting, DHCP, DNS, and routing.

- Wireless Security: Configuring secure SSIDs, WPA2/WPA3 authentication, and wireless network isolation.

- DNS Security: Implementing DNS filtering with AdGuard Home to block malicious domains, advertisements, and unwanted traffic.

- Security Monitoring: Using UniFi logs and network traffic analysis to identify suspicious activity and troubleshoot connectivity issues.

- Troubleshooting & Validation: Testing firewall policies, verifying VLAN isolation, and diagnosing network connectivity problems.

- Technical Documentation: Creating network diagrams, documenting configurations, and maintaining project documentation through GitHub.

### Tools Used

- Ubiquiti UniFi Dream Machine Pro SE
- Ubiquiti UniFi U7 Pro Access Points
- UniFi Network Application
- Wazuh SIEM
- UniFi IDS/IPS
- Nmap
- Wireshark

## Steps
 *Reference 1 created multiple VLANS for Guest, IoT, Cameras, Lab. <img width="1320" height="286" alt="Screenshot 2026-10-08 130537" src="https://github.com/user-attachments/assets/82b1b70d-74bf-4a5c-a903-d7bae1f31271" />




