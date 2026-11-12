W2-PM5: ZENMAP-BASED NETWORK SCANNING

1. Overview

This exercise involved using Zenmap, the graphical interface for Nmap, to perform network discovery and scanning on my local network.

The objective was to identify active hosts, examine open ports, and identify services running on devices connected to the network.

2. Installation and Setup

I downloaded and installed Zenmap on my Windows system.

Before performing the scan, I used the Windows Command Prompt (CMD) to retrieve my system’s IP configuration and identify my local network setup.

I then launched Zenmap and initiated a scan of my local network.

3. Scanning Results

The scan covered 256 IP addresses and identified three active hosts.

Host 1

Host status: Up

Port	State	Service
22/tcp	Open	SSH
53/tcp	Open	DNS
80/tcp	Open	HTTP
443/tcp	Closed	HTTPS

Host 2

Host status: Up

Port	State	Service
49152/tcp	Open	Unknown

The service associated with this port was not identified by Nmap.

Host 3

Host status: Up

Port	State	Service
135/tcp	Open	MSRPC
139/tcp	Open	NetBIOS-SSN
445/tcp	Open	Microsoft-DS

These ports are commonly associated with Windows networking, Remote Procedure Call (RPC), and Server Message Block (SMB).

4. Summary of Findings

The scan produced the following results:

* Total IP addresses scanned: 256.
* Active hosts discovered: 3.
* One host exposed SSH, DNS and HTTP services.
* A second host exposed an unidentified service on TCP port 49152.
* A third host exposed Windows-related RPC and SMB services.

Internal IP addresses and MAC addresses have been omitted from this public documentation for privacy.

5. Learning Outcomes

Through this exercise, I gained practical experience in:

* Installing and configuring Zenmap on Windows.
* Retrieving IP configuration information using CMD.
* Performing network discovery.
* Identifying active hosts on a local network.
* Identifying open and closed TCP ports.
* Recognising common network services.
* Interpreting Nmap scan results.

6. Conclusion

This exercise demonstrated how Zenmap can be used to discover active devices and identify accessible network services.

It improved my understanding of network visibility, host discovery, port states and service identification, which are important components of network reconnaissance and security assessment.

7. Disclaimer

The scanning exercise was conducted on my own local network for educational purposes as part of the cybersecurity internship.
