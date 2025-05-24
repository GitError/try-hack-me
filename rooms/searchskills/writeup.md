## Theory

## Specialized Search Engines

### Shodan

[Shodan](https://www.shodan.io/) is a search engine for **devices connected to the Internet**. It allows you to search for specific types and versions of servers, networking equipment, industrial control systems, and IoT devices. You may want to see how many servers are still running Apache 2.4.1 and the distribution across countries. To find the answer, we can search for apache 2.4.1, which will return the list of servers with the string “apache 2.4.1” in their headers.

### Censys

At first glance, [Censys](https://search.censys.io/) appears similar to Shodan. However, Shodan focuses on Internet-connected devices and systems, such as servers, routers, webcams, and IoT devices. Censys, on the other hand, focuses on **Internet-connected hosts, websites, certificates, and other Internet assets**. Some of its use cases include enumerating domains in use, auditing open ports and services, and discovering rogue assets within a network. You might want to check Censys Search Use Cases.

### VirusTotal

[VirusTotal](https://www.virustotal.com/gui/) is an online website that provides a virus-scanning service for files using multiple antivirus engines. It allows users to upload files or provide URLs to scan them against numerous antivirus engines and website scanners in a single operation. They can even input file hashes to check the results of previously uploaded files. 

### Have I Been Pwned

[Have I Been Pwned (HIBP)](https://haveibeenpwned.com/) does one thing; it tells you if an email address has appeared in a leaked data breach. Finding one’s email within leaked data indicates leaked private information and, more importantly, passwords. Many users use the same password across multiple platforms, if one platform is breached, their password on other platforms is also exposed. Indeed, passwords are usually stored in encrypted format; however, many passwords are not that complex and can be recovered using a variety of attacks.

## CVE

We can think of the **Common Vulnerabilities and Exposures (CVE)** program as a dictionary of vulnerabilities. It provides a standardized identifier for vulnerabilities and security issues in software and hardware products. Each vulnerability is assigned a CVE ID with a standardized format like CVE-2024-29988. This unique identifier (CVE ID) ensures that everyone from security researchers to vendors and IT professionals is referring to the same vulnerability, [CVE-2024-29988](https://nvd.nist.gov/vuln/detail/CVE-2024-29988) in this case.

The **MITRE** Corporation maintains the CVE system. For more information and to search for existing CVEs, visit the [CVE Program website](https://www.cve.org/). Alternatively, visit the[ National Vulnerability Database (NVD)](https://nvd.nist.gov/) website.

### Exploit Database

There are many reasons why you would want to exploit a vulnerable application; one would be assessing a company’s security as part of its red team. Needless to say, we should not try to exploit a vulnerable system unless we are given permission, usually via a legally binding agreement.

Now that we have permission to exploit a vulnerable system, we might need to find a working exploit code. One resource is the [Exploit Database](https://www.exploit-db.com/). The Exploit Database lists exploit codes from various authors; some of these exploit codes are tested and marked as verified.

GitHub, a web-based platform for software development, can contain many tools related to CVEs, along with proof-of-concept (PoC) and exploit codes. To demonstrate this idea, check the screenshot below of search results on GitHub that are related to the Heartbleed vulnerability.
