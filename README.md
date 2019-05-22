## OSI Model 7 layers by @Anakein

![OSI7](https://www.cloudflare.com/img/learning/ddos/what-is-a-ddos-attack/osi-model-7-layers.svg)

## Table of Contents
- [Layer 1](#layer-1)
- [Layer 2](#layer-2)
- [Layer 3](#layer-3)
- [Layer 4](#layer-4)
- [Layer 5](#layer-5)
- [Layer 6](#layer-6)
- [Layer 7](#layer-7)

## Layer 1

- Fiber Optics
- TX/RX
- Cat 5
- Wifi
- Twisted Pair, Coax,

## Layer 2

- MAC Flooding
- MAC Spoofing
- MAC Duplicating
- ARP Poisoning
- ARP Spoofing
- Man-In-The-Middle

**Switches / Hubs**

- Foot printing / Fingerprinting
- Extract MAC Address
- Password Guessing Attacks
- Man-In-The-Middle
- Spoofing MAC
- Wan Encapsulations
- X.25, Frame Relay, HDLC, SDLC, ISDN BRI, ISDN PRI
- VPN
- L2f, L2TP, PPTP
- NDIS

## Layer 3

- Foot printing / Fingerprinting
- Extract IP Addresses
- Router Password Guessing
- Man-In-The-Minddle
- Spoof IP Address
- IP

**IPSec**

- AH
- ESP
- Oakley, ISAKMP, IDE

**Routing Protocols**

- RIP
- OSPF
- IGRP
- BGP
- EGP
- HSRP
- ICMP

**Smurf Attack** - Broadcast address, spoofed source address, lage packet.
Ping of Death - Large Fragmented packet (>65000)

Routers

**Tools**

- Nmap
- Netcat
- hping

## Layer 4

**TCP**

- SRAF UP [FLAGS]

To learn how this works, record a conversation in `Wireshark` and then play the stream back and watch the flags change from source destination

![flags](https://raw.githubusercontent.com/e-anakein/OSI-Model/master/images/ws-tcp-analysis.png)

- Session Hijacking
- TCP Sequence Number Prediction
- Syn Flooding with spoofed IP source address
- Man-In-The-Middle

- Netstat 

**UDP**
Fraggle

Commonly Targeted Protocols **(TCP/UDP)**

## Layer 5

- SQL Injection
- RPC
- NFS
- SMB

Commonly Targeted Protocols **(SQL, NFS, RPC)**

## Layer 6

- File Type Conversions
- Encoding / Decondig
- Encryption / Decryption
- HEX Editing
- Change File Type

Commonly Targeted Protocols **(.html, .doc, .php, .xml, .txt, .mp3, .wav)**

## Layer 7

- Use of Stolen Login Credentials
- Exploitation of backdoor / Command Control
- Brute Force and Dictionary
- OS Commanding
- Default Passowrd / Configs
- Foot printing / Fingerprinting
- Cross Site Scripting
- Extract Usernames or Accounts
- DNS POisoning
- DHCP Starvation
- Service Flood Requests
- Application Hijacking
- Tools
   - Back orifice, Netcat, tini, NetBus, FU, Brutus, etc
- Maintain Access with Backdoors
- Rootkits and Trojans
- Data Modification Attacks
- Password Guessing attacks
- Man-In-The-Middle
- Identify Spoofing

- Exploitation of Authentication
      - Replay Attacks
- Exploitation of Insuffcient Authorization 
- Man-In-The-Middle
- URL Obfuscation
- Buffer Overflows

Commonly Targeted Protocols **(HTTP, POP3, SMTP, IMAP, DNS)** https://en.wikibooks.org/wiki/Network_Plus_Certification/Technologies/Common_Protocols

Source: https://www.youtube.com/watch?v=CjVgWOviYiU&feature=youtu.be
