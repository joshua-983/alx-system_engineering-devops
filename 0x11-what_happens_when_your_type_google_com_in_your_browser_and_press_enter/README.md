0x11. What happens when you type google.com in your browser and press Enter

When you enter a URL such as “https://www.google.com" into your web browser and press the enter key, a series of intricate processes take place before you see any results on your browser.

The remarkable thing is that all of these actions occur within a fraction of a second, leaving us rarely pondering over them.


Have you considered the multitude of processes that occur before any visible content appears in your web browser? Now, let’s dive into it in detail step by step.

DNS Request
Anytime you use your browser to access any website or domain name, the browser stores information concerning that domain name (DNS record) in its cache.

So, anytime you type a domain name like “google.com” into your web browser, the browser first checks its cache to see if it has a recent copy of the DNS record for that domain.

If there is a recent copy of the DNS records for that domain, it will use the IP address in the cache to send a request to the server. This speeds up the process of resolving the domain name to an IP address because it avoids the need to send a request to the DNS server.

If the browser cache does not contain a recent copy of the DNS record, or if the DNS record has changed since the last time it was cached, the browser will send a request to the DNS server to resolve the domain name to an IP address.

This is also a whole process on its own, so let’s explore the various steps involved.

DNS lookup process
Here’s how the DNS lookup process works in more detail:

The browser sends a request to the local DNS resolver, which is usually provided by the internet service provider (ISP).
The local DNS resolver checks its cache to see if it has a recent copy of the DNS record for the domain. If it does, it sends the IP address back to the browser.
If the local DNS resolver does not have a recent copy of the DNS record, it sends a request to a root nameserver.
The root nameserver responds with the address of a top-level domain (TLD) nameserver, such as .com or .org.
The local DNS resolver sends a request to the TLD nameserver.
The TLD nameserver responds with the address of the authoritative nameserver for the domain.
The local DNS resolver sends a request to the authoritative nameserver.
The authoritative nameserver responds with the IP address for the domain.
The local DNS resolver sends the IP address back to the browser.
The browser sends a request to the server at the IP address to retrieve the webpage.
This process may involve additional steps if the DNS record is not found at any of the nameservers, or if the DNS record has been configured to use a service such as DNS load balancing or content delivery networks (CDN).

Once the IP address has been resolved, it is cached by the local DNS resolver and the browser so that future requests for the same domain name can be resolved more quickly.

The length of time that the DNS record is cached (the “TTL,” or Time To Live) is determined by the authoritative nameserver and can be configured by the domain owner.

TCP/IP connection
TCP (Transmission Control Protocol) and IP (Internet Protocol) are two of the main protocols that make up the Internet.

They work together to establish a connection between a client and a server and facilitate the transmission of data between them.

When you enter “google.com” into a web browser, the browser uses TCP/IP to establish a connection with the server that hosts the website.

Here’s what happens in more detail:

The browser sends a request to the server using IP to establish a connection.
The server receives the request and sends back a message acknowledging the request to establish a connection. This is the handshake process.
Once the handshake is complete, the browser can send a request for the webpage it wants to access (in this case, the homepage of google.com). This request is sent using TCP, which ensures that the request is transmitted reliably and in the correct order.
The server receives the request and sends back the HTML code for the homepage of google.com to the browser. This response is also sent using TCP to ensure reliable transmission.
The browser receives the HTML code and uses it to render the webpage on your screen. Any resources (such as images) that the webpage needs are also requested and received using TCP/IP.
Firewall
A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules. Its primary purpose is to protect a network from external threats, such as hackers and malware.

When you type a URL like “google.com” into your browser, the request that your browser makes to Google’s server passes through the firewall on its way. The firewall checks the incoming request to make sure it is allowed based on its security rules.

There are two main types of security rules that a firewall uses to check incoming requests:

Rules that allow or block traffic based on the source and destination of the request. For example, a firewall may be configured to block all traffic from certain countries or to allow only certain IP addresses to access the network.
Rules that allow or block traffic based on the type of traffic. For example, a firewall may be configured to block all traffic on certain ports (such as those used by malware) or to allow only certain types of traffic (such as HTTP or HTTPS).
If the incoming request meets the security rules set by the firewall in front of Google’s server, it is allowed through, and the browser is able to access the website.

However, if the request does not meet the security rules, it is blocked, and the browser is unable to access the website.
