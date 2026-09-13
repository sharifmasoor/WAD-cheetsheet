 ## Lecture 02

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