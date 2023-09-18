<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Created a Windows 10 Virtual Machine & Linux (Ubuntu) Virtual Machine using Microsoft Azure 
- Used Remote Desktop to connect to Windows 10 
- Installed Wireshark and filters for ICMP traffic only
- Retrieved the private IP address of the Ubuntu VM and observed the ping requests and replies within Wireshark
- Disabled incoming (inbound) ICMP traffic within the Network Security Group used by Ubuntu VM
<h2>Actions and Observations</h2>

<p>
<img src="https://github.com/labuser41/azure-protocols/assets/144741692/6c5cc431-fc76-4eb7-a30b-a1d9fc0a3267">

</p>
<p>
<h4>Created a Resource Group. Within the Resource Group, I created a Windows 10 Virtual Machine (VM1)and a Linux (Ubuntu) Virtual Machine VM2. </h4>


</p>
<br />

<p>
<img src="https://github.com/labuser41/azure-protocols/assets/144741692/ecdd6fc1-6fa4-40ac-911a-6c5ec90e7332"/>
<img src="https://github.com/labuser41/azure-protocols/assets/144741692/413c66d4-daf9-42b5-bfda-4810a3660989"/>


</p>
<p>
<h4>Used Remote Desktop to connect to my Windows 10 Virtual Machine. Within my Windows 10 Virtual Machine, Installed Wireshark.</h4>

</p>
<br />

<p>
<img src="https://github.com/labuser41/azure-protocols/assets/144741692/7f7bd076-ef10-4d10-a400-89571707abd1)"/>

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
