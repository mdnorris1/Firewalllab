# Firewall lab
You work as the IT security administrator for a small corporate network. You recently placed a Web server in the demilitarized zone (DMZ). You need to configure the perimeter firewall on the network security appliance (pfSense) to allow access from the WAN to the Web server in the DMZ using both HTTP and HTTPs. You also want to allow all traffic from the LAN network to the DMZ network.

In this lab, your task is to:

Access the pfSense management console:
Username: admin
Password: P@ssw0rd (zero)
Create and configure a firewall rule to pass HTTP traffic from the WAN to the Web server in the DMZ.
Create and configure a firewall rule to pass HTTPS traffic from the WAN to the Web server in the DMZ.
Use the following table when creating the HTTP and HTTPS firewall rules:
Parameter	Setting
Source	WAN network
Destination port/service	HTTP (80), HTTPS (443)
Destination	A single host
IP address for host	172.16.1.5
Descriptions	For HTTP: HTTP from WAN to DMZ
For HTTPS: HTTPS from WAN to DMZ
Create and configure a firewall rule to pass all traffic from the LAN network to the DMZ network. Use the description LAN to DMZ Any.



https://github.com/mdnorris1/Firewalllab/assets/147259516/137b8a40-87b9-4382-9df5-ad7b0a2b34ef


You are the IT administrator for a small corporate network. You want to make a web server that runs services accessible from the internet. To help protect your company, you want to place this server and other devices in a demilitarized zone (DMZ). This DMZ and server need to be protected by the pfSense Security Gateway Appliance (pfSense). Since a few of the other devices in the DMZ require an IP address, you have also decided to enable DHCP on the DMZ network.

In this lab, your task is to perform the following:

Access the pfSense management console:
Username: admin
Password: P@ssw0rd (zero)
Add a new pfSense interface that can be used for the DMZ.
Name the interface DMZ.
Use a static IPv4 address of 172.16.1.1/16.
Add a firewall rule for the DMZ interface that allows all traffic from the DMZ.
Use a description of Allow DMZ to any rule.
Configure and enable the DHCP server for the DMZ interface.
Use a range of 172.16.1.100 to 172.16.1.200.




https://github.com/mdnorris1/Firewalllab/assets/147259516/d7e14b7b-1e0e-4f16-8bce-5941ec32d9ae



This lab was part of my CompTIA Cyber Ready programme.
