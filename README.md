# NETWORKS-CYBERSECURITY-LAB
Virtual lab setup for ethical hacking and penetration testing as part of my Networks internship
## Evidence

### Virtual Machine Setup

![Virtual machine setup](screenshots/kalilab.png)
![Kali Linux Network Configuration](screenshots/kali-network-configuration.png)
[View all lab screenshots](screenshots/)
Lab Setup

Kali Linux Network Configuration

The Kali Linux virtual machine was configured and tested in Oracle VirtualBox.

* Network Interface: eth0
* Primary IPv4 Address: 10.0.0.2/24
* Secondary IPv4 Address: 10.0.0.4/24 (dynamically assigned)
* Default Gateway: 10.0.0.1
* Local Subnet: 10.0.0.0/24

Connectivity Verification

* IP Connectivity Test: Passed (ping -c 4 8.8.8.8 — 4 packets received, 0% packet loss).
* DNS Resolution Test: Passed (ping -c 4 google.com — 4 packets received, 0% packet loss).
* Routing Verification: Confirmed the default gateway and local subnet route using ip route.
