Network Cybersecurity Lab

Project Overview

This project documents the setup and initial network verification of a Kali Linux virtual machine running in Oracle VirtualBox. The lab provides a foundation for learning networking concepts and practising ethical hacking and penetration testing in an authorised environment.

The initial verification covered network interface configuration, IPv4 addressing, routing, IP connectivity, and DNS resolution.
# NETWORKS-CYBERSECURITY-LAB
Virtual lab setup for ethical hacking and penetration testing as part of my Networks internship
## Evidence

### Virtual Machine Setup

![Virtual machine setup](screenshots/kalilab.png)
![Kali Linux Network Configuration](screenshots/kali-network-configuration.png)
[View all lab screenshots](screenshots/)
Lab Setup

Kali Linux Network Configuration and Connectivity Tests

The screenshot documents the Kali Linux virtual machine’s primary and secondary IPv4 addresses, along with successful connectivity tests to 8.8.8.8 and google.com. Both tests completed with four packets received and zero packet loss.

Testing and Verification

The Kali Linux virtual machine’s network configuration and connectivity were verified using terminal commands.

Test	Command	Result
IP address verification	ip -4 addr show eth0	Primary and secondary IPv4 addresses identified
IP connectivity	ping -c 4 8.8.8.8	Passed — 4 packets received, 0% packet loss
DNS resolution	ping -c 4 google.com	Passed — 4 packets received, 0% packet loss
Routing verification	ip route	Default gateway and local subnet route identified

Supporting visual evidence is available in the screenshots folder.
