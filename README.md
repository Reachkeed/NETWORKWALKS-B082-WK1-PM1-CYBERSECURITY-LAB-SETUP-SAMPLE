# NETWORKWALKS-B082-WK1-PM1-CYBERSECURITY-LAB-SETUP-SAMPLE
CYBERSECURITY LAB SETUP
🔐 Cybersecurity & Penetration Testing Lab Setup

"Kali Linux" (https://img.shields.io/badge/OS-Kali%20Linux-blue?logo=kalilinux)
"VirtualBox" (https://img.shields.io/badge/Virtualization-Oracle%20VirtualBox-blue?logo=virtualbox)
"Networkwalks" (https://img.shields.io/badge/Training-Networkwalks-orange)
"Status" (https://img.shields.io/badge/Project-Week%201-success)

📌 Project Overview

This project is part of my Cybersecurity Training Program with Networkwalks (Batch B082).

The objective was to build a virtual cybersecurity and penetration testing laboratory using Oracle VirtualBox and Kali Linux.

The lab provides an isolated virtual environment for learning cybersecurity concepts, practising networking configurations, and performing authorised security testing.

🎯 Project Objectives

- Install and configure Oracle VirtualBox.
- Import and configure Kali Linux.
- Create and configure a private NAT Network.
- Understand virtual machine networking.
- Enable hardware virtualization technology.
- Configure and inspect network interfaces.
- Prepare a virtual environment for future cybersecurity practicals.

🛠️ Tools and Technologies Used

Tool| Purpose
Oracle VirtualBox| Virtual machine management
Kali Linux 2026.3| Cybersecurity operating system
Windows| Host operating system
NAT Network| Virtual network configuration
Terminal| Network configuration and testing

⚙️ Lab Configuration

The following configurations were used during the setup:

Virtual Machine

- Operating System: Kali Linux 2026.3
- Architecture: 64-bit
- Base Memory: 2048 MB (2 GB)
- Processors: 2
- Virtual Hard Disk: Approximately 80 GB

Network Configuration

- Network Adapter: Adapter 1
- Attached To: NAT Network
- Network Name: NatNetwork
- IPv4 Network Prefix: 10.0.0.0/24
- DHCP: Enabled
- Virtual Cable Connected: Enabled

BIOS Configuration

- Intel VT-x: Enabled
- Intel VT-d: Enabled

🚀 Implementation Steps

Step 1: Installing Oracle VirtualBox

Installed Oracle VirtualBox on the Windows host machine to create and manage virtual machines.

Step 2: Importing Kali Linux

Downloaded and imported the Kali Linux VirtualBox image and configured its virtual machine resources.

Step 3: Configuring the NAT Network

Created a NAT Network named "NatNetwork" with the IPv4 prefix "10.0.0.0/24" and enabled DHCP.

Step 4: Configuring the Network Adapter

Configured Adapter 1 of the Kali Linux virtual machine to use the created NAT Network and enabled the virtual cable connection.

Step 5: Enabling Virtualization Technology

Accessed the HP BIOS settings and confirmed that Intel VT-x and VT-d were enabled.

Step 6: Booting Kali Linux

Successfully started the Kali Linux virtual machine and accessed the Kali Linux desktop environment.

Step 7: Inspecting Network Interfaces

Opened the Kali Linux terminal and used NetworkManager commands to inspect available network connections.

🧪 Network Testing

The following commands are intended for verifying network configuration and connectivity:

ip a

Displays network interfaces and IP addresses.

ip route

Displays the routing table.

nmcli device status

Displays network device status.

ping -c 4 1.1.1.1

Tests connectivity to an external IP address.

ping -c 4 google.com

Tests DNS resolution and connectivity.

Verification status: Network adapter configuration and interface detection were completed. External connectivity and DNS resolution still need to be confirmed.

📸 Project Screenshots

Screenshots documenting the practical implementation will be organised in the "screenshots" folder.

They will cover:

1. VirtualBox Manager.
2. NAT Network configuration.
3. Kali Linux network adapter settings.
4. BIOS virtualization settings.
5. Kali Linux desktop environment.
6. Network interface inspection.
7. Successful connectivity and DNS tests.

🎥 Project Demonstration

A short video demonstration of the completed lab environment will be added here.

Video: Coming soon.

📚 Key Learning Outcomes

Through this project, I gained practical exposure to:

- Virtualization and virtual machine management.
- Kali Linux installation and configuration.
- NAT and NAT Network concepts.
- DHCP and IP addressing.
- Network adapter configuration.
- BIOS virtualization technology.
- Basic Linux terminal commands.
- Network troubleshooting.

⚠️ Challenges and Troubleshooting

During the setup, I encountered a virtual machine startup error related to hardware virtualization.

I accessed the HP BIOS configuration and confirmed that Intel VT-x was enabled, allowing Kali Linux to boot successfully.

I also encountered a network disconnection notification, which I identified as an area requiring further troubleshooting and verification.

🔮 Future Improvements

- Complete internet connectivity and DNS verification.
- Create a clean virtual machine snapshot.
- Practise Linux networking commands.
- Set up additional virtual machines for controlled lab exercises.
- Explore basic penetration testing tools.
- Document future cybersecurity practicals.

🙏 Acknowledgement

Special appreciation to Sir Waqas Karim (CCIE) and the entire Networkwalks team for their guidance, mentorship, and support throughout this learning journey.

👨‍💻 Author

Reachkeed

Cybersecurity Student | Aspiring Cybersecurity Professional

GitHub: "@Reachkeed" (https://github.com/Reachkeed)

---

This project was completed as part of the Networkwalks Cybersecurity Training Program – Batch B082, Week 1.

Disclaimer: This lab is intended strictly for educational purposes and authorised cybersecurity testing.
