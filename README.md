<h1>SOC/SOAR Home Lab</h1>

<h2>Description</h2>
In my recent project, I led the implementation of a sophisticated Security Orchestration, Automation, and Response (SOAR) system, integrating Wazuh, Shuffle, TheHive, and Cortex technologies. I meticulously configured my Windows 11 machine as a Wazuh client to track file activities. Leveraging Telegram integration, real-time log notifications were seamlessly dispatched, ensuring stakeholders stayed promptly informed of security events.

Central to the system's architecture was Shuffle, where I crafted workflows to extract file hashes from Wazuh alerts. These hashes were relayed to Cortex, enriched with Malware Bazar and VirusTotal integrations for thorough threat analysis. Cortex's insights into potential risks empowered proactive mitigation strategies.

Results from Cortex seamlessly flowed into TheHive, facilitating incident response management. Predefined use cases enabled automated decision-making based on threat severity, with admins promptly notified. This project showcased my expertise in configuring and integrating diverse security technologies, enhancing our organization's cybersecurity posture in today's evolving threat landscape.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
  
<h2>Environments Used </h2>

- <b>VmWare</b> 
- <b>Docker</b> 
- <b>Wazuh</b>
- <b>Cortex</b>
- <b>TheHive</b>
- <b>Shuflle</b>
- <b>Telegram</b>
- <b>Windows 11</b>



<h2>Program walk-through:</h2>

<p align="center">
Wazuh Interface : <br/>
<img src="https://imgur.com/xGYdGSD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center" >
Wazuh agent in my windowsq 11 machine<br/>
 <img src="https://imgur.com/yADP0VQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Real-time alerts bein sent in telegram<br/>
 <img src="https://imgur.com/NyOkuy6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
File created in windows agent machine<br/>
 <img src="https://imgur.com/5GsxRTA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Alerts in Wazuh <br/>
 <img src="https://imgur.com/oLdkUbK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Automated Workflow in Shuffle <br/>
 <img src="https://imgur.com/UxvfcYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Thehive Interface<br/>
 <img src="https://imgur.com/zhwayR1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Usecase and observations in thehive<br/>
 <img src="https://imgur.com/30oVqVt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Cortex Interface<br/>
 <img src="https://imgur.com/unelf8t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



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
