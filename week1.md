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


## Lecture 02

### TCP/IP Model

**4 layers:**

1. **Link** — communication within the same network; frames, MAC addresses.
2. **Internet** — logical addressing + routing between networks; IP.
   - IPv4 → 32-bit
   - IPv6 → 128-bit
3. **Transport** — end-to-end delivery, reliability, flow control, ports.
   - TCP
   - UDP
4. **Application** — services used by applications.
   - HTTP → web pages/resources
   - SSH → secure remote access
   - FTP → file transfer
   - POP → receive/download email
   - IMAP → access/manage email on server
   - SMTP → send email
   - DNS → domain name → IP address

### DNS

**DNS (Domain Name System)** converts domain names into IP addresses.

Example: `google.com` → IP address

- **TLD (Top-Level Domain)** → last part of a domain name
- **gTLD** → `.com`, `.org`, `.net`
- **ccTLD** → `.pk`, `.uk`

### URL

**URL (Uniform Resource Locator)** → address of a resource on the Internet.

Example:

`https://example.com:8080/products?id=10`

- **Protocol** → `https`
- **Domain** → `example.com`
- **Port** → `8080`
- **Path** → `/products`
- **Query** → `?id=10`

### Port

A **port** identifies a specific service/application on a device.

**Range:** `0–65535`

### HTTP Headers

Extra information included in HTTP requests/responses, such as **content type, size, and accepted formats**.