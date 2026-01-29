# Task-1 : Basic Network Scanning with Nmap
## Objective
Perform a network scan to identify open ports and running dervices on a target machine using Nmap.
## Tools used
- Nmap

## Target 
Local Virtual Machine

## Command Executed
 sudo nmap -sT -p 80,443 10.0.2.15/24

 ## Results
 The scan identified the following open ports:
 PORT     STATE SERVICE
135/tcp  open  msrpc
445/tcp  open  microsoft-ds
5357/tcp open  wsdapi
6646/tcp open  unknown

 ## Significance
 Open ports indicate services running on the system. If misconfigured, they can be exploited by attackers. 
 Identifying open ports helps administratiors secure systems by closing unnecessary services and applying patches.

 ## Conclusion
 Nmap successfully detected open ports and services on the target machine. This demonstrates the importance of network scanning
 as a first step in penetration testing and security auditing.
