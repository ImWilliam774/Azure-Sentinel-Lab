<h1>Failed RDP to IP Geolocation information</h1>

<h2>Description</h2>
The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Utilites Used </h2>

- <b>Windows 10 VM</b>
- <b>ipgeolocation.io</b> : IP Address to Geolocation API
- <b>Microsoft Azure</b>
- <b>Microsoft Sentinel</b>

<h2>Program walk-through:</h2>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
