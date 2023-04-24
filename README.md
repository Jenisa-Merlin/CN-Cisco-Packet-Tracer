# CN-Cisco-Packet-Tracer
Designing a Hotel Management System network using Cisco Packet Tracer

The hotel has 3 floors. In the first floor 3 departments (Reception, Store, and Logistics). In the 2nd floor there are 3 departments (Finance, HR and Sales). While the 3rd floor hosts the IT and Admin. 
1.	There should be 3 routers connecting each floor (all placed in the server room in IT department).
2.	All routers should be connected to each other using DCE cable.
3.	The network between the routers should be 10.10.10.0/30, 10.10.10.4/30, 10.10.10.8/30.
4.	Each floor is expected to have one switch (placed in the respective floor).
5.	Each floor is expected Wi-Fi networks connected to laptops and phones.
6.	Each department is expected to have a printer.
7.	Each department is expected to be in different VLAN with the following details.

1st Floor
•	Reception – VLAN 80, network of 192.168.8.0/24
•	Store – VLAN 70, network of 192.168.7.0/24
•	Logistics – VLAN 60, network of 192.168.6.0/24

2nd floor
•	Finance – VLAN 50, network of 192.168.5.0/24
•	HR – VLAN 40, network of 192.168.4.0/24
•	Sales – VLAN 30, network of 192.168.3.0/24

3rd Floor
•	Admin – VLAN 20, network of 192.168.2.0/24
•	IT – VLAN 10, network of 192.168.1.0/24


8.	Use OSPF as the routing protocol to advertise routes.
9.	All devices in the network are expected to obtain IP address dynamically with their respective router configured as the DHCP server.
10.	 All the devices in the network are expected to communicate with each other.
11.	 Configure SSH in all the routers for remote login.
12.	 In IT department, add PC called Test-PC to port fa0/1 and use it to test remote login.
13.	 Configure port security to IT department switch to allow only Test-PC to access port fa0/1 (use sticky method to obtain MAC-Address with violation mode of shut down). 

