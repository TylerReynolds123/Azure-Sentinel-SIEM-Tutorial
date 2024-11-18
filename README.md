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
Create Virtual Machine Domain Controller (DC): <br/>
<img src="https://i.imgur.com/ecLpPBK.jpg" height="80%" width="80%" alt="VM Steps"/> 
<br />
<br />
Configure Internet and Internal NICs:  <br/>
<img src="https://imgur.com/apPkzqr.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Configure IP address settings: <br/>
<img src="https://imgur.com/YHd9Ybh.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Add Active Directory to Virtual Machine:  <br/>
<img src="https://imgur.com/kQYvXsC.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Created myself as a user:  <br/>
<img src="https://imgur.com/JpgYxrQ.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Configure Routing/Remote Access:  <br/>
<img src="https://imgur.com/295qODC.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Created users from script:  <br/>
<img src="https://imgur.com/hRVrrSL.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Create and Configure "CLIENT1" VM:  <br/>
<img src="https://imgur.com/nYs6NgN.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Use the "ping" command to verify internet connectivity/confirm DNS resolution:  <br/>
<img src="https://imgur.com/i1WvOiF.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Verify client is in DHCP lease:  <br/>
<img src="https://imgur.com/0AgvMw5.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Ensure client is a member of DC: <br/>
<img src="https://imgur.com/LBUNYT2.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Verify successful login to mydomain.com: <br/>
<img src="https://imgur.com/xlXIanu.jpg" height="80%" width="80%" alt="VM Steps"/>

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
