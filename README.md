<h1>MSFvenom - Android Package Kit </h1>

 ### [YouTube Demonstration](https://youtu.be/GiODh2SpzTw)

<h2>Description</h2>
MSFvenom is a powerful and versatile tool that is part of the Metasploit Framework, a widely used penetration testing and exploitation toolkit. This tool allows security professionals and ethical hackers to generate custom payloads quickly and efficiently for various purposes, such as remote code execution, reverse shell connections, and other cyberattack simulations. MSFvenom's primary function is to create malicious payloads that can be used for penetration testing and vulnerability assessments.

<br />Here's a description of how to use MSFvenom to create a malicious payload for Android devices:


<h2>Tools Used </h2>

- <b>Kali Linux</b>
- <b>MSFvenom</b>
- <b>Android Phone</b>
- <b>Android Packaging Kit (APK)</b>
- <b>QR Code Generator</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch Kali Linux, open terminal and run MSFvenom: <br/>
<img src="https://i.imgur.com/J28oKqx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter flags to create APK file :  <br/>
<img src="https://i.imgur.com/8t5JRX2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Start Apache web service: <br/>
<img src="https://i.imgur.com/XmxA79e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch msfconsole from terminal:  <br/>
<img src="https://i.imgur.com/OdowDDg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure listener with payload and options:  <br/>
<img src="https://i.imgur.com/tVIHNrf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/NMRCXxF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create QR code using attacker IP address and APK file  (QR-code-generator.com):  <br/>
<img src="https://i.imgur.com/G96Wn4Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Exploit device using commands: (examples: sysinfo, dump_sms, send_sms, geolocate) <br/>
<img src="https://i.imgur.com/u9KT6DD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/kevFvtT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />





</p>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
