# Ethical Hacking – Vulnerability Assessment & Penetration Testing (VAPT) Lab

## Project Overview

This project demonstrates an authorized local Vulnerability Assessment and Penetration Testing (VAPT) lab performed using Kali Linux.

The project focuses on network identification, port and service enumeration, HTTP security analysis, vulnerability identification, remediation, and retesting.

## Tools & Technologies

- Kali Linux
- Nmap
- Python HTTP Server
- cURL
- Linux Networking Tools

## Key Activities

- Network and IP identification
- Connectivity testing
- Port discovery
- Service and version enumeration
- HTTP header analysis
- Directory exposure assessment
- Vulnerability identification
- Remediation
- Retesting

## Finding

A local HTTP service initially exposed the contents of the home directory through directory listing.

### Remediation

The HTTP service was moved to a dedicated VAPT lab directory and bound to `127.0.0.1` to restrict access to the local machine.

## Project Documentation

- VAPT Final Report – PDF
- VAPT Project Presentation – PPT

## Disclaimer

This project was performed in an authorized local lab environment for educational and cybersecurity learning purposes. No unauthorized systems were tested.# vapt-security-assessment-lab
Authorized local VAPT lab project using Kali Linux, Nmap, Python HTTP Server and cURL.
