In the name of God

# Bavin - Realtime StackedUI Packet Analyzer for Students

Bavin is a packet analyzer like `wireshark` which will breakdown each in/out packets from any network interface in your computer, but it will decipher the packets in a more readable and senseble `TCP/IP` Protocol Stack, so you will be able to read what is happening in each packet and it's headers in the most simplest and efficient way.

## Goal
One of the main reason behind the development of this app is to everyone can understand and learn better the **TCP/IP** Protocols in action based on `IETF` in the sense of **Stacked Protocol in UI** especially diffrent headers of each famous protocols.

<img width="600px" src="https://github.com/SeyyedMahdiHP/MyOtherProjects/blob/master/PacketAnalyzer/GUIPacketAnalyzer(WithProtocolStack)/pktanz.PNG" alt="Realtime StackedUI Packet Analyzer - Listen Started "/>

## Protocols
This app supports 15 protocols:
- Ethernet
- IP
- IPV6
- ARP
- ICMP
- UDP
- TCP
- HTTP
- DNS
- NBNS
- LLMNR
- SSDP
- IGMP
- IGMPV6
- DHCP


## Requirements
- Windows
- Install [dotnetframework4](https://dotnet.microsoft.com/en-us/download/dotnet-framework)
- Install [Winpcap](https://www.winpcap.org/install/) Library


## How to Run

Just open the app and select one interface, then it will automatically listen to the all in/out packets and will show it to you.

Step1:
<br>
![alt text](https://github.com/SeyyedMahdiHP/MyOtherProjects/blob/master/PacketAnalyzer/GUIPacketAnalyzer(WithProtocolStack)/startup.PNG "Step1: Program Started")
<br>
Step2:
<br>
![alt text](https://github.com/SeyyedMahdiHP/MyOtherProjects/blob/master/PacketAnalyzer/GUIPacketAnalyzer(WithProtocolStack)/selectNIC.PNG "Select one NetworkCardInterface to start listening")
<br>
Step3:
<br>
![alt text](https://github.com/SeyyedMahdiHP/MyOtherProjects/blob/master/PacketAnalyzer/GUIPacketAnalyzer(WithProtocolStack)/pktanz.PNG "Listen Started")
