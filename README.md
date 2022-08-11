# Net-Practice
a System Administration related exercise

## What Is TCP/IP? 
Transmission Control Protocol/Internet Protocol (TCP/IP) is a protocol system—a collection of protocols that supports network communications. 
- TCP/IP carefully defines how information moves from sender to receiver. First, application programs send messages or streams of data to one of the Internet Transport Layer Protocols, either the User Datagram Protocol (UDP) or the Transmission Control Protocol (TCP). These protocols receive the data from the application, divide it into smaller pieces called packets, add a destination address, and then pass the packets along to the next protocol layer, the Internet Network layer.
- The Internet Network layer encloses the packet in an Internet Protocol (IP) datagram, puts in the datagram header and trailer, decides where to send the datagram (either directly to a destination or else to a gateway), and passes the datagram on to the Network Interface layer.
- The Network Interface layer accepts IP datagrams and transmits them as frames over a specific network hardware, such as Ethernet or Token-Ring networks.

### Network
A network is a collection of computers or computer-like devices that can communicate across a common transmission medium. Often the transmission medium is an insulated metal wire that carries electrical pulses between the computers, but the transmission medium could also be a phone line, or even no line at all in the case of a wireless network.
### Network protocol
A network protocol is a system of common rules that helps define the complex process of network communication. Protocols guide the process of sending data from an application on one computer, through the networking components of the operating system, to the network hardware, across the transmission medium, and up through the destination computer’s network hardware and operating system to a receiving application 

###  Routing 
A router is a special device that can read logical addressing information and direct data across the network to its destination. At the simplest level, a router divides a local subnet from the larger network.

### IP Addressing
An IP address is a 32-bit binary address. This 32-bit address is subdivided into four 8-bit segments called octets. Humans do not work well with 32-bit binary addresses or even 8-bit 
binary octets, so the IP address is almost always expressed in what is called dotted-decimal format. In dotted-decimal format, each octet is given as an equivalent decimal number. The four decimal values (4 × 8 = 32 bits) are then separated with periods. Eight binary bits can represent any whole number from 0 to 255, so the segments of a dotted-decimal address are decimal numbers from 0 to 255. You have probably seen examples of dotted-decimal IP addresses on your computer, in this book, or in other TCP/IP documents. A dotted-decimal IP address looks like this: 209.121.131.14.
Part of the IP address is used for the network ID, and part of the address is used for the host ID. As you learned earlier in this hour, the original scheme for specifying the network and host ID is through a system of address classes. Although the more recent CIDR classless addressing has reduced the importance of the class system, address classes are still important enough to describe here as a starting point for understanding addressing in TCP/IP. 
### Address Class: 
 A classification system for IP addresses. The network class determines how the address is subdivided into a network ID and host ID.
 ![image](https://user-images.githubusercontent.com/79755743/184171658-b984152c-f63e-4564-a394-fdc1712f9565.png)
![image](https://user-images.githubusercontent.com/79755743/184171720-acf3e307-0fc4-402f-891d-1c4f9a13a6c2.png)
![image](https://user-images.githubusercontent.com/79755743/184171800-043a65a0-c774-441b-b152-2707cbee6a3e.png)
![image](https://user-images.githubusercontent.com/79755743/184171893-10d4f6cc-cb95-4dd3-8085-d4d274b9dcf6.png)

 ## Resources 
 
- Networking With Microsoft Tcp/Ip: Certified Administrator's Resource Edition Har/Cdr Edition by Drew Heywood and Rob Scrimger 
- Sams teach yourself TCP/IP in 24 hours Book by Joe Casad
- TCP/IP network administration Book by Craig Hunt
- https://www.open.edu/openlearncreate/mod/oucontent/view.php?id=129584&printable=1
- https://github.com/ifanzilka/NetPractice
- https://velog.io/@mseo/NetPractice-과제-해석
- https://velog.io/@mseo/NetPractice-과제를-위한-기초학습
- https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=dreamxpeed&logNo=221671848467
- https://note.com/syamashi/n/n57fc506e0c5c
- https://www.ibm.com/docs/en/aix/7.1?topic=protocol-tcpip-protocols
- https://www.freecodecamp.org/news/subnet-cheat-sheet-24-subnet-mask-30-26-27-29-and-other-ip-address-cidr-network-references/
- https://www.coursera.org/learn/computer-networking/lecture/vdyzA/subnet-masks
- https://hackr.io/blog/subnet-cheat-sheet
- https://bigpel66.oopy.io/library/42/inner-circle/2
