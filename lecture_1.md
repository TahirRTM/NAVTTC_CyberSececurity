# NAVTTC_CyberSececurity
## Nmap
## Burpsuite
## wireshark
## SQL Injection 
## installations
### step 1
[go to getkali](https://www.kali.org/)
### step 2
click vm ware download and download it
### step 3 
install vm ware


### what is cyber security
pratice to safe and protect your computer system from digital theft and or digital attacks
### CIA Triads:
1.Confidentiality 
2.Integrity 
3.Availibility
## Access Control:
Mandatory Access Control (MAC), Role-Based Access Control (RBAC), Discretionary Access Control (DAC), and Rule-Based Access Control (RBAC or RB-RBAC)

# TYpe of Attacks:
## Malware.....
malicious software
 Virus
Attach karta hai khud ko kisi legitimate file ke sath.
Jab wo file chalay jaati hai to virus activate ho jata hai.
Apne aap ko spread karta hai aur system resources (RAM) consume karta hai.
2. Worms
Ye ek standalone program hota hai.
Kisi file ke sath attach nahi hota — khud ka software hota hai.
Network ke zariye khud ko automatically spread karta hai (e.g., email contacts).
3. Trojan Horses
Legitimate software ban kar aata hai, par andar malicious code hota hai.
User ko lagta hai ye useful program hai, lekin ye backdoor open karta hai attacker ke liye.
4. Spyware
Chupke se system me install ho jata hai.
User ki activity monitor karta hai (jaise browsing, passwords waghera).
Mostly bina user ke pata chale data send karta hai attacker ko.
5. Adware
User ko bht zyada ads dikhata hai (pop-ups, banners).
Kabhi kabhi spyware ke sath bhi aata hai.
Zyada tar user experience kharab karta hai aur data bhi collect karta hai.
6. DDoS/Botnet
Botnet: Infected computers ka network hota hai jise attacker control karta hai.
DDoS (Distributed Denial of Service): Bohat sare infected systems se aik server/website pe attack kiya jata hai — taake wo down ho jaye.
7. Keyloggers
User ke keyboard strokes record karta hai.
Passwords, chats, banking info sab secretly capture kar leta hai.
Mostly spyware ke zariye install hota hai.
8. Rootkits
System ke root (admin level) tak access le leta hai.
Apni presence chhupa leta hai, taa ke detect na ho.
Attackers ko full control deta hai without being noticed.
### 1. virus:Attach themself to a legitmate files spread itself and make RAM more consumed
### 2. worms: itself a standalone program
### 3. Trojan horses:.... 
### 4. spyware...
### 5. Adware:....
### 6. DDos/Botnet....
### 7. Keyloggers(keyboard)....
### 8. RootKits: takes root access.....
R=read
X=executable
w= write
chmod+x hassan.tct

# Attacks
## 🔸social engineering attacks:
manuplate and decive an individual 
verbal and non-verbal
verbal means calling  non-verbal means phishing
## 🔸DOS 
dirupt the normal functioning when it is done by botnet then it is DDOS
## 🔸on Path Attack(mITM) & 🔸seo poisoning(promote malicious website)
## 🔸wifi password cracking
## 🔸password Attacking 
guess the password 
### 🔸brute force
### 🔸dictornary attack or rainbow attack
## 🔸Cracking Time
## 🔸APTs

# vulnerablitity:
weakness or loophole
## Hardware Vulnerablities:
Flaws in mother board RAM 
rowhammer the vulnerabilty led to .....
## software vulnerability 
buffer overflow

#backups:
### home backup
### cloud

### dont get spoofed
Preventing spoofing attack
spoofing Email:..... Attackers id

# Security Appliances:
### Router
boundary of network
## IPS & IDS
alerts and block vs only alert (dog Example)
## VPN
Encrypt the messege
Purpose:
To secure your internet connection and hide your IP address by routing all traffic through an encrypted tunnel.

How it works:
It encrypts your entire internet traffic and routes it through a remote VPN server. All websites and apps see the VPN server's IP.

Use cases:

Browse anonymously

Access blocked websites (e.g., Netflix, Facebook)

Secure public Wi-Fi usage

Hide your location/IP

Pros:

Full internet encryption

Protects privacy

Works system-wide (for all apps)

Cons:

Can slightly reduce internet speed

Requires software or OS configuration
## RDP
Purpose:
To remotely control another computer as if you're physically there.

How it works:
You connect to a remote computer and get its screen, keyboard, and mouse over the internet.

Use cases:

Access work PC from home

IT support/control of remote systems

Use a different OS or environment remotely

Pros:

Full control over a remote machine

Great for remote work or tech support

Cons:

Not private (host sees everything)

No anonymity (you’re still using the remote PC's network)

Needs configuration and open ports
## proxy
Purpose:
To redirect specific app or browser traffic through a different server—like a middleman.

How it works:
You set your app/browser to use a proxy server. The proxy fetches data for you and forwards it back.

Use cases:

Bypass geo-blocks (e.g., limited YouTube videos)

Web scraping

Limited anonymity (e.g., school, work filters)

Pros:

Simple to set up (just in browser)

Can be faster than VPN for some tasks

Good for region switching (e.g., pricing)

Cons:

No encryption (unless using HTTPS)

Doesn’t protect all traffic—only configured apps

Many free proxies are slow or unreliable
## Firewalls:
a barrier used for filtering the data coming and out of my computer.

## Port Scanning:
65535 ports
Port	Protocol / Service	Purpose
20	FTP (Data Transfer)	File transfer (data channel)
21	FTP (Command)	File transfer (command/control)
22	SSH (Secure Shell)	Secure remote login
23	Telnet	Unsecured remote login
25	SMTP	Sending emails
53	DNS	Domain name resolution
67	DHCP (Server)	Assign IP addresses
68	DHCP (Client)	Receive IP configuration
69	TFTP	Trivial file transfer
80	HTTP	Web browsing (insecure)
110	POP3	Receiving emails
123	NTP	Time synchronization
143	IMAP	Email retrieval (more advanced than POP3)
161	SNMP	Network device monitoring
162	SNMP Trap	SNMP alerts
179	BGP	Border Gateway Protocol (routing)
443	HTTPS	Secure web browsing
465	SMTPS	Secure email sending
514	Syslog	System log messages
587	SMTP (with TLS)	Secure email sending (modern)

## 🧑‍💻 Registered / Popular Ports (1024–49151)
Port	Protocol / Service	Purpose
3306	MySQL	Database server
3389	RDP (Remote Desktop Protocol)	Remote access to Windows machines
5432	PostgreSQL	Database server
5900	VNC	Remote desktop access
8080	HTTP (Alternate)	Common alternative for web servers
8443	HTTPS (Alternate)	Secure alternative for 8080

## ⚠️ Ports Used in Hacking / Security Testing
Port	Protocol / Service	Purpose
135	Microsoft RPC	DCOM services (exploited in many attacks)
139	NetBIOS Session	File sharing on Windows
445	SMB	File and printer sharing
1433	MSSQL	Microsoft SQL Server
5900	VNC	Often targeted for remote access
21/22	FTP / SSH	Brute-force targets

## port Scanning tools:
NMAP
ZENMAP
ANGRY IP SCANNER
SUSPERSCAN
HPING

## real-time Detection:
Behaviour detectng attacks in real time.DDOS Attack is the biggest example of threat require real time detection.
## Netflow
## penetration Testing 
to check the flaws and weakness of system
5 Steps
palnning 
scanning
gaining access 
mantaing acess
analysis and reporting

## risk Management

# week 3
## nikto
nikto -h (domain name)
auinetix

# Week 3 day 6
### TCP vs OSI
TCP/IP vs OSI Model
📑 1. Number of Layers

OSI Model → 7 layers

TCP/IP Model → 4 layers

📑 2. Layer Structure
OSI Model (7 Layers)	TCP/IP Model (4 Layers)
Application	Application
Presentation	Application
Session	Application
Transport	Transport
Network	Internet
Data Link	Network Access
Physical	Network Access
📑 3. Purpose

OSI Model → A theoretical reference model, mainly used for learning & understanding networking.

TCP/IP Model → A practical implementation, used for real-world networking (Internet).

📑 4. Development

OSI → Developed by ISO (1984).

TCP/IP → Developed by DARPA (1970s) for ARPANET (precursor to the Internet).

📑 5. Protocol Dependency

OSI → Protocol-independent (general model).

TCP/IP → Protocol-specific (designed around TCP & IP).

📑 6. Usage in Cybersecurity

OSI → Helps in mapping attacks & defenses layer by layer (useful for analysis).

TCP/IP → Used in real attacks and defenses (firewalls, VPNs, IDS/IPS work on TCP/IP).
## OSI model
 ### Physical Layer (Layer 1)

Attacks target the hardware & signals.

🔴 Examples:

Cable cutting / physical damage

Signal jamming (wireless networks)

Hardware keylogger insertion

TEMPEST attack (electromagnetic eavesdropping)

### 2. Data Link Layer (Layer 2)

Focuses on MAC addresses & switching.

🔴 Examples:

MAC Flooding → overload switch to act like a hub.

ARP Spoofing/Poisoning → attacker tricks network into sending packets to them.

VLAN Hopping → gain access to restricted VLANs.

### 3. Network Layer (Layer 3)

Responsible for IP addressing & routing.

🔴 Examples:

IP Spoofing → fake IP to impersonate another device.

Route Hijacking / BGP attack → manipulate routing tables.

Ping of Death / ICMP Flood → crash systems with malformed packets.

DoS/DDoS → overwhelming traffic at the IP level.

### 4. Transport Layer (Layer 4)

Deals with TCP/UDP communication.

🔴 Examples:

SYN Flood Attack → send many half-open TCP requests to exhaust server.

Port Scanning (Nmap) → find open ports for exploitation.

UDP Flood → overload target with UDP packets.

Session Hijacking → taking over active TCP connections.

### 5. Session Layer (Layer 5)

Manages sessions & authentication.

🔴 Examples:

Session Hijacking → steal session tokens/cookies.

Man-in-the-Middle (MITM) → intercept communication between two hosts.

Replay Attack → reuse a valid session token to gain unauthorized access.

### 6. Presentation Layer (Layer 6)

Handles data translation, encryption, compression.

### 🔴 Examples:

SSL Stripping → downgrade HTTPS to HTTP.

Certificate Forgery → fake certificates to trick users.

Data Encoding Attacks (Unicode manipulation to bypass filters).

### 7. Application Layer (Layer 7)

Closest to user; deals with apps, browsers, protocols.

🔴 Examples:

SQL Injection → attacker injects malicious queries.

Cross-Site Scripting (XSS) → injects malicious code into websites.

Cross-Site Request Forgery (CSRF) → trick users into performing unwanted actions.

Phishing → fake websites/emails to steal credentials.

Malware Injection / Ransomware → delivered via apps.

# password guessing
hydra -L /home/kali/usr -P /home/kali/pswrd -v ftp://192.168.85.129
usr and pswrd are text files and have the correct name and password in that list like msfadmoin.






# sir sami
There are two types of softwares 
propritery
open source 
kali linux is open source which is promoted by Apache
Forking (ver0sion or distribution)
linux based verison knowm as kali linux
## Linux vs Other Operating systems
linux has less user interface than other os. we change only configuratu=ion by writing it in terminal.most of the usedd os is linux as it is used in linux or settlites facebook or youtube or anyy other banking system uses Linux. 
PECA(when you scan or nmap any government website it will take action against u)pakistan electronic crime act.
USED in:
1. Banking
2. telecom
3. PTA 
4. Ecommerce
5. Fbr(NCCIA)
OT based system operational technology cia triads will be reversed

## NAT
## Bridge
## Host
## OSSTMM
# week 3:
## footprinting
## enumuration detail of ip and its services
### exploit.tb(website)
### exploitation in pentesting domain
### Network operation center:NOC
###  SNMPis used to monitor availibility in CIA 
### NMS
## NetBIOS LAN DNS services
## letral moment: if one end point is exploit then whole network can be exploited:
## SMB
## NTP
## tell the risk---->> by vulnerablity and likelihood or probablity
### IDOR---> has fraud of biilions of dollars
## heart bleed bug 
## equifax
## CVE's
## STRIDE FRAMEWORK
## SAACA 
## CISA



# Sir sufyan
## ip and MAc
### 🔸IP Address (Internet Protocol Address)
Kya hai?
Ye ek logical address hota hai jo har device ko internet ya network par identify karta hai.

Example: 192.168.1.5 ya 10.0.0.2

Change hota hai?
✔️ Haan, IP address change ho sakta hai (router restart, dynamic IP, VPN etc.)

Kis cheez ke liye?

Network pe device ko identify karna

Data ko kahaan bhejna hai decide karna (like home address)

###🔸 MAC Address (Media Access Control Address)
Kya hai?
Ye ek physical (hardware) address hota hai jo network card (NIC) ke saath built-in hota hai.

Example: 00:1A:2B:3C:4D:5E

Change hota hai?
❌ Normally nahi hota, fixed hota hai. (Lekin spoof kiya ja sakta hai manually)

Kis cheez ke liye?

Local network par device ki unique identity batata hai

Router ya switch MAC address dekh ke decide karta hai data kahan bhejna ha
## ARP table 
Computer ya VM jab kisi IP se baat karna chahta hai, to usko pehle us IP ka MAC address chahiye hota hai (network ke andar).
ARP ka kaam hai: "IP → MAC" mapping karna.
## 🔸NAT (Network Address Translation):
Apka VM apne alag network me hota hai.

Ye internet chalata hai lekin host PC ke through.

VM ka IP address local hota hai (jaise 192.168.x.x), aur ye baahar ke network se directly visible nahi hota.

Safe hota hai kyunki external world VM ko directly access nahi kar sakta.

Example:

Jaise ek chhoti gali jahan se sirf ek gate (host PC) ke zariye log andar ja sakte hain. Andar sab ke alag ghar hain (VMs), lekin bahar wale sirf gate tak pahunch sakte hain.

## 🔸Bridged Mode:
VM directly aapke real network ka hissa ban jata hai.

VM ko apke router se real IP milta hai, jaise host PC ko milta hai.

VM aur host dono same level pe hote hain network me.

VM network pe dusre devices se communicate kar sakta hai jaise ek normal computer karta hai.

Example:

Jaise ek open colony jahan har ghar ka apna entrance hai (VMs + host PC), aur sab directly road se connected hain.
write a command in command prompt tracert google.com it shows the total journey of a request
