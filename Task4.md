# Cyber-Security Task 4

Aim: To configure and test basic firewall rules to allow or block network traffic using Windows Firewall or UFW on Linux.

Software Required:
- Windows Firewall (for Windows users)
- UFW (Uncomplicated Firewall) for Linux
- Command Line / Terminal or Firewall GUI

Procedure / Steps:
- Open the firewall configuration tool
- List current firewall rules
- Add a rule to block inbound traffic on a specific port
- Test the rule by trying to connect to port 23
- Add a rule to allow SSH (port 22) to ensure remote access remains functional
- Remove the test rule to restore the firewall to its original state
- Document each command or step used, and optionally take a screenshot of the firewall status.

Output :
Status: active

To               Action      From
--               ------      ----
22               ALLOW       Anywhere
23               DENY        Anywhere (until removed)

Conclusion:
This task provided hands-on experience in managing firewall rules. Blocking insecure ports like Telnet (23) and allowing essential services like SSH (22) are fundamental steps in securing a system. Understanding how firewalls filter traffic improves overall awareness of network security and system protection.
