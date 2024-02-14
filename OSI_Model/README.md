# 📟 OSI Model
OSI model is a conceptual framework(base) that divides network communications functions into seven layers

7 layers or 7 levels

*System administrator* works with first 4 layers

*Software engineer* works with 3 layers upper

## 🍰 Seven layers
### 💪🏼 First layer = Physical

Connect electricity, cables, ethernet connection, Bluethooth, WI-FI

Network Devices of this level it's Hub and Repeater

Hub it's simple network device with ethernet connections


### 🔗 Second layer = Data link

We have some signal, now we need to convert him to bytes

In this layer we scanning and checking the transmission errors

Frame = a structure containing some information

Framing is a function of the data link layer. 

It provides a way for a sender to transmit a set of bits that are meaningful to the receiver.


### 📶 Third layer = Network

It manages the routing of data on a network, ensuring(make sure) that data is delivered from a sender to a recipient through multiple nodes


### 🚛 Fourth layer = Transport

On this layer ensures reliable(safety) and orderly transfer of data between devices

We have 2 protocols on that layer: *TCP and UDP*

*TCP* = reliable delivery

*UDP* = faster, but unreliable delivery

### 🕓 Fifth layer = Session

This layer manages communication sessions, he breaks sessions

Example: breaks codecs sessions of ZOOM

### 🗣 Sixth layer = Presentation

Here data convert to the format, that understandable for applications 

Example: like GIF, JPEG he converts bytes to IMAGE

It can be include compression, encryption and other data manipulations

### 🧩 Seventh layer = Application

This layer give you interface to work with applications

For example protocols: HTTP, HTTPS, FTP, SMTP
