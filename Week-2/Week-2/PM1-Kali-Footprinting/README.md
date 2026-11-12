## Overview

This exercise involved using six Kali Linux tools to perform footprinting and information gathering against the Networkwalks website (networkwalks.com).

The objective was to understand how different tools can collect publicly available information about a domain, examine its DNS configuration, identify web technologies, inspect HTTP response headers, and detect possible Web Application Firewall (WAF) protection.

## Tools Used

1. WHOIS

## Evidence

![WHOIS footprinting result](whois%20networkwalks%201.png)

Purpose:

WHOIS retrieves publicly available domain registration information, which may include registrar details, registration dates, expiry dates, and name servers.

2. WhatWeb

### WhatWeb Evidence

![WhatWeb Results](whatweb%20networkwalks.png)

Purpose:

WhatWeb identifies technologies used by a website, such as content management systems, web servers, frameworks, and other technology indicators.

3. NSLookup

### NSLookup Evidence

![NSLookup Results](nslookup%20result.png)

Purpose:

NSLookup queries the Domain Name System (DNS) to obtain information such as the IP address associated with a domain.

4. DNSRecon

   ### DNSRecon Evidence

![DNSRecon Results](dns%20-d%20result.png)

Purpose:

DNSRecon performs DNS reconnaissance to identify DNS records and gather information about a domain’s DNS infrastructure.

5. cURL

### cURL Evidence

![cURL Results](curl%20-I%20result.png)

Purpose:

cURL sends an HTTP request and retrieves the response headers without downloading the full webpage content. These headers can reveal information about server responses and HTTP security configurations.

6. WAFW00F

*Evidence:*

![WAFW00F Scan Results](waf00f%20result%20firewalk%20for%20networkwalks.png)

Purpose:

WAFW00F is used to identify whether a website is protected by a Web Application Firewall (WAF) and, where detectable, identify the firewall product.

3. Learning Outcomes

Through this exercise, I gained practical experience in:

* Retrieving domain registration information.
* Identifying website technologies.
* Querying DNS records.
* Performing DNS reconnaissance.
* Inspecting HTTP response headers.
* Detecting Web Application Firewall protection.
* Understanding how different footprinting tools contribute to the information-gathering phase of security assessments.

4. Conclusion

This exercise provided practical exposure to multiple footprinting tools available in Kali Linux. It demonstrated how publicly accessible information can be collected and examined to develop an initial understanding of a website’s digital infrastructure.

5. Disclaimer

This documentation is for educational purposes. Activities were conducted within the scope of the assigned internship exercise and applicable authorization.
