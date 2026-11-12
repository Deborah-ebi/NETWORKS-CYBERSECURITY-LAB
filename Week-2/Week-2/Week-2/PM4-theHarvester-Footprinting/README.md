## Evidence

### 1. Baidu Source Search

![theHarvester Baidu Results](theHarvester%20Search%20result%20for%20Networkwalks.png)

### 2. All Sources Search

![theHarvester All Sources Results](theHarvester%20-b%20all%20Sanitised.png)

W2-PM4: THEHARVESTER-BASED FOOTPRINTING

1. Overview

This exercise involved using theHarvester, an OSINT tool available in Kali Linux, to gather publicly available information associated with a target domain.

The practical focused on identifying information such as email addresses, hostnames, IP addresses and other domain-related information using different data sources.

2. Tools and Commands Used

Command 1: Baidu Source

theHarvester -d microsoft.com -l 1000 -b baidu

Explanation:

* -d microsoft.com: Specifies the target domain.
* -l 1000: Sets the search limit to 1,000.
* -b baidu: Specifies Baidu as the data source.

Observed Results:

The search returned no results for:

* IP addresses
* People
* Email addresses
* Hostnames

Command 2: All Available Sources

theHarvester -d microsoft.com -l 50 -b all

Explanation:

* -d (target): Specifies the target domain.
* -l 50: Sets the search limit to 50.
* -b all: Requests information from all supported sources available to the tool.

Observed Results:

The second command returned considerably more information, including IP addresses and other domain-related information.

3. Comparison of Results

The two commands produced different outcomes.

The Baidu source returned no matching information, while the all-sources search returned multiple results, including IP addresses.

This demonstrated how the selection and availability of data sources can influence the results of an OSINT investigation.

4. Learning Outcomes

Through this exercise, I gained practical experience in:

* Using theHarvester for domain reconnaissance.
* Selecting different data sources.
* Understanding search limits and their effect on information gathering.
* Identifying publicly available IP address and hostname information.
* Comparing results obtained from different OSINT sources.
* Understanding the importance of multiple sources during footprinting.

5. Conclusion

The exercise demonstrated the usefulness of theHarvester in gathering publicly available information about a target domain. Comparing the two searches highlighted the importance of selecting appropriate data sources when conducting footprinting and reconnaissance.

6. Evidence

Screenshots of both theHarvester commands and their terminal outputs were captured during the practical exercise.

7. Disclaimer

This exercise was conducted for educational purposes as part of the assigned cybersecurity internship activity. Information gathering was performed within the scope of the exercise and applicable authorisation.
