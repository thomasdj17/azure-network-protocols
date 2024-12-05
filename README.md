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

<h2>High-Level Deployment and Configuration Steps</h2>

- Create virtual machine
- Log into virtual machine with Remote Desktop
- Retrieve IP
- Ping a public site using Powershell
- Observe the ping traffic in WireShark

<h2>Deployment and Configuration Steps</h2>

 <p> 
<img src="https://i.imgur.com/P9f6XqS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows the Virtual Machine being created in Azure
</p>
<br />
</p>
<p>
</p>
<p>
 
<p>
<img src="https://i.imgur.com/93KKcVv.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows logging into the virtual machine
</p>
<br />
</p>
<p>
</p>
<p>

<p>
<img src="https://i.imgur.com/QeehDgp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows the private IP address of Virtual Machine being searched and found
</p>
<br />
</p>
<p>
</p>
<p>

<p>
<img src="https://i.imgur.com/UiFg89X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows the use of powershell inside the virtual machine sending a ping to another machine
</p>
<br />
</p>
<p>
</p>
<p>


<p>
<img src="https://i.imgur.com/ium0TJi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows the reply being sent back to our machine through Wireshark
</p>
<br />
