<h1>Browser Privacy</h1>



<h2>Description</h2>
Welcome!
In this tutorial, we're gonna go through setting up a secure and truly private browser without the concern of bad actors trying to steal your data or harvest your credentials. Whether it's survelliance, data exfiltration, or browsers not disclosing what type of cookies they use, it's good to make it a habit to have a zero trust policy and to indivdually improve your OPSEC. Let's get started... 
<br />


<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)
- <b>Firefox</b>
<h2>Program walk-through:</h2>

<p align="center">
 Open up a new broswer tab. Type "about:profiles" to create a new profile. Then access "about:config" within the new profile. <br>
<br />
<br />
  
![image alt](https://i.imgur.com/C2HBmLv.png)
<br />
<br />
![image_alt](https://i.imgur.com/8zL7byy.png)
<br />
<br />

<p align="center">
Enable Fingerprint Resisitance, which will toss the need for any fingerprint blocking addons.<br>
<br />
<br />
  
![image_alt](https://i.imgur.com/CW08iUx.png)
<br />
<br />

<p align="center">
Diable 3DES because of its known security flaws<br>
<br />
<br />
  
![image_alt](https://i.imgur.com/1PbE3w7.png)
<br />
<br />

<p align="center">
 Disable 0 round trip time to secure forward secrecy <br>
 
![image alt](https://i.imgur.com/QHJwHja.png)

<br />
<br />

<p align="center">
Disable Disk Caching
<b />
<b />
  
![image_alt](https://i.imgur.com/oqkXYzI.png)
<br />
<br />

<p align="center">
Disabe geolocation services
<b />
<b />
  
![image_alt](https://i.imgur.com/ESpssqN.png)
<br />
<br />

<p align="center">
Disabe plugin scanning to improve functionality, as some sites will scan for script & adblockers.
<b />
<b />
  
![image_alt](https://i.imgur.com/NIMNlza.png)
<br />
<br />

<p align="center">
Enable first-party isolation to prevent supercookies and browsers from making  requests outside of the primary domain of the website.
<b />
<b />
  
![image_alt](https://i.imgur.com/j7magbk.png)
<br />
<br />

<p align="center">
Disable TLS false start
<b />
<b />

![image_alt](https://i.imgur.com/3VRGSeP.png)
<br />
<br />

<p align="center">
Test your browsers privacy after you refresh the settings disabling and enabling features.
<b />
<b />
  
![image_alt](https://i.imgur.com/eJnZ7Yv.png)
