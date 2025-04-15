Beginning stages

- In our quest to understand Wireshark, we have installed Kali on a virtual machine (Windows). Jazlyn set up GNOME (GNU Network Object Model Environment) on Windows through Oracle Virtual Box, but it did not include Wireshark.  
 
- So we troubleshooted the terminal visited the root directory location /etc/apt/sources. List  found it empty, so added the source link : deb http://http.kali.org/kali kali-rolling main-free contrib updated using sudo apt update.


- After installing Kali VBOX, we captured some traffic and analyzed it and saved it.

- Wireshark is running on individual laptops, capturing network traffic, we will continues normal activities while Wireshark monitors traffic in the background. 

Wireshark is being utilized on separate laptops to capture network traffic. While it operates in the background, normal activities will continue uninterrupted, allowing for simultaneous monitoring and usage. This setup enables effective traffic analysis without disrupting everyday tasks.


- Over the weekend 3/28 we are both going to do research how to analyze our packets we just found out about air crack-ng that will help with that.

Where we at

We connected Fayaz VM to Jazlyn VM and replicated the same step-up to my own.
- Jazlyn IP address : 10.245.56.153/21
- Fayaz IP address : 10.245.56.38/21
 
- SSH has remote access to another system securely over a network.
ex code: ssh jazlyn@remote-ip

- Opening Wireshark, starting capture and doing the process web browsing then ping some websites Downloading somethings, SSH into Another machine using their passwords.

- After sometimes we will stop the capture and start analyze some packets, for analyze Statistics TO Protocol Hierarchy to see what protocols are present.

Then Examine Packet Details :
 - Use Traffic : HTTP
- ICMP (ping) Responses : icmp
- Traffic from your IP: .ip.addr = = YOUR_IP
- SSH and FTP we need to install FTP 

We have installed tcp 

4/15 - Jazlyn has kind of analyze tcp Instructions :
edit - Preferences
Protocols - IEEE802.11
enable decryption
click on edit
Add a new key
Dropdown : -wpa-pwk or wep
type password123 or any password
click save
AFTER THAT
filters : http, tcp, dns ( Right click on packets)
Click Follow tcp stream 
You will see all the communications going on from that packet.








