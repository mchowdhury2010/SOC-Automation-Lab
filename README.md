<h1>SOC Automation Lab</h1>

<h2>Description</h2>
In this lab we will cover SOC Automation Project. Starts with setting up a Security Operations Center (SOC) automation project (home lab). We will be using EDR like Wazuh and TheHive as Security Incident Response Solutions as well, We will be also using Shuffle as SOAR platform and Mimikatz as an exploit on Microsoft Windows that extracts passwords stored in memory and software that performs that exploit. Here we will explore how automation enhances incident response, accelerates threat detection, and streamlines SOC workflows.
<br />


<h2>Languages and Utilities Used</h2>

- <b>VirtualBox</b> 
- <b>Wazuh</b>
- <b>TheHive</b>
- <b>Shuffle</b>
- <b>Java</b>
- <b>Cassandra</b>
- <b>Elasticsearch</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Ubuntu 22.04 LTS</b> (21H2)

   
<h2>Program walk-through:</h2>

<p align="center">
SOC-Automation-Project-Diagram: <br/>
<img src="https://i.imgur.com/PAh7zq9.png" height="80%" width="80%" alt="SOC-Automation-Project-Diagram"/>
<br />
<br />
Download and install VirtualBox:  <br/>
<img src="https://i.imgur.com/gk8vVNB.jpg" height="80%" width="80%" alt="Download and install VirtualBox"/>
<br />
<br />
Downloading Windows 10 ISO: <br/>
<img src="https://i.imgur.com/yJWTrXe.jpg" height="80%" width="80%" alt="Downloading Windows 10 ISO"/>
<br />
<br />
Sysmon install on Windows:  <br/>
<img src="https://i.imgur.com/aZABJrL.png" height="80%" width="80%" alt="Sysmon install on Windows"/>
<br />
<br />
Create Wazuh and TheHive servers on Digital Ocean Cloud:  <br/>
<img src="https://i.imgur.com/z66DLp0.png" height="80%" width="80%" alt="Create Wazuh and TheHive servers on Digital Ocean Cloud"/>
<br />
<br />
Configure Wazuh Agent on Windows:  <br/>
<img src="https://i.imgur.com/arAHPij.png" height="80%" width="80%" alt="Configure Wazuh Agent on Windows"/>
<br />
<br />
Install Mimikatz on Windows:  <br/>
<img src="https://i.imgur.com/3rwVygt.png" height="80%" width="80%" alt="Install Mimikatz on Windows"/>
<br />
<br />
Captured mimikatz logs using Wazuh:  <br/>
<img src="https://i.imgur.com/7GdndeS.png" height="80%" width="80%" alt="Captured mimikatz logs using Wazuh"/>
<br />
<br />
Shuffle-Workflows Creation:  <br/>
<img src="https://i.imgur.com/eEsb7V3.png" height="80%" width="80%" alt="Shuffle-Workflows Creation"/>
<br />
<br />
Mimikatz Usage Detection on TheHive:  <br/>
<img src="https://i.imgur.com/7JvuSAa.png" height="80%" width="80%" alt="Mimikatz Usage Detection on TheHive"/>  
<br />
<br />
Testing rules on Wazuh:  <br/>
<img src="https://i.imgur.com/s2dOI57.png" height="80%" width="80%" alt="Testing rules on Wazuh"/> 

  
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
