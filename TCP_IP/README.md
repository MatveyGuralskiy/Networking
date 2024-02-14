# 💡 **TCP/IP**
**TCP/IP**= is a set protocols designed to transmit data over computer networks, including the Internet


**TCP**= ensures(guaranteed) that data is delivered correctly


**IP**= indicates where to send them


**IP Address**= unique confidential number for device


<br> We have two types of **IP Addresses**:

IPv4 : 
          *192.168.100* .10  
          *Subnet ID:* Numbers between 0-255
          Host ID:Numbers between 1-254
<br>
Subnet Mask: 255.255.255.0    &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   Numbers between: 0-255(0-254)
<br>
<br>
 **Subnet ID** is like a number or address that tells you where in the network a computer or device is located.
<br>
 **Subnet mask** is like a set of instructions that tells a computer how to divide an IP address into two parts: one part identifies the subnet and the other part identifies the specific device in that subnet.
<br>
 **Host ID** is like a number or address that tells you which specific device or computer within the subnet is using that IP address.
In Host ID numbers: 0 and 255 doesn't use (doesn't exist for user usage) because number 0 is the base IP of IP Address. 
<br> Number 255 is a broadcast ID  

<br>

* If you want to take a lot of devices in one network, you should have the same Subnet ID and Subnet Mask.

  Host ID will be different for every device
<br>
Address of your computer (**local or localhost**):    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;127.0.0.1

It can also will show you if protocols TCP/IP work

Commands to check **IP Addresses**:

Linux: &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ifconfig
<br> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  ip addr
<br> Windows:  <br> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ipconfig
 
