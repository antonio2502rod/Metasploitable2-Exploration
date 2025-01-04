# Metasploitable2 Vulnerability Assesment

## Description
This project is a part of my cybersecurity learning journey, focusing on vulnerability assessment and explotation using Metasploitable2 as a test enviroment. The purpose of this repository is to document the tools, techniques, and results obtained during the process.

## Objetives
- Conduct a thorough vulnerability assessment of a vulnerable virtual machine (Metasploitable2).
- Use industry-standard tools to identify and exploit vulnerabilities.
- Document findings and provide insights for the future improvements,

## Tools Used
- Nmap: For network and port scanning.
- Searchsploit: For identifying known vulnerabilities.
- Metasploit: For exploiting vulnerabilities.

## WorkFlow
1. Port Scanning: Used Nmap to identify open ports, services and versions.
   - Command: 'nmap -sS -sV -p- 192.168.200.5'
2. Vulnerability Discovery: Leveraged Searchsploit to find known vulnerabilities based on the services identified.
3. Explotation: Used Metasploit to exploit vulnerabilities and gain access to the target system.

## Results
- Successfully identified open ports and running services.
- Found several known vulnerabilities in outdated software.
- Gained unauthorized accedd to the Metasploitable2 virtual machine.

## Folder Structure
The repository is organized as follows:
