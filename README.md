# azure-network-protocols
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

- Creating Resources
- Remote Desktop
- Perform activities on network

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/ughfays.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log into microsoft azure and create a resource group. Once you creaed your resource group create two VM one will be running on windows 10 and the other will be running on linux. When creating the linux VM make sure you click password for Authentication Type. Both VM's should be completed and now go to the start menu and type remote desktop connection. Copy and past your windows 10 VM public IP address.
</p>
<p>
<img src="https://i.imgur.com/MUcAycD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sign into remote desktop by using the user name and password you set up in the VM. Open explorer page and download Wireshark application windows installer (64-bit). When download is complete open up wireshark and click the ethernet adapter and than click on the blue shark fin icon. This will show you the live traffic on the VM. Now yo will be able to use windows powershell application to ping from one VM to the other by using the Private IP address associated with the linux vm.
</p>
<p>
<img src="https://i.imgur.com/4TtaYVK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<br />
