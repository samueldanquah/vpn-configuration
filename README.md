<p align="center">
![download](https://github.com/samueldanquah/vpn-configuration/assets/153206496/d6f0e8a7-1a5d-4c46-a0a2-4ca962472061)
</p>

<h1>Azure VM and VPN Geographic Experiment</h1>
This experiment outlines the steps for setting up an Azure VM in a different geographic location, using a VPN to simulate web access from various countries, and observing the changes in web content based on IP geolocation.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN
- Web Browsers

<h2>Operating Systems Used </h2>

- Windows 10

<h2>Project Objectives</h2>

- Create and connect to an Azure VM in a different geographic location.
- Use a VPN to simulate access from various countries.
- Observe changes in web content based on IP geolocation.

<h2>Project Steps and Observations</h2>

<h3>Creating a Virtual Machine in Azure:</h3>
<ul>
    <li>Created a new Resource Group in Azure.</li>
    <li>Deployed a Windows 10 Virtual Machine in a different country.</li>
    <li>Logged into the VM using Remote Desktop and visited https://whatismyipaddress.com/ to note the IP address.</li>
</ul>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Azure VM Setup"/>
</p>
<p>
    This step was crucial for understanding how geographic location impacts IP addresses and web content delivery.
</p>
<br />

<h3>Setting Up and Testing ProtonVPN:</h3>
<ul>
    <li>On my actual computer, signed up for the free version of Proton VPN.</li>
    <li>Within the Azure VM, downloaded and installed the Proton VPN client.</li>
    <li>Connected to a VPN server in a different country (e.g., Japan) and observed the change in IP address on https://whatismyipaddress.com/.</li>
    <li>Explored how websites like Google, Disney, and Amazon differed in content presentation based on the VPN server’s location.</li>
</ul>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="VPN Testing"/>
</p>
<p>
    This experiment highlighted the influence of VPNs on web browsing, especially in terms of content localization and IP address masking.
</p>
<br />

<!-- Footer or additional notes -->

