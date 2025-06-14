# Cyber-Security Task 1
 
Aim : To discover open ports on devices in the local network using Nmap and understand the
network exposure for cybersecurity awareness.

Software Required : 
- Nmap – for performing port scans
- Wireshark (Optional) – for packet analysis
- Operating System: Windows/Linux/macOS

Steps :
1. Install Nmap from the official website: https://nmap.org/
2. Find your local IP range, e.g., 192.168.1.0/24:
 - On Windows: ipconfig
 - On Linux/macOS: ifconfig or ip a
3. Run a TCP SYN scan using:
 nmap -sS 192.168.1.0/24
4. Note down active IP addresses and open ports found.
5. Optional: Use Wireshark to capture and analyze network traffic during the scan.
6. Research services running on the open ports.
7. Identify potential security risks (e.g., outdated services, unnecessary open ports).
8. Save scan results using:
 nmap -oN result.txt 192.168.1.0/24
 or
 nmap -oX result.xml 192.168.1.0/24

Output : 

Nmap scan report for 192.168.1.1
Host is up (0.0020s latency).
Not shown: 996 closed ports
PORT STATE SERVICE
22/tcp open ssh
80/tcp open http
443/tcp open https
8080/tcp open http-proxy

Conclusion :

This task introduced basic network reconnaissance using Nmap. By scanning the local
network, open ports and running services were identified. This information is critical in
evaluating security exposure and hardening systems by closing or securing unused services.
