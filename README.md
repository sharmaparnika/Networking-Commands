# Networking Commands

## 1.	Ipconfig

Description:

Indispensable and frequently used utility that is used for finding network information about your local machine-like IP addresses, DNS addresses etc 

Basic Use: 

Finding Your IP Address and Default Gateway Ip config has a number of switches the most common are: 

• ipconfig /all – displays more information about the network with MAC address. 

• ipconfig /release – release the current IP address.

• ipconfig /renew – renew IP address 

• ipconfig /? -shows help 

• ipconfig/flushdns – flush the dns cache

Example: ipconfig/all

![image](https://user-images.githubusercontent.com/73773202/156869762-5451dd0c-fb63-4833-b242-e3ff7272c5a9.png)

## 2.	Ping Command-

Description:

The ping command is one of the most often used networking utilities for detecting devices on a network and for troubleshooting network problems.
When you ping a device you send that device a short message, which it then sends back (the echo).

Syntax:  ping hostname or ping IP - address.

Example: ping www.google.com or ping 216.58.208.68

![image](https://user-images.githubusercontent.com/73773202/156869827-24d2dbe3-b506-4ba4-a7e3-53741eeea49b.png)

## 3.	Hostname Command-
Description:

It is used to obtain the DNS(Domain Name System) name and set the system's hostname or NIS(Network Information System) domain name. A hostname is a name which is given to a computer and it attached to the network. Its main purpose is to uniquely identify over a network. 

Syntax: hostname 

Example: hostname

![image](https://user-images.githubusercontent.com/73773202/156869976-2a2b5e8a-89d2-4755-80bb-6e03d6ec5b89.png)

## 4. getmac Command- 

Description:

Getmac is a Windows command used to display the Media Access Control (MAC) addresses for each network adapter in the computer. 

Syntax: getmac

Example: getmac

![image](https://user-images.githubusercontent.com/73773202/156870904-66d9ce06-82ed-4474-adb2-412c9cddc8ad.png)

## 5.	arp Command- 

Description:
This is used for showing the address resolution cache. This command must be used with a command line switch arp -a is the most common. 

Example: arp -a

![image](https://user-images.githubusercontent.com/73773202/156870934-665942c4-d17c-4610-a491-97042c5fe460.png)

## 6.	NetStat- 

Description:

Netstat is a Common TCP – IP networking command-line method present in most Windows, Linux, UNIX, and other operating systems. The netstat provides the statistics and information in the use of the current TCP-IP Connection network about the protocol. It will give the information of all the Active Connections. 

Example1: netstat
 
 ![image](https://user-images.githubusercontent.com/73773202/156870973-f2a95ce8-aeab-49c9-96f2-4f958c696f47.png)

Example2: netstat -r

![image](https://user-images.githubusercontent.com/73773202/156871032-293db0bb-c976-43fa-afef-68ce6229c4be.png)

## 7.	Nslookup- 

Description:

The Nslookup, which stands for name server lookup command, is a network utility command used to obtain information about internet servers. It provides name server information for the DNS (Domain Name System), i.e., the default DNS server’s name and IP Address. 

Example:

![image](https://user-images.githubusercontent.com/73773202/156871156-05a93a6b-bd04-427e-971b-bdc06a9a8e39.png)


## 8.	Route-

Description:

In IP networks, routing tables are used to direct packets from one subnet to another. The Route command provides the device’s routing tables. To get this result, just type route print. The Route command returns the routing table, and the user can make changes by Commands such as Route Add, Route Delete, and Route Change, which allows modifying the routing table as a requirement.

Syntax: Route

Example: Route

![image](https://user-images.githubusercontent.com/73773202/156871234-0e11d05b-a3b2-441a-916c-460267c5f916.png)

## 9.	Tracert 

Description: The tracert command is a Command Prompt command which is used to get the network packet being sent and received and the number of hops required for that packet to reach to target. 

Syntax: tracert [-d] [-h MaxHops] [-w TimeOut] target 

Example: tracert www.google.com

![image](https://user-images.githubusercontent.com/73773202/156871292-cf4a1acf-dfbe-40ec-aef3-eefdb0d0c59f.png)

## 10.	Nbtstat 

Description: Nbtstat is designed to help troubleshoot NetBIOS name resolution problems. 

Syntax: nbtstat < -a (name)> < -A (IP-address)> < -c>< -n> <-r> <-R><-RR> <-S> <-s> 

Example: nbtstat 

![image](https://user-images.githubusercontent.com/73773202/156871328-51261316-9207-4225-a8ae-742977ba94d3.png)

---
