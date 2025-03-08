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

- Create a Windows 10 Virtual Machine (VM) & a Linux (Ubuntu) VM
- Ensure both VMs are in the same Virtual Network / Subnet
- Use Remote Desktop
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/cUWZLku.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
While creating the VM, select the previously created Resource Group
While creating the VM, allow it to create a new Virtual Network (Vnet) and Subnet
<p>
While creating the VM, select the previously created Resource Group and Virtual Network—the Virtual Network must be the same.
</p>
<br />

<p>
<img src="https://i.imgur.com/qwNWL5C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
While creating the VM, select the previously created Resource Group and Virtual Network—the Virtual Network must be the same.
</p>
<br />

<p>
<img src="https://i.imgur.com/GYd74FZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
MSTSC, or Microsoft Terminal Services Client, is a command line interface that allows users to connect to remote computers and virtual machines. It's also the name of the Remote Desktop Connection app in Windows. 
</p>
<br />
