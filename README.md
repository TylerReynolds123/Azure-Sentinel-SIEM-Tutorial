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
<img src="https://i.imgur.com/dkAT6lh.jpg" height="80%" width="80%" alt="SIEM Steps"/> 
<br />
<br />
Create Virtual Machine (HoneyPot):  <br/>
<img src="https://i.imgur.com/Zs7fZkp.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Create Inbound rule to allow ALL internet traffic into VM: <br/>
<img src="https://i.imgur.com/NnBH6rY.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Deploy Virtual Machine:  <br/>
<img src="https://i.imgur.com/7GnYW49.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Deploy Log Analytics:  <br/>
<img src="https://i.imgur.com/6xnfjKa.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Capture logs in Microsoft Defender:  <br/>
<img src="https://i.imgur.com/QOFErrl.jpg" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Enable gathering VM logs in Security Center:  <br/>
<img src="https://i.imgur.com/NOATXKW.jpg" height="80%"
