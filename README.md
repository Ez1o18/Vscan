# VScan v1.2 - The Multi-Tool Web Vulnerability Scanner

A multi-tool web security scanner is a software tool or application designed to identify and assess security vulnerabilities and weaknesses in web applications, websites, or web services

# Features
-> One-step installation.
-> Executes a multitude of security scanning tools, does other custom coded checks and prints the results spontaneously.
-> Some of the tools include nmap, dnsrecon, wafw00f, uniscan, sslyze, fierce, lbd, theharvester, amass, nikto etc executes under one entity.
-> Saves a lot of time, indeed a lot time!.
-> Checks for same vulnerabilities with multiple tools to help you zero-in on false positives effectively.
-> Extremely light-weight and not process intensive.
-> Legends to help you understand which tests may take longer time, so you can Ctrl+C to skip if needed.
-> Association with OWASP Top 10 & CWE 25 on the list of vulnerabilities discovered. (under development)
-> Critical, high, medium, low and informational classification of vulnerabilities.
-> Vulnerability definitions guides you what the vulnerability actually is and the threat it can pose.
-> Remediation tells you how to plug/fix the found vulnerability.
-> Executive summary gives you an overall context of the scan performed with critical, high, low and informational issues discovered.
-> Artificial intelligence to deploy tools automatically depending upon the issues found. for eg; automates the launch of wpscan and plecost tools when a wordpress installation is found. (under development)
-> Detailed comprehensive report in a portable document format (*.pdf) with complete details of the scans and tools used. (under development)
-> On the run metasploit auxilliary modules to discover more vulnerabilities. (under development)

# FYI:
-> Program is still under development, works and currently supports 80 vulnerability tests.
-> Parallel processing is not yet implemented, may be coded as more tests gets introduced.

# Vulnerability Checks:
-> ✔️ DNS/HTTP Load Balancers & Web Application Firewalls.
-> ✔️ Checks for Joomla, WordPress and Drupal
-> ✔️ SSL related Vulnerabilities (HEARTBLEED, FREAK, POODLE, CCS Injection, LOGJAM, OCSP Stapling).
-> ✔️ Commonly Opened Ports.
-> ✔️ DNS Zone Transfers using multiple tools (Fierce, DNSWalk, DNSRecon, DNSEnum).
-> ✔️ Sub-Domains Brute Forcing (DNSMap, amass, nikto)
-> ✔️ Open Directory/File Brute Forcing.
-> ✔️ Shallow XSS, SQLi and BSQLi Banners.
-> ✔️ Slow-Loris DoS Attack, LFI (Local File Inclusion), RFI (Remote File Inclusion) & RCE (Remote Code Execution).
& more coming up...

# Requirements
-> Python 3
-> Kali OS (Preferred, as it is shipped with almost all the tools)
-> Tested with Parrot & Ubuntu Operating Systems.

# Usage
python3 vscan.py target.com

# Installation
Alternatively, your can install the Vscan python module with pip. This will create a link for vscan in your PATH.
git clone https://github.com/arun1033/Vscan.git
cd vscan
python3 -m pip install .
