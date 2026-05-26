# OSI Model  
## What it is  
The OSI (Open Systems Interconnection) model is a reference model that explains how computers communicate over a network.  
## How many layers it has  
It has 7 layers.  
## How it is organized  
From lowest to highest:  
1. Physical — cables, signals, hardware  
2. Data Link — MAC addresses, switches  
3. Network — IP addresses, routing  
4. Transport — TCP/UDP, ports  
5. Session — manages communication sessions  
6. Presentation — encryption, compression, formatting  
7. Application — services used by applications (HTTP, FTP, DNS, etc.)  

# What is a LAN  
A LAN (Local Area Network) is a network that connects devices in a small local area.  
## Typical usage  
- Home networks  
- Schools  
- Offices  
- Small businesses  
## Typical geographical size  
Localy, like in one room or building.

# What is a WAN  
A WAN (Wide Area Network) connects multiple LANs over large distances.  
## Typical usage  
- Connecting company offices in different cities/countries  
- Internet service providers  
- The Internet itself  
## Typical geographical size  
Global, like a city, country or even worldwide.  

# What is the Internet  
The Internet is a global network of interconnected computers and networks that communicate using IP protocols.  
## What is an IP address  
An IP address is a unique number assigned to a device on a network so it can be identified and communicate.  
## What are the 2 types of IP address  
- 32-bit address: 192.168.1.1  
- 128-bit address: 2001:0db8:85a3::8a2e:0370:7334  
## What is localhost  
localhost refers to the current computer itself.  
## What is a subnet  
A subnet is a smaller division of a network.  
## Why IPv6 was created  
IPv6 was created because:  

- IPv4 addresses were running out  
- More devices needed Internet access  
- IPv6 provides a much larger address space  

# TCP/UDP  
## What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)  
At the Transport layer of the OSI model:  
- TCP (Transmission Control Protocol)  
- UDP (User Datagram Protocol)  
## What is the main difference between TCP and UDP  
TCP:  
- Reliable  
- Connection-oriented  
- Checks errors and packet order  
- Slower  
Used for:  
- Web browsing  
- File transfers  
- Emails  

UDP:  
- Faster  
- Connectionless  
- No guarantee of delivery  
- Less overhead  
Used for:  
- Video streaming  
- Online gaming  
- VoIP  
## What is a port  
A port is a logical communication endpoint used by applications/services on a device.  
## Memorize SSH, HTTP and HTTPS port numbers  
SSH: 22  
HTTP: 80  
HTTPS: 443  
## What tool/protocol is often used to check if a device is connected to a network  
ping  
