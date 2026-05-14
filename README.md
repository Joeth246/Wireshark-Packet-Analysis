# Wireshark-Packet-Analysis
Network traffic analysis of ICMP, DNS, TCP, HTTP, and TLS packets to understand protocol behavior and identify communication patterns.

## Overview
This project focuses on analyzing network traffic to understand how data moves across systems at the packet level. Packet captures were reviewed to observe protocol behavior, communication flows, and encrypted traffic patterns.

The analysis includes ICMP, DNS, TCP, HTTP, and TLS traffic to demonstrate foundational network forensics and protocol understanding.

## Objectives
- Capture and analyze ICMP, DNS, TCP, HTTP, and TLS traffic
- Understand how devices communicate over a network
- Identify request/response patterns across protocols
- Observe encrypted vs unencrypted traffic behavior
- Develop foundational network security analysis skills

## Traffic Analysis Findings

### ICMP (Ping Traffic)
- Captured ICMP echo requests and echo replies using ping
- Verified network reachability between source and destination hosts
- Observed round-trip response behavior

### DNS (Domain Resolution)
- Analyzed DNS queries and responses during domain lookups
- Identified how domain names are resolved into IP addresses
- Observed query-response timing and resolution patterns

### TCP (Connection Establishment)
- Observed TCP three-way handshake (SYN, SYN-ACK, ACK)
- Analyzed reliable connection setup between client and server
- Tracked sequence and acknowledgment numbers

### HTTP Traffic
- Examined unencrypted HTTP requests and responses
- Identified visible headers and transmitted data
- Observed client-server communication over port 80

### TLS / HTTPS Traffic
- Analyzed encrypted HTTPS traffic patterns
- Observed TLS handshake before secure communication begins
- Identified encrypted payload behavior (no readable application data)

## Key Observations
- ICMP traffic confirmed basic network connectivity and latency behavior
- DNS analysis showed how domain names resolve into IP addresses
- TCP handshake demonstrated reliable connection establishment
- HTTP traffic exposed readable application-layer data
- TLS encrypted traffic protected payload visibility while still showing handshake metadata

## Skills Demonstrated
- Network packet analysis
- Protocol identification (ICMP, DNS, TCP, HTTP, TLS)
- Understanding of OSI/TCP-IP model layers
- Traffic flow interpretation
- Basic network security awareness and inspection
