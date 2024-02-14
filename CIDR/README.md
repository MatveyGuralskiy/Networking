# ✂️ CIDR Notation

It's shortened form of writing **IP Address + Subnet Mask**

Example: IPv4: 192.168.100.10 **/24**

CIDR Notation in this example is "/24"

* You should convert IP address to binary number for CIDR format

* The number in CIDR means how many number 1, we have in Subnet mask
<br>

## &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  **192.168.100.10 &nbsp; /24**

* 192 equal to 11000000
* 168 equal to 10101000
* 100 equal to 01100100
* 10 equal to 00001010

  
* So IP Address 192.168.100.10 equal to 11000000.10101000.01100100.00001010
  
We have in this IP Address 24 times number 1:

11111111.11111111.11111111.00000000

## &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  **0.0.0.0 &nbsp; /0**
All addresses of TCP/IP use in Route Table or Firewall Rules, for example: local network usage

<br>

* To check Subnet mask from CIDR go to Wikipedia:

   Classless Inter Domain Routing
