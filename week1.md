
**WAD CHAPTER 1:**


1. Internet is a global network of interconnected computers/devices (infrastructure) whereas the Web is a service comprised of a collection of websites which mainly provide info. FTP, Web, Gaming and Email are supported by the internet. *Intranet* is a private network for businesses/orgs which is inaccessible by the general public as it is protected by firewalls.
2. Communication is done via packet switching which divides msgs into small chunks (packets) and sends them to a destination address via multiple pathways so has lower bandwidth (advantage).
3. Web apps are internet-dependent, easily updatable, compatible w/ multiple OS and browsers, have centralized storage. But they have storage, security, appearance, and OS restriction issues.
4. Static webpage (plain HTML) has fixed content stored in server for each user whereas dynamic webpage (made of programs) changes based on user actions. Web 2.0 = static -> dynamic.
5. Client (device that requests a service/resource) - Server (dedicated computer that responds to requests and has types e.g. database, media etc.) Model-based communication. P2P (Peer-to-peer) Model suggests that each computer can be both server + client.
6. Server farm has many servers located together w/ load balancer routers to reduce failover redundancy (in hardware). They are housed within data centers (which have security, cooling, storage systems).
7. Device->Router (fwds data packets to/from networks)->Broadband Modem (bridge b/w in-house network to outside network)->Copper/DSL/Coaxial/Fiber Cable->Fiber Junction Box (connects old copper cables to fiber optic)->ISP head-end (Internet Service Provider facility aggregating connections with a larger internet->Regional/National Network/Tier 2 (transit=small ISP pays larger ISP, peer (directly connect) for free w/ other T2s but pay T1s)->Tier 1 (internet backbone, peer w/ other T1s for free)->IXPs (Internet Exchange Points made up of switches which allow different networks to exchange traffic for reduced cost + increased speed)->Undersea Fiber Optic Cables.
8. Cloud servers are virtual servers backed by one real physical server which allows elasticity (increase/decrease no. of virtual servers based on demand).
9. HTTP(S): (secure) protocols to transfer web data b/w client and web server. HTML: A textual markup language for creating/structuring webpages.




**WAD CHAPTER 2:**
# TCP/IP Model

The  TCP/IP model  has 4 layers:

1. Link Layer:

Handles communication between devices on the same network. It deals with  frames, MAC addresses, and physical/network access .

2. Internet Layer:

Responsible for  logical addressing and routing packets  between networks. It mainly uses IP.
   IPv4: 32-bit address
   IPv6: 128-bit address


3. Transport Layer:

Provides  end-to-end communication  between applications. It handles data delivery, reliability, flow control, and ports. Main protocols are
TCP and UDP.

4. Application Layer:

Provides network services directly to applications.

   HTTP- Hypertext Transfer Protocol:  Used to transfer web pages and web resources.
   SSH - Secure Shell:  Used for secure remote login and command-line access.
   FTP - File Transfer Protocol:  Used to transfer files between computers.
   POP - Post Office Protocol:  Used to download emails from a mail server.
   IMAP - Internet Message Access Protocol:  Used to access and manage emails stored on a mail server.
   SMTP - Simple Mail Transfer Protocol:  Used to send emails.
   DNS - Domain Name System:  Converts domain names into IP addresses and helps locate network services.

# DNS (Domain Name System)
 DNS  translates human-readable domain names such as `google.com` into IP addresses such as `142.250.x.x`, so devices can find the correct server.

1. TLD (Top-Level Domain)

The last part of a domain name, such as `.com`, `.pk`, or `.org`.
   gTLD - General-purpose domains such as `.com`, `.org`, `.net`.
   ccTLD - Represents a country/territory, such as `.pk` (Pakistan), `.uk` (United Kingdom).

# URL (Uniform Resource Locator)

A URL is the address used to locate a resource on the Internet.
Example:

`https://example.com:8080/products?id=10 details`

   Protocol:  Specifies how to access the resource, e.g. `https`.
   Domain:  Identifies the website/server, e.g. `example.com`.
   Port:  Identifies the network service/application; e.g. `443` is commonly used for HTTPS.
   Path:  Shows the location of a specific resource, e.g. `/products`.
   Query String:  Contains extra parameters sent to the server, e.g. `?id=10`.
   Fragment:  Points to a specific section of a resource, e.g. ` details`.

# Port
A port is a logical number used to identify a specific service or application on a device. Port numbers range from 0–65535 .

# HTTP Headers
 Headers are extra information sent with an HTTP request or response. They tell the client or server things about the message, such as its type, size, or accepted formats.
=======