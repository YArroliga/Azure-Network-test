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

- Windows 10
- Ubuntu Server 20.04

<h2>Network Security Lab </h2>

- Create 2 Virtual Machines using Linux and Windows software
- Observe ICMP Traffic
- Observe SSH Traffic
- Observe DHCP Traffic
- Observe DNS Traffic
- Observe RDP Traffic

<h2>Actions and Observations</h2>

<p>
  
![image](https://github.com/YArroliga/Azure-Network-test/assets/139689160/839aff11-08c5-44c4-a7f2-4a4213480c54)
![image](https://github.com/YArroliga/Azure-Network-test/assets/139689160/3ad0df6c-19cf-4912-b9ce-5db26ad528c6) 

</p>
<p>
To start this lab we create two Virtual Machines on Azure. One running Windows 11 and the other running Ubuntu 20.04 
<br />

![image](https://github.com/YArroliga/Azure-Network-test/assets/139689160/bccb7648-7297-4c00-aa21-b376ce9fe714) 
<p>

</p>
<p>
Remote Desktop into the Windows VM
</p>
<br />

![image](https://github.com/YArroliga/Azure-Network-test/assets/139689160/a76cc0d7-d144-4f5c-9d5d-71c349737027) 
![image](https://github.com/YArroliga/Azure-Network-test/assets/139689160/189acc9e-d8fa-4cfa-a42d-942ace71b616)


<p> Download Wireshark for the lab
</p>
  <h3> Observe ICMP traffic </h3> 

![image](https://github.com/YArroliga/Azure-Network-test/assets/139689160/f15021a4-5006-4bf9-96ed-e27e41aa0d64)

  <p> Using Powershell and Wireshark we can visualize when we ping Google.com
  </p>
  

</p>
<p>

</p>
<br />
