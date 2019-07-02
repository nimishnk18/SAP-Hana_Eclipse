# SAP-Hana_Eclipse

Steps to setup the SAP HANA Studio on Eclipse:

1) First check your system type (32 bit/ 64 bit). For that Click on Windows Icon  <img width="18" alt="icon" src="https://user-images.githubusercontent.com/30903014/60544011-06596600-9cd5-11e9-9a72-5b457ebb5f34.PNG">
 -> Settings -> System -> About
<br> <br>
<img width="918" alt="1" src="https://user-images.githubusercontent.com/30903014/60542667-b4631100-9cd1-11e9-8262-9923101ba0ca.png">

<br><br>
2) Download the required Eclipse version for 32/64 bit version.
<br> For example:
http://www.eclipse.org/downloads/packages/eclipse-ide-java-developers/oxygen2
<br><br>
![2](https://user-images.githubusercontent.com/30903014/60541082-fe49f800-9ccd-11e9-9ebd-c694b0a8a5a8.png)
<br><br>

3) Unzip your downloaded Eclipse version and start Eclipse.

4) Select your workspace
<br><br>
![3](https://user-images.githubusercontent.com/30903014/60541092-073ac980-9cce-11e9-9aa5-abcee70c1bda.png)
<br><br>

5) Change proxy configuration in Eclipse (Windows > Preferences > General > Network Connections) for:
	Manual
	Server: proxy.jbssa.com
	Port: 8080
	Login & Password are your AD credentials
	
 <br><br>
 ![12](https://user-images.githubusercontent.com/30903014/60541163-32bdb400-9cce-11e9-9b74-4a0f16c2f6c4.png)
<br><br>
![13](https://user-images.githubusercontent.com/30903014/60541169-36513b00-9cce-11e9-98c6-01d67df17df5.png)
<br><br>
![14](https://user-images.githubusercontent.com/30903014/60541178-3a7d5880-9cce-11e9-8742-f0156ec6d389.png)
<br><br>	

6) Configure HANA Servers
	<br>
	Ustxribwhdbd – Port: 01
	<br>
	ustxribwhdbq – Port: 10
	<br>
	ustxcrbwhdbi – Port: 50

7) Install SAP Tools (Help > Install New Software wizard of Eclipse)
 Location http://tools.hana.ondemand.com/oxygen
	<br><br>
![4](https://user-images.githubusercontent.com/30903014/60541103-0c981400-9cce-11e9-8d95-553f9e8ceeac.png)
<br><br>
![5](https://user-images.githubusercontent.com/30903014/60541115-115cc800-9cce-11e9-9cac-1b45c74ca3e5.png)
<br><br>
![6](https://user-images.githubusercontent.com/30903014/60541119-1588e580-9cce-11e9-9a61-4eac26ab8693.png)
<br><br>
Install ABAP, BW and HANA tools
<br><br>
![7](https://user-images.githubusercontent.com/30903014/60541131-1de12080-9cce-11e9-8e07-8790e6eadd97.png)
<br><br>
  
8) Installation Overview
<br><br>
![8](https://user-images.githubusercontent.com/30903014/60541142-22a5d480-9cce-11e9-954b-c0ad9fd9d4e4.png)
 <br><br>

9) Download and install the software
<br><br>
![9](https://user-images.githubusercontent.com/30903014/60541147-26d1f200-9cce-11e9-9f81-7f3eb9c6b21e.png)
<br><br>

10) Restart your eclipse

11) How to change the perspective?
 
 If you install several tools, you can switch the perspective

 ![10](https://user-images.githubusercontent.com/30903014/60541155-2b96a600-9cce-11e9-95de-5ba889483980.png)

Select a perspective
<br><br>
![11](https://user-images.githubusercontent.com/30903014/60541158-2f2a2d00-9cce-11e9-9dcc-1903f5fb035a.png)
<br><br>

<b> Good Work! You have successfully setup the SAP HANA Studio on Eclipse.


