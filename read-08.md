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