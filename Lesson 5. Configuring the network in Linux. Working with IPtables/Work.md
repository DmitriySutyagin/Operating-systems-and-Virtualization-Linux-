# Lesson 5. Configuring the network in Linux. Working with IPtables 

* Set up a static configuration (without DHCP) in Ubuntu via ip and netplan.
Configure the IP, default route, and DNS servers (1.1.1.1 and 8.8.8.8).
Check the network performance.

![Screnshot](/ScreenShot/Lesson_5.Tincture%20of%20the%20static%20configuration%20of%20the%20linux_net..png)
![Screnshot](/ScreenShot/Lesson_5.Network%20diagnostics.Part_1..png)
![Screnshot](/ScreenShot/Lesson_5.Network%20diagnostics.Part_2.png)

* Configure iptables rules for the availability of services on TCP ports 22, 80 and 443.
The server must also be able to establish connections to the update server.
Prohibit all other connections.
*Prohibit any incoming traffic from IP 3.4.5.6.

* Redirect requests to port 8090 to port 80 (on the same server).

* Allow SSH connection only from the 192.168.0.0/24 network.

![Screnshot](/ScreenShot/Lesson_5.Other.png)