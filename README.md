# codealphas
Network Packet Sniffer
A simple packet sniffer built using Python and the Scapy library to capture and analyze network packets. This script filters packets based on TCP, UDP, and IP protocols and displays relevant details, such as source and destination IPs, port numbers, and raw payload data.

Table of Contents
Installation
Usage
Features
Example Output
License
Installation
Ensure Python is installed on your machine. This script is compatible with Python 3.x.
Install Scapy using pip:
pip install scapy
To run the script: python packet_sniffer.py Example Output Source IP: 192.168.1.5, Destination IP: 192.168.1.10 TCP Source Port: 443, Destination Port: 53784 Payload (Raw Data): b'...'
