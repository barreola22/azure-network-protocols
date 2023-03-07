<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

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

- Step 1
- Step 2
- Step 3
- Step 4

1. Create Network Security Groups: The first step is to create Network Security Groups within Azure that define the rules for inspecting traffic between Azure Virtual Machines. These rules can allow or deny traffic based on source and destination IP addresses, port numbers, and protocol.

2. Assign NSGs to Virtual Machines: Once the NSGs are created, assign them to the Azure Virtual Machines that you want to secure. This can be done by associating the NSGs with the virtual network or the individual network interfaces of the virtual machines.

3. Define Inbound and Outbound Rules: After assigning NSGs to Virtual Machines, define inbound and outbound rules to inspect traffic between them. Inbound rules define how traffic can enter a Virtual Machine, while outbound rules define how traffic can leave it.

4. Test and Refine Rules: Once the rules are defined, test them to ensure that they are working as expected. You can use the Azure Portal or command-line tools to monitor network traffic and verify that the rules are correctly inspecting traffic between Azure Virtual Machines. Refine the rules as needed to ensure that your network security is effective and efficient.

By following these steps, you can use Network Security Groups to inspect traffic between Azure Virtual Machines, and help ensure that your network is secure and protected. It is essential to regularly monitor and refine the NSG rules to maintain the security of your Azure environment.
