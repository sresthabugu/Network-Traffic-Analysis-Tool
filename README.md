\Network Traffic Analysis Tool with Wireshark and Nmap\
This repository contains a shell script for analyzing network traffic patterns and identifying potential security threats.

Features:

Captures network traffic on a specified interface using Wireshark.\
Performs a basic Nmap scan on a defined IP address range.\
Opens the captured traffic in Wireshark for further analysis.\
Displays Nmap scan results for identified active hosts.

Requirements:

Wireshark\
Nmap\
Bash Shell

How to Use:

Clone this repository.
Save the script as a file (e.g., network_analysis.sh).
Make the script executable: chmod +x network_analysis.sh
Run the script: ./network_analysis.sh
Customization:

Edit the script to change:
Network interface for traffic capture (default: enp0s3)\
Capture duration (default: 30 seconds)\
Captured traffic filename (default: traffic.pcap)\
Target IP range for Nmap scan (default: 192.168.1.0/24)

Analysis:

Use Wireshark to analyze the captured traffic for suspicious patterns:\
Unusual ports\
Excessive traffic from specific hosts\
Unauthorized protocols\
Review the Nmap scan results for identified active hosts and potential vulnerabilities.\

Note:

This is a basic script for educational purposes. A comprehensive security analysis requires a deeper understanding of network protocols, Wireshark, and Nmap.
