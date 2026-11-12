# WEEK 2 – DETAILED CYBERSECURITY PROJECT REPORT

*Participant:* Areprekumor Deborah Ebikomboere  
*Programme:* Networkwalks Cybersecurity Internship  
*Week:* 2  
*Reporting Date:* 12 November 2026  

---

## 1. Executive Summary
This report presents the practical cybersecurity activities completed during Week 2 of the Networkwalks Cybersecurity Internship. The project covered four selected modules: Kali Linux Footprinting (W2-PM1), Maltego Footprinting (W2-PM3), theHarvester Footprinting (W2-PM4), and Zenmap Network Scanning (W2-PM5).

The exercises involved using six Kali Linux tools to examine the assigned domain, networkwalks.com; using Maltego to visualise relationships between digital entities; using theHarvester to gather publicly available information associated with microsoft.com; and using Zenmap to identify active hosts, open ports, and services on a local network.

The Zenmap scan covered 256 IP addresses and identified three active hosts. The theHarvester exercises demonstrated differences in results across search sources, while the Maltego exercise provided a visual representation of relationships between an organisation, domain, person, website entities, and an email address.

The project strengthened practical understanding of reconnaissance, information gathering, network discovery, service identification, and cybersecurity documentation. It also reinforced the importance of responsible testing and accurate interpretation of technical findings.


## 2. Introduction and Objectives

### 2.1 Introduction

This report documents the practical cybersecurity activities completed during Week 2 of the Networkwalks Cybersecurity Internship. The exercises focused on information gathering, footprinting, and network scanning using selected cybersecurity tools in a controlled learning environment.

The report presents the tools used, the procedures followed, observations from the exercises, and the knowledge gained.

### 2.2 Objectives

The objectives of the Week 2 activities were to:

- Understand the fundamentals of footprinting and information gathering.
- Use Kali Linux tools to collect publicly available information about a target domain.
- Explore relationships between digital entities using Maltego.
- Use theHarvester to identify publicly available information associated with a domain.
- Perform network discovery and port scanning using Zenmap.
- Document findings and understand their relevance to cybersecurity assessments.

## 3. Tools and Methodology

### 3.1 Tools Used

The following tools were used during the Week 2 practical exercises:

| Tool | Purpose |
|---|---|
| WHOIS | Retrieves domain registration information. |
| WhatWeb | Identifies technologies used by websites. |
| NSLookup | Queries DNS records and resolves domain names. |
| DNSRecon | Performs DNS enumeration. |
| cURL | Retrieves information from web servers and HTTP response headers. |
| WAFW00F | Detects and identifies Web Application Firewalls (WAFs). |
| Maltego | Visualises relationships between domains, organisations, people, and other digital entities. |
| theHarvester | Gathers publicly available information such as email addresses, IP addresses, and hostnames. |
| Zenmap | Provides a graphical interface for Nmap-based network discovery and port scanning. |

### 3.2 Methodology

The exercises were carried out using a practical, tool-based approach:

1. Kali Linux was used to execute the footprinting commands against the assigned domain, networkwalks.com.
2. Maltego was used to create a visual graph of related digital entities.
3. theHarvester was used to gather publicly available information from selected search sources.
4. Zenmap was used to discover active hosts and identify open ports and associated services on my local network.
5. Screenshots and command outputs were collected as evidence of the practical activities.

All activities were conducted for educational purposes within the scope of the internship tasks.

 |

#### Observations and Results

The six selected Kali Linux footprinting tools were executed against networkwalks.com. Screenshots of the tool outputs were captured and included in the PM1 module documentation. The tools provided practical exposure to domain registration lookup, web technology identification, DNS enumeration, and HTTP header inspection.

#### Learning Outcome

This exercise provided practical experience using multiple Kali Linux tools for domain footprinting, DNS enumeration, web technology identification, and HTTP header inspection.

### 4.2 W2-PM3: Maltego Footprinting

#### Learning Outcome

The Maltego graph displayed relationships involving New Networkwalks Academy, networkwalks.com, Waqas Karim CCIE, related website entities, and the email address info@networkwalks.com. The graph provided a visual representation of how the selected digital entities were connected.

#### Practical Implementation

Maltego was used to create a visual graph of digital entities associated with the assigned organisation and domain.

#### Learning Outcome

The exercise demonstrated how Maltego can be used to visualise relationships between digital entities and organise information gathered during footprinting.

### 4.3 W2-PM4: theHarvester Footprinting

#### Commands Executed

```bash
theHarvester -d microsoft.com -l 1000 -b baidu
theHarvester -d microsoft.com -l 50 -b all

## 6. Risk Analysis and Recommendations

### 6.1 Risk Analysis

The practical exercises revealed information that may be relevant to an organisation's security posture.

- *Information Exposure:* Publicly available domain information and discovered digital relationships can help an organisation understand its external information footprint.
- *Network Exposure:* Open ports and running services identified during the Zenmap scan indicate network services that should be understood and appropriately secured.
- *Service Identification:* Identifying services such as SSH, DNS, HTTP, MSRPC, NetBIOS, and Microsoft-DS helps establish visibility into the services operating on a network.

These observations do not independently confirm that the identified systems are vulnerable. Further authorised assessment would be required to determine actual security weaknesses and their impact.

### 6.2 Recommendations

Based on the exercises, the following general security recommendations are proposed:

1. Regularly review publicly available domain and organisational information to identify unnecessary information exposure.
2. Maintain an inventory of internet-facing assets, domains, and associated services.
3. Ensure that network services and open ports are limited to those required for legitimate operations.
4. Apply appropriate access controls and authentication mechanisms to exposed services.
5. Keep operating systems, applications, and network services updated with relevant security patches.
6. Conduct periodic authorised network assessments to identify and address potential security weaknesses.
7. Maintain proper documentation of assessment activities, observations, and supporting evidence.

## 7. Challenges Encountered

During the practical exercises, a few challenges were encountered:

1. *Tool Familiarisation:* Understanding the functionality and command syntax of different Kali Linux footprinting tools required additional research and practice.
2. *Information Availability:* TheHarvester returned different results depending on the selected data source. The Baidu search produced no discovered records, while the all-sources search returned additional information.
3. *Visualisation and Entity Relationships:* Working with Maltego required understanding how entities and their relationships are represented in a visual graph.
4. *Network Scanning Interpretation:* Interpreting Zenmap results required distinguishing between active hosts, open ports, closed ports, filtered ports, and identified services.
5. *Documentation:* Organising practical outputs and screenshots into a structured GitHub repository required learning and applying Markdown formatting.

These challenges provided opportunities to develop technical problem-solving, research, analytical, and documentation skills.

## 8. Lessons Learned

The Week 2 project strengthened my understanding of practical information gathering and network reconnaissance.

Key lessons learned include:

1. Different footprinting tools provide different types of information and can complement one another during reconnaissance.
2. Publicly available information can reveal relationships between domains, organisations, people, and digital assets.
3. Search sources influence the volume and type of information returned by theHarvester.
4. Network scanning helps identify active hosts, open ports, and services within a network.
5. Open ports are not automatically vulnerabilities; their security implications depend on the services, configurations, and access controls involved.
6. Accurate documentation and supporting screenshots are important for presenting and reviewing cybersecurity assessment results.
7. Responsible and authorised testing is essential when conducting cybersecurity activities.

The exercises also improved my confidence in using cybersecurity tools, interpreting technical outputs, and documenting practical findings.
## 9.

Conclusion

The Week 2 Cybersecurity Project provided practical experience in footprinting, information gathering, digital relationship mapping, and network scanning.

Through the use of Kali Linux tools, Maltego, theHarvester, and Zenmap, I explored different approaches to collecting publicly available information, identifying digital entities, discovering active network hosts, and examining exposed services.

The exercises reinforced the importance of understanding reconnaissance techniques, interpreting results accurately, documenting evidence, and maintaining responsible testing practices.

Overall, the project contributed to my technical development and provided a stronger foundation for further learning in network security and penetration testing.

## 10. Evidence and References

### 10.1 Practical Evidence

Screenshots and supporting evidence from the completed exercises are organised within their respective module folders in the Week 2 project repository.

| Module | Evidence |
|---|---|
| W2-PM1 – Kali Linux Footprinting | Screenshots of WHOIS, WhatWeb, NSLookup, DNSRecon, cURL, and WAFW00F outputs. |
| W2-PM3 – Maltego Footprinting | Screenshot of the Maltego entity relationship graph. |
| W2-PM4 – theHarvester Footprinting | Screenshots of the Baidu and all-sources search results. |
| W2-PM5 – Zenmap Network Scanning | Screenshot of the network scan results, with private network identifiers excluded from public documentation. |

### 10.2 References

- Networkwalks Cybersecurity Internship – Week 2 Project Guidelines.
- [Nmap Documentation](https://nmap.org/book/man.html).
- [Maltego Documentation](https://docs.maltego.com/).
- [theHarvester GitHub Repository](https://github.com/laramies/theHarvester).
- [Kali Linux Documentation](https://www.kali.org/docs/).
- [Sample Penetration Testing Report](https://github.com/waqaskarimccie/Pentesting-Report-Sample).


## Disclaimer

This report was prepared solely for educational and training purposes as part of the Networkwalks Cybersecurity Internship.

The activities documented were conducted within the scope of the assigned exercises. Footprinting activities were performed against the specified training target, while network scanning was limited to the participant's local network.

The findings represent observations made during the practical exercises and should not be interpreted as a comprehensive security audit or confirmation of all possible vulnerabilities.

No unauthorised access, exploitation, or damage to systems was intended.

