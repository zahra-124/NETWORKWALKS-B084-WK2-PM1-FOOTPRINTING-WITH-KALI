# NETWORKWALKS-B084-WK2-PM1-FOOTPRINTING-WITH-KALI
A hands-on cybersecurity project exploring footprinting and reconnaissance using six Kali Linux tools: WHOIS, WhatWeb, Nslookup, cURL, WAFW00F, and DNSRecon.

# Footprinting & Reconnaissance Using Kali Linux

## Project Overview

This repository documents my practical work on **Footprinting and Reconnaissance**, completed as part of Week 2, Project Module 1, during my cybersecurity training with **NetworkWalks**.

The project explores the reconnaissance phase of ethical hacking, focusing on gathering and analysing publicly available information about a domain to understand its digital footprint and externally exposed infrastructure.

Using Kali Linux, I explored six reconnaissance tools, each providing a different perspective on the target's publicly accessible information.

## Objectives

- Understand the importance of reconnaissance in ethical hacking.
- Investigate domain registration and DNS information.
- Identify website technologies and server components.
- Analyse HTTP response headers.
- Understand Web Application Firewall detection.
- Enumerate publicly accessible DNS records.
- Document findings and understand their security implications.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| WHOIS | Domain registration and ownership information |
| WhatWeb | Website technology fingerprinting |
| Nslookup | Domain-to-IP resolution |
| cURL | HTTP response header analysis |
| WAFW00F | Web Application Firewall detection |
| DNSRecon | DNS record enumeration |

## Project Tasks

### 1. WHOIS – Domain Information
Investigated domain registration details, registrar information, registration dates and name servers.

<img width="1028" height="465" alt="kaliwhois png" src="https://github.com/user-attachments/assets/ae40fef4-2b99-4852-81a0-726a478f18ee" />


### 2. WhatWeb – Technology Fingerprinting
Identified publicly detectable website technologies, frameworks and server components.

<img width="1897" height="177" alt="whatweb" src="https://github.com/user-attachments/assets/a15b6481-ad15-4783-96ac-0d8fd4415365" />


### 3. Nslookup – DNS Resolution
Examined domain name resolution and identified the associated IP address.

<img width="291" height="147" alt="nslookup" src="https://github.com/user-attachments/assets/da6748aa-6a86-4241-95fd-36831ed51846" />


### 4. cURL – HTTP Header Analysis
Analysed HTTP response headers to understand server responses, technologies and related information.

<img width="1895" height="317" alt="curl" src="https://github.com/user-attachments/assets/f2b8758f-2bda-4c7f-b56b-02b316b180a6" />


### 5. WAFW00F – Firewall Detection
Investigated whether a Web Application Firewall was present and identified the reported firewall technology.

<img width="713" height="345" alt="wafw00f" src="https://github.com/user-attachments/assets/6f8b766f-cfe3-41ea-beb5-c098b2037bae" />


### 6. DNSRecon – DNS Enumeration
Explored DNS records, including:
- Name server records
- Mail exchange records
- TXT records
- SPF information
- Service records (SRV)

<img width="1185" height="417" alt="dnsrecon" src="https://github.com/user-attachments/assets/ccde03fa-85be-46a2-982b-231581897b39" />


## Key Learning Outcomes

Through this project, I developed a better understanding of:

- The role of reconnaissance in the ethical hacking lifecycle.
- How different tools contribute to information gathering.
- The relationship between DNS infrastructure and web hosting.
- Website technology fingerprinting.
- The security implications of publicly exposed information.
- How reconnaissance findings can help organisations evaluate their external attack surface.


## Ethical Considerations

This project was conducted for educational purposes as part of cybersecurity training, with appropriate authorization from NetworkWalks.

Reconnaissance activities should only be performed against systems you own or have explicit permission to assess. Findings should be handled responsibly and should not be used to access, disrupt or compromise systems.

## Acknowledgements

Special thanks to **NetworkWalks** for providing the project framework and practical learning opportunity.

---

**Project:** Week 2 – Project Module 1  
**Focus:** Footprinting & Reconnaissance  
**Environment:** Kali Linux  
**Organisation:** NetworkWalks
