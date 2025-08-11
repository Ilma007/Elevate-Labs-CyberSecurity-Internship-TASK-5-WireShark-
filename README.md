# Elevate-Labs-CyberSecurity-Internship-TASK-5-WireShark-
Capture and Analyze Network Traffic Using Wireshark.

Wireshark Network Traffic Analysis Report

1. Objective
The objective of this task is to capture live network traffic using Wireshark, analyze different protocols, identify communication patterns.

2. Methodology
Setup:
open your kali linux terminal 

Installed Wireshark/open Wireshark through terminal and confirmed permissions to capture on the network interface.

Selected the active interface based on live traffic statistics.

Capture:

Started capture for ~60 seconds.

Generated sample network traffic by browsing websites, pinging, and performing DNS lookups.

for example : I select and ping  www.instagram.com 

and then stop the capturing packets ..........and then find the active packets through the filter .
by using this command ip.addr == 157.240.239.174
and then simply enter press.

Analysis:

All the selected packets of this ip is filterered and display on the screen .

now do same for .....
Applied display filters for specific protocols (TCP,UPD,DNS, HTTP, TLS, ICMP).ETC. By using this command ....

TCP &&/and ip.addr == 157.240.239.174


Conclusion & Recommendations
The captured traffic shows normal browsing activity with standard protocols (TCP,UDP,DNS, TLS, HTTP, ICMP, ARP). No malicious or suspicious patterns were detected.
For a more thorough analysis:

Capture longer sessions.

Use Wireshark expert info (Analyze → Expert Information).

Apply protocol-specific dissectors for deeper inspection.



Followed selected TCP/UDP streams to inspect packet-level data.


.......................................COMMANDS ......................................
1.sudo apt update
2.sudo apt upgrade
3.sudo apt install wireshark
or 
open preinstall wireshark in your kali linux 
4. start your scanning the traffic in your wireshark tool ....
5.open your search broswer and open any website or any login website for search and then back to your tool then stp the captureing .
6. now filter your scanning packets through this command ...
ip.addr == <ip address> of target website .... or search through short abbrivation .
7. now you can search your tcp , udp ,dns ,icmp packets through using this command which show you the result into text form .
tcp and/&& ip.addr == <ip address>

then analyze your traffic on network .



FOR TRAFFIC SCAN AND ANALYZE 
<img width="1701" height="827" alt="image" src="https://github.com/user-attachments/assets/f81a4e81-fd61-466a-a46d-a08cb0d5175a" />


FOR IP.ADDR == 157.240.239.174
<img width="1687" height="696" alt="image" src="https://github.com/user-attachments/assets/c1b9f34a-51d8-4bca-9b73-cdb414693c23" />

FOR UDP
<img width="1608" height="807" alt="image" src="https://github.com/user-attachments/assets/5814649d-8c77-415d-9b3f-547546913674" />
FOR TCP
<img width="1640" height="693" alt="image" src="https://github.com/user-attachments/assets/10508793-53c4-4c4d-adbf-d805809f6019" />

