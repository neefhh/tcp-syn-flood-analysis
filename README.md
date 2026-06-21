# tcp-syn-flood-analysis
Wireshark analysis of a TCP SYN Flood DoS attack.
# TCP SYN Flood Attack Analysis
## Overview
This project analyzes a network traffic log to identify the cause of a website connection timeout. The investigation found signs of a TCP SYN flood denial-of-service attack.

## Tools Used
- Wireshark
- TCP/HTTP traffic logs
- Cybersecurity incident report

## Attack Identified
The attack identified was a TCP SYN flood attack.

## Evidence
The traffic logs showed repeated SYN packets from IP address 203.0.113.0 to the web server at 192.0.2.1. These connection requests did not complete the TCP three-way handshake.

## Impact
The attack caused the server to reserve resources for many incomplete connections. This can lead to slow response times, connection timeouts, and denial of service for legitimate users.

## Skills Demonstrated
- Network traffic analysis
- TCP/IP fundamentals
- Wireshark log review
- Denial-of-service attack identification
- Cybersecurity incident reporting
