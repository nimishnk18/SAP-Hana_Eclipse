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



