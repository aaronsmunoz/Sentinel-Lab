# Sentinel-Lab
<h1>Failed RDP to IP Geolocation Information</h1>
<h2>Description</h2>
<b>This repository's Powershell script is in responsible of extracting information from Windows Event Log about unsuccessful RDP attempts and using a third-party API to get geographic data about the attackers' location.
</b>
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on a Azure Sentinel Map!
<br />
<br />

</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API
