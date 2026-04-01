#  Traffic Analysis Lab (Wireshark)

Objective
Analyze network traffic to identify normal behavior and understand how systems communicate over a network.

Tools Used
- Wireshark
- Kali Linux

Traffic Analysis

DNS Requests
Observed domains:
- google.com
- api.github.com
- fibertel.com.ar

Additionally, AAAA (IPv6) queries for google.com were detected.

HTTPS Traffic
Detected secure connections to external IP:

- 4.228.31.149:443

This indicates encrypted communication using HTTPS.


Uncommon Traffic
No unusual ports were observed. Traffic was limited to standard web ports (80 and 443).


Findings

- Normal browsing generates DNS queries and HTTPS traffic
- Multiple domains are resolved before establishing connections
- HTTPS encrypts communication between the client and external servers
- No suspicious or abnormal traffic was detected


Conclusion

This lab demonstrates how to capture and analyze real network traffic using Wireshark, identifying normal communication patterns and understanding DNS and HTTPS behavior.


## Author
Tomas Brown
