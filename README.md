# Roadmap-Day-1-Task
About = (HTTP 1.1) vs (HTTP/2) 
      = Objects Its Internal Representation In Javascript

First Let See About (HTTP 1.1) vs (HTTP/2)

HTTP/1.1:
Sequential Processing: Requests and responses are processed sequentially, meaning that the browser can only handle one request at a time. If a resource is requested, the browser has to wait until the server responds before it can request another resource.

HTTP/2:
Multiplexing: HTTP/2 allows multiple requests and responses to be multiplexed over a single connection. This means that multiple resources can be requested and delivered simultaneously, improving the overall efficiency and speed of data transfer.

What Is The Different Between (HTTP 1.1) vs (HTTP/2)

>>> HTTP/1.1:
>- Sequential Processing: Requests and responses are processed sequentially, one at a time.
>- Header Inefficiency: Each request and response carries a set of headers, which can be large and redundant, leading to increased overhead.
>- No Built-in Compression: Content needs to be compressed separately, and without compression, data transfer may be slower.
>- No Server Push: The server cannot proactively send additional resources to the client without a specific request.

>>> HTTP/2:
>- Multiplexing: Supports multiple requests and responses concurrently, improving data transfer efficiency.
>- Header Compression: Headers are compressed, reducing redundancy and lowering overhead.
>- Built-in Compression: Data can be compressed within the protocol, enhancing transfer speed.
>- Server Push: Allows the server to push resources to the client without explicit requests, reducing latency.

Find the Blog link :link:=> https://medium.com/@ahizaan2005/title-the-internet-adventures-slow-postman-http-1-1-vs-quick-superhero-http-2-27204c07577b 

This Blog Will be More Easier To understand About (HTTP 1.1) vs (HTTP/2)
