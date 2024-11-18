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
<img src="https://imgur.com/zG1hMVa.jpg" height="80%" width="80%" alt="SIEM Steps"/>
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
Create and Configure "CLIENT1" VM:  <br/>
<img src="https://imgur.com/nYs6NgN.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Use the "ping" command to verify internet connectivity/confirm DNS resolution:  <br/>
<img src="https://imgur.com/i1WvOiF.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Verify client is in DHCP lease:  <br/>
<img src="https://imgur.com/0AgvMw5.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Ensure client is a member of DC: <br/>
<img src="https://imgur.com/LBUNYT2.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Verify successful login to mydomain.com: <br/>
<img src="https://imgur.com/xlXIanu.jpg" height="80%" width="80%" alt="SIEM Steps"/>

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
