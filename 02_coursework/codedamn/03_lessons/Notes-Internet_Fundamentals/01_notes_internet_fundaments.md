## DNS

<br>

**The Domain Name System (DNS)** is the phonebook of the Internet. Humans access information online through domain names, like nytimes.com or espn.com. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources.

## HTTP

<br>

**HTTP** is the TCP/IP based application layer communication protocol which standardizes how the client and server communicate with each other. It defines how the content is requested and transmitted across the internet.

## HTTP Status Codes:

<br>

- **(100–199)** Informational responses
  <br>
- **(200–299)** Successful responses
  <br>
- **(300–399)** Redirection messages
  <br>
- **(400–499)** Client error responses
  <br>
- **(500–599)** Server error responses
  <br>

HTTP Port Range: **0-65535**

Default Port: **80**
HTTPS Default Port: **443**

## HTTP Request Methods:

<br>

HTTP defines a set of **request methods** to indicate the desired action to be performed for a given resource.
<br>
HTTP requests work as the intermediary transportation method between a client/application and a server.
<br>
The client submits an HTTP request to the server, and after internalizing the message, the server sends back a response. The response contains status information about the request.

## Types of Request Methods:

<br>

- ### GET:
<br>

GET is used to retrieve and request data from a specified resource in a server. GET is one of the most popular HTTP request techniques. In simple words, the GET method is used to retrieve whatever information is identified by the Request-URL.

- ### POST:
<br>
In web communication, POST requests are utilized to send data to a server to create or update a resource. The information submitted to the server with POST request method is archived in the request body of the HTTP request. The HTTP POST method is often used to send user-generated data to a server. One example is when a user uploads a profile photo.

<br>

- PUT
  <br>
- DELETE
  <br>
- PATCH
  <br>
- TRACE
  <br>

## HTTP HEADERS:

<br>

HTTP headers let the client and the server pass additional information with an HTTP request or response. An HTTP header consists of its case-insensitive name followed by a colon (:), then by its value.

Headers can be grouped according to their contexts:

-> _Request_ headers contain more information about the resource to be fetched, or about the client requesting the resource.

-> _Response_ headers hold additional information about the response, like its location or about the server providing it.

-> _Representation_ headers contain information about the body of the resource, like its MIME type, or encoding/compression applied.

-> _Payload_ headers contain representation-independent information about payload data, including content length and the encoding used for transport.

Headers can also be grouped according to how proxies handle them:

- _Connection_
  <br>
- _Keep-Alive_
  <br>
- _Proxy-Authenticate_
  <br>
- _Proxy-Authorization_
  <br>
- _TE_
  <br>
- _Trailer_
  <br>
- _Transfer-Encoding_
  <br>
- _Upgrade_ (see also Protocol upgrade mechanism)
  <br>

### End-to-end headers

<br>

These headers must be transmitted to the final recipient of the message: the server for a request, or the client for a response. Intermediate proxies must retransmit these headers unmodified and caches must store them.

### Hop-by-hop headers

<br>
These headers are meaningful only for a single transport-level connection, and must not be retransmitted by proxies or cached. Note that only hop-by-hop headers may be set using the Connection header.
