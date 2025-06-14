# Cyber-Security Task 5

Aim: To capture live network packets using Wireshark and identify at least three different protocols and their characteristics.

Software Required: 

-Wireshark (Free network protocol analyzer)

-Internet connection to generate traffic during capture


Procedure / Steps:

-Install Wireshark from https://www.wireshark.org

-Launch Wireshark and start capturing on the active network interface (e.g., Ethernet, Wi-Fi)

-Generate traffic by browsing a website or running commands like

-Stop capturing after around 1 minute

-Use the Filter bar to isolate traffic by protocols:

- http for web traffic

- dns for domain resolution

- tcp or udp for transport layer

-Identify 3 protocols, note down their characteristics

-Export the capture as a .pcap file (File > Export Specified Packets)

-Summarize findings including packet counts and behavior

Output (Sample Protocol Summary):

Captured Protocols:

DNS: Queries and responses between host and DNS server (port 53)

TCP: Reliable connection-based traffic, such as HTTP and HTTPS

HTTP: Web browsing traffic showing GET and POST methods


Conclusion:

This task provided hands-on experience with network analysis using Wireshark. By filtering and identifying traffic types, a clearer understanding of how devices communicate over the internet was achieved. Mastery of such tools is essential for network troubleshooting and cybersecurity analysis.



