# SAP-Hana_Eclipse

Steps to setup the SAP HANA Studio on Eclipse:
1)	Download Eclipse (32bit / 64bit):
a.	http://www.eclipse.org/downloads/packages/eclipse-ide-java-developers/oxygen2
2)	Change proxy configuration in Eclipse (Windows > Preferences > General > Network Connections) for:
a.	Manual
b.	Server: proxy.jbssa.com
c.	Port: 8080
d.	Login & Password are your AD credentials
3)	Install SAP Tools (Help > Install New Software wizard of Eclipse)
a.	https://tools.hana.ondemand.com/
b.	Install ABAP, BW and HANA tools
4)	Configure HANA servers
a.	Ustxribwhdbd – Port: 01
b.	ustxribwhdbq – Port: 10
c.	ustxcrbwhdbi – Port: 50
















I also found an YouTube video with the Step-by-Step, just make sure the proxy configuration (Step 3) was done before 3:10 min from the video.
https://www.youtube.com/watch?v=EemEcQdMUuk

Bonus video – How to configure proxy in Eclipse:

https://www.youtube.com/watch?v=4-XC5583bBA





First check your system type 32bit or 64 bit. Right-click on computer – prereferences
<br> <br>
<img width="918" alt="1" src="https://user-images.githubusercontent.com/30903014/60542667-b4631100-9cd1-11e9-8262-9923101ba0ca.png">

<br><br>
Download eclipse neon for 32-bit the x86 version and for 64-bit x64 version.
<br><br>
![2](https://user-images.githubusercontent.com/30903014/60541082-fe49f800-9ccd-11e9-9ebd-c694b0a8a5a8.png)
<br><br>

unzip your downloaded eclipse version and start eclipse.
if eclipse doesnt start please update to version 1.8+ – here

select your workspace
<br><br>
![3](https://user-images.githubusercontent.com/30903014/60541092-073ac980-9cce-11e9-9aa5-abcee70c1bda.png)
<br><br>

Download the SAP HANA Tools
<br><br>
![4](https://user-images.githubusercontent.com/30903014/60541103-0c981400-9cce-11e9-8d95-553f9e8ceeac.png)
<br><br>

![5](https://user-images.githubusercontent.com/30903014/60541115-115cc800-9cce-11e9-9cac-1b45c74ca3e5.png)

 
Location http://tools.hana.ondemand.com/oxygen
<br><br>
![6](https://user-images.githubusercontent.com/30903014/60541119-1588e580-9cce-11e9-9a61-4eac26ab8693.png)
<br><br>
choose your components
<br><br>
![7](https://user-images.githubusercontent.com/30903014/60541131-1de12080-9cce-11e9-8e07-8790e6eadd97.png)
<br><br>

Installation overview
<br><br>
![8](https://user-images.githubusercontent.com/30903014/60541142-22a5d480-9cce-11e9-954b-c0ad9fd9d4e4.png)
 <br><br>

download and install the software
<br><br>
![9](https://user-images.githubusercontent.com/30903014/60541147-26d1f200-9cce-11e9-9f81-7f3eb9c6b21e.png)
<br><br>

restart your eclipse


New possibilities after installing SAP HANA tools.

 
change perspective
 

if you install several tools you can switch the perspective

 ![10](https://user-images.githubusercontent.com/30903014/60541155-2b96a600-9cce-11e9-95de-5ba889483980.png)

select a perspective
<br><br>
![11](https://user-images.githubusercontent.com/30903014/60541158-2f2a2d00-9cce-11e9-9dcc-1903f5fb035a.png)
<br><br>

 proxy settings – if needed for example in a company network.
 <br><br>
 ![12](https://user-images.githubusercontent.com/30903014/60541163-32bdb400-9cce-11e9-9b74-4a0f16c2f6c4.png)
<br><br>
![13](https://user-images.githubusercontent.com/30903014/60541169-36513b00-9cce-11e9-98c6-01d67df17df5.png)
<br><br>
![14](https://user-images.githubusercontent.com/30903014/60541178-3a7d5880-9cce-11e9-8742-f0156ec6d389.png)
<br><br>
close preferences



in my case no. If you choose yes, you must always type the password when you starting eclipse


