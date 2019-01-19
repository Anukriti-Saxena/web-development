# web-development
Client and server communicate through request response cycle.
<br>Here client requests the server according its requirement and server responses to the request.<br>
Web browsers and web servers function together as a client-server system. In computer networking, client-server is a standard method for designing applications where data is kept in central locations (server computers) and efficiently shared with any number of other computers (the clients) on request. All web browsers function as clients that request information from websites (servers).

Numerous web browser clients can request data from the same website. Requests can happen at all different times or simultaneously. Client-server systems conceptually call for all requests to the same site to be handled by one server. In practice, however, because the volume of requests to web servers can sometimes grow very large, web servers are often built as a distributed pool of multiple server computers.

For very large websites popular in different countries around the world, this web server pool is geographically distributed to help improve the response time to browsers. If the server is closer to the requesting device, it would follow that the time it takes to deliver the content is faster than if the server were further away.

Network Protocols for Web Browsers and Servers
Web browsers and servers communicate via TCP/IP. Hypertext Transfer Protocol (HTTP) is the standard application protocol on top of TCP/IP supporting web browser requests and server responses.

Web browsers also rely on DNS to work with URLs. These protocol standards enable different brands of web browsers to communicate with different brands of web servers without requiring special logic for each combination.

Like most internet traffic, web browser and server connections normally run through a series of intermediate network routers.

A basic web browsing session works like this:

The user specifies a URL in their browser (either from a bookmark or by typing it in)
The browser initiates a TCP connection to the web server or server pool (using port 80 by default) via its IP address as published in DNS. As part of this process, the browser also makes DNS lookup requests to convert the URL to an IP address
After the server completes acknowledgment of its side of the TCP connection, the browser sends HTTP requests to the server to retrieve the content.
To request a server one should know the IP address . This IP address is too comlicated to remember, so we are given a sting for name called domain name which icludes the name and extension.<br>
A domain name is an identification string that defines a realm of administrative autonomy, authority or control within the Internet. Domain names are formed by the rules and procedures of the Domain Name System (DNS). Any name registered in the DNS is a domain name. Domain names are used in various networking contexts and for application-specific naming and addressing purposes. In general, a domain name represents an Internet Protocol (IP) resource, such as a personal computer used to access the Internet, a server computer hosting a web site, or the web site itself or any other service communicated via the Internet. 
Domain names are organized in subordinate levels (subdomains) of the DNS root domain, which is nameless. The first-level set of domain names are the top-level domains (TLDs), including the generic top-level domains (gTLDs), such as the prominent domains com, info, net, edu, and org, and the country code top-level domains (ccTLDs). Below these top-level domains in the DNS hierarchy are the second-level and third-level domain names that are typically open for reservation by end-users who wish to connect local area networks to the Internet, create other publicly accessible Internet resources or run web sites.

The registration of these domain names is usually administered by domain name registrars who sell their services to the public.

A fully qualified domain name (FQDN) is a domain name that is completely specified with all labels in the hierarchy of the DNS, having no parts omitted. Labels in the Domain Name System are case-insensitive, and may therefore be written in any desired capitalization method, but most commonly domain names are written in lowercase in technical contexts
The work of  converting domain name to IP addressis done by Name servers.
