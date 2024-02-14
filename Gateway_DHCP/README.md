# 🔄 Gateway
A gateway in a computer network is a device or software that converts data between different network protocols or networks.
It acts as an intermediary, facilitating(helps to) communication between devices using different protocols or between devices in different network segments.
Gateways can perform routing functions, address translation, traffic filtering, and other tasks, ensuring efficient and secure network operation.

## 🏡 Demonstarion of Home Office Network

**PC-1** 192.168.1.100

**Samsung** 192.168.1.101
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  DHCP  &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 97.134.78.43

**PC-2** 192.168.1.102 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **+** &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **Router** <-----------------> **Internet**

**Iphone** 192.168.1.103
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;192.168.1.1

**Laptop** 192.168.1.104

## ❗ Explanation of Demonstraion

* Your **Router** connects to the Internet and he gets some IP Address (97.134.78.43), It called Public IP

* The **Router** had Internal (*Local*) IP Address (192.168.1.1) and the Router gives to all devices which are connect to the WI-FI/Ethernet Address of IP Internal (they unique IP Address)

* To do this function Router should use **DHCP** Protocol

* You can connect for example in one time to the Router 254 unique devices

* After some time if, PC (Some device) doesn't use Router, Router **will remove him** and give to someone else his IP Address
