<h1>Azure Sentinel SIEM Tutorial</h1>

 

<h2>Description</h2>
In this project, I set up Microsoft Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. I observe attacks (RDP Brute Force) from all over the globe. I use a custom PowerShell script to look up the attacker's geolocation information and plot it on the Microsoft Sentinel Map. This simulates LIVE cyber attacks!
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>Microsoft Sentinel</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Virtual Machine</b>

<h2>Program walk-through:</h2>

<p align="center">
Create a free Azure account: <br/>
<img src="https://imgur.com/dkAT6lh.jpg" height="80%" width="80%" alt="SIEM Steps"/> 
<br />
<br />
Create Virtual Machine (HoneyPot):  <br/>
<img src="https://imgur.com/Zs7fZkp.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Create Inbound rule to allow ALL internet traffic into VM: <br/>
<img src="https://imgur.com/NnBH6rY.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Deploy Virtual Machine:  <br/>
<img src="https://imgur.com/7GnYW49.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Deploy Log Analytics:  <br/>
<img src="https://imgur.com/6xnfjKa.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Capture logs in Microsoft Defender:  <br/>
<img src="https://imgur.com/QOFErrl.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Enable gathering VM logs in Security Center:  <br/>
<img src="https://imgur.com/NOATXKW.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Connect Log Analytics to VM:  <br/>
<img src="https://imgur.com/2DFmpRS.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Set up Azure Sentinel:  <br/>
<img src="https://imgur.com/iMpX8Ib.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Log into VM with Remote Desktop:  <br/>
<img src="https://imgur.com/eoO2gzw.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Observe Event Viewer Logs in VM: <br/>
<img src="https://imgur.com/6eneOBo.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Turn off Windows Firewall on VM: <br/>
<img src="https://imgur.com/zG1hMVa.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Get Geolocation.io API key: <br/>
<img src="https://imgur.com/J4zb6dy.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Run Script to get Geo data from attackers: <br/>
<img src="https://imgur.com/490RAvF.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Create Custom Log in L.A.W.: <br/>
<img src="https://imgur.com/eJvEsC6.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Extract Fields: <br/>
<img src="https://imgur.com/hz7u63w.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Set up map in Sentinel: <br/>
<img src="https://imgur.com/xbi9M8s.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
See results on the map!: <br/>
<img src="https://imgur.com/PufZzsr.jpg" height="80%" width="80%" alth="SIEM Steps"/>
 
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
