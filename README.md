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
 *Reference 1 created multiple VLANS for Guest, IoT, Cameras, Lab, etc. Also changed Unifi Allow All approach to Block All to better align with Zero Trust. <img width="1302" height="324" alt="Screenshot 2026-10-08 131356" src="https://github.com/user-attachments/assets/95d7b0d0-b0c6-4990-af12-96ee1577d7c2" />
 *Reference 2 Created 3 different SSID's for main trusted network, guest, and Iot. <img width="1341" height="216" alt="Screenshot 2026-10-08 132302" src="https://github.com/user-attachments/assets/a54ae8d2-2f70-4105-b64f-5489dd4c090e" />
 *Reference 3 Created firewall rules to Block All Internal Traffic for all protocols. <img width="1910" height="913" alt="Screenshot 2026-10-08 132615" src="https://github.com/user-attachments/assets/12e26ed6-cd8a-4794-b928-668ebf7fd893" />
 






