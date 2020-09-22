# Summary of Reading for Class 08

## [HTTP basics](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
### Hypertext Transfer Protocol
Allows for communication between hosts and clients. HTTP is stateless, meaning it does not keep track of state between protocols. The default port is 80, however others can be used.

### URLs - Uniform Resource Locators
* CRUD routes are most typical verbs used for HTTP requests.

* HEAD: this is similar to GET, but without the message body. It's used to retrieve the server headers for a particular resource, generally to check if the resource has changed, via timestamps.
* TRACE: used to retrieve the hops that a request takes to round trip from the server. Each intermediate proxy or gateway would inject its IP or DNS name into the Via header field. This can be used for diagnostic purposes.
* OPTIONS: used to retrieve the server capabilities. On the client-side, it can be used to modify the request based on what the server can support.

### Status Codes
There are loads of different status codes, these are just a code that communicates how your request was processed by the host. 

`200` is a good request

`404 not found` this one is obvious. Anything in the 400's is you (the clients) fault.

`500` server side error.

### Headers
Must be sent with each request/ response. General headers can be sent with both requests and responses, other headers are special to either a request or response.

## [DNS](https://howdns.works/)
Sicc comic on DNS
### Domain Name System
System that has humans remembering names instead of ip addresses to request websites. Computers use the ip, humans use the domain name.

When a domain name is requested, the browser first searches its cache for the domain, then the OS does that, then they hit a resolver.

When the resolver (ISP - internet service provider) can't find the domain, then it hits the root server. The root server knows where the .COM top level domain (TLD) server.

Root servers sit at the top of the DNS, there are 12 scattered across the globe

.COM is the biggest DNS (started in 1985 and run by ICANN), however there are loads others.

Once the resolver is given the IP address from DNS, it goes home and gives the browser that information to then communicate with and get files from. Like HTML files.

## [Rest API](https://www.youtube.com/watch?v=Q-BpqyOT3a8&ab_channel=TraversyMedia)
