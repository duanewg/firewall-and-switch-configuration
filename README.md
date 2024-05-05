<p align="center">
<img src="https://place-hold.it/600x200" alt="Place Holder Image"/>
<!-- <img src="assets/logo.svg" alt="Logo Text There" /> -->
</p>

# Project Title
"[Project Name]" involves [briefly describe the main objective or purpose of the project] utilizing [mention any specific tools, technologies, or platforms]. This project aims to [mention the primary goal or outcome] to [highlight the intended impact or benefit].

## Environments and Technologies Used

- Netgear M4100-24G-POE+ Managed Switches 
- FortiGate-60E Firewall

## Operating Systems Used

- macOS High Sierra

## High-Level Deployment and Configuration Steps

- Initial Hardware Setup:
Unbox the FortiGate 60E and connect it to power.
Connect your computer to one of the LAN ports on the FortiGate using an Ethernet cable.
Connect to the FortiGate's web-based management interface using a web browser.
- Initial Configuration:
Access the FortiGate's web-based management interface by navigating to its default IP address (usually https://192.168.1.99).
Log in using the default username and password (usually "admin" for both).
Follow the initial setup wizard to configure basic settings such as timezone, admin password, and network interfaces.
- Network Configuration:
Configure WAN and LAN interfaces with appropriate IP addresses, subnet masks, and gateway settings.
Define DHCP server settings for the LAN network if needed.
Set up static routes if your network requires routing to other subnets or the internet.
- Security Policies:
Create firewall policies to control traffic flow between different network segments.
Define NAT policies if you need to translate private IP addresses to public IP addresses for outgoing traffic.
- VPN Configuration:
Set up VPN tunnels if you need to establish secure connections with remote networks or users.
Configure IPsec or SSL VPN settings based on your requirements.
- Security Profiles:
Enable security features such as antivirus, web filtering, and intrusion prevention systems (IPS).
Configure security profiles and apply them to firewall policies to inspect and filter traffic for threats.
- Logging and Monitoring:
Configure logging settings to capture firewall events and traffic logs for analysis.
Set up SNMP monitoring if you need to monitor the FortiGate's status and performance.
- Testing and Verification:
Test the firewall configuration by sending traffic through different firewall policies and VPN tunnels.
Verify that security profiles are correctly inspecting and blocking malicious traffic.
Ensure that logging and monitoring are capturing relevant data for analysis.
Documentation and Maintenance:
Document the firewall configuration settings for future reference.
Regularly update firmware and security definitions to keep the firewall protected against emerging threats.
<h2>Architecture Diagram</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
