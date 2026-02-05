# CYBR – Lab 1: Network Assessment with Common Security Tools

## Overview
This project documents a hands-on enterprise cybersecurity lab focused on
network reconnaissance, traffic analysis, and firewall baseline assessment.

## Tools Used
- Wireshark
- Nmap / Zenmap
- tcpdump
- hping3
- ipconfig / ifconfig
- Telnet (HTTP GET testing)

## What I Did
- Collected host and network configuration (IP, subnet, gateway, MAC)
- Reviewed ARP behavior and host discovery traffic (ICMP/ARP)
- Captured and filtered traffic in Wireshark (ICMP, ARP)
- Performed host/port discovery using Nmap profiles (Regular/Intense)
- Observed TCP handshake behavior using tcpdump
- Validated HTTP exposure via manual GET request and noted server banner
- Documented DMZ host configuration and established firewall baseline behavior

## Key Findings (Lab Environment)
- ICMP echo request/reply traffic was observed
- Port 80 (HTTP) was open and responding
- No ARP or DNS traffic was observed from the WAN perspective
- HTTP response revealed an NGINX server banner

## Skills Demonstrated
- Packet capture and protocol filtering
- Reconnaissance visibility and baseline assessment
- Understanding of LAN/WAN/DMZ segmentation
- Interpreting TCP handshake activity from packet traces
  
## Evidence (Selected Screenshots)
See the `screenshots/` folder for supporting captures.

## Notes
Educational use only. All testing performed in an isolated academic lab environment.
