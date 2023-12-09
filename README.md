# Cybersecurity Internship Project: Nmap Port Scans

## Overview
This repository showcases my summer internship project conducted at Cyberekta, focusing on cybersecurity and Nmap port scans. The project explores various Nmap scanning techniques, identifies common vulnerabilities, and utilizes different scan types for comprehensive network security assessment.

**Port scanning** is an essential method for identifying open ports and services within a network, providing security professionals and network administrators with valuable insights to assess network security and identify potential vulnerabilities. This undertaking delves into the nuances of TCP flags, exploring the ramifications of sending TCP packets with specific flags set outside the confines of an established TCP connection. It comprehensively examines various port scanning techniques, encompassing Null Scan, FIN Scan, Xmas Scan, Maimon Scan, ACK Scan, Window Scan, and Custom Scan, elucidating their mechanisms and applications. The initiative emphasizes the critical role of port scanning in evaluating network security while underscoring the utmost importance of responsible and ethical utilization of this technique.

The project involves a thorough examination of alternative port scanning techniques employing TCP flags to elicit responses from target hosts. It specifically aims to achieve the following objectives:

**Mechanism and Application of Port Scanning Techniques:** Investigate the theoretical foundations and practical implementation of diverse port scanning techniques, including Null Scan, FIN Scan, Xmas Scan, Maimon Scan, ACK Scan, Window Scan, and Custom Scan.

**Effectiveness of Port Identification:** Conduct experiments and simulations to evaluate the capability of each port scanning technique to accurately identify open ports and services on target hosts.

**Detectability by Network Security Devices:** Assess the likelihood of each technique being detected by firewalls, intrusion detection systems, and other network security devices.

**Recommendations for Network Security Assessments:** Based on the evaluation findings, provide recommendations for the appropriate use of these port scanning techniques in network security assessments.

**Impact on TCP Flag Status:** Analyze the status of TCP flags for each scanned port, determining which flags are set to 1 and which are set to 0.

**Quantification of Open and Filtered Ports:** Quantify the number of ports identified as open or filtered as a result of the scans.

**Flag Counts for Scanned Ports:** Count the number of TCP flags set for each scanned port, offering additional insights into the port states and potential vulnerabilities.

**Analysis of Port Numbers After Scans:** Examine the range of port numbers scanned and identify the specific open or filtered port numbers.

**Identification of Services Behind Newly Discovered Ports:** For newly discovered open ports, attempt to identify the services running behind them using techniques such as banner grabbing, service detection tools, and network traffic analysis.

## Key Features
- **Scan Techniques:** In-depth exploration of Nmap scanning methodologies.
- **Vulnerability Assessment:** Identification and documentation of common vulnerabilities.
- **Comprehensive Scanning:** Use of various scan types (TCP, UDP, SYN) for thorough network analysis.

## Tools and Technologies
- **Nmap:** The primary tool used for conducting port scans.
- **Kali Linux:** Operating System
- **Network:** Need a network with a target host to scan (home network/college network)

While the project primarily focuses on the technical aspects and effectiveness of these port scanning techniques, it does not explicitly delve into the ethical considerations or legal implications of unauthorized port scanning. However, the project emphasizes the significance of responsible and ethical use of these techniques.


