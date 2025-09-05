# Week 2 - VAPT Project

## Project Overview

This repository contains the documentation for a full Vulnerability Assessment and Penetration Test (VAPT) conducted on a Metasploitable2 virtual machine as part of the CyArt weekly task. The assessment follows the standard VAPT lifecycle, including reconnaissance, scanning, exploitation, post-exploitation, and reporting.

## VAPT Workflow / Steps

1.  **Reconnaissance:** Performed Open-Source Intelligence (OSINT) using tools like WHOIS and Sublist3r to gather initial information.
2.  **Scanning:** Conducted network and vulnerability scans using Nmap and OpenVAS to identify open ports, services, and known vulnerabilities.
3.  **Risk Assessment:** Analyzed scan results, prioritized vulnerabilities using CVSS, and logged all findings.
4.  **Exploitation:** Successfully exploited critical vulnerabilities in VSFTPD and Apache Tomcat using the Metasploit Framework to gain shell access.
5.  **Post-Exploitation:** Performed evidence collection by hashing sensitive system files to prove the level of access.


## Repository Contents

* `Final_VAPT_Report.pdf`: The main comprehensive report.
* `Vulnerability_Log.xlsx`: A spreadsheet of all identified vulnerabilities.
* `Evidence_Log.xlsx`: A log of post-exploitation evidence collection.
* `nmap_full_scan.txt`: Raw output from the Nmap discovery scan.
* `msf_output.txt`: Console log of the successful Metasploit exploit session.
* `screenshots/`: A directory containing all raw screenshot evidence.
* `hashes.txt`: Contains the SHA256 hashes of all submitted evidence files for integrity.
