Lecture 1
=========

Topics
------

- [RFCs](http://en.wikipedia.org/wiki/Request_for_Comments)
    - what is it about
    - http://www.rfc-editor.org/rfc.html
- [URL](http://en.wikipedia.org/wiki/Uniform_Resource_Locator)
    - motivation
    - `<scheme> : <hierarchical part> [? <query>] [# <fragment>]`
    - resamblance to filesystem hierarchy
    - [RFC 1738](http://tools.ietf.org/html/rfc1738)
    - [RFC 3305](http://tools.ietf.org/html/rfc3305)
- [TCP/IP](http://en.wikipedia.org/wiki/Tcp/ip)
    - CIDR
    - routing
    - address space
    - IPv6
    - some tools (`iwconfig`, `ipconfig`, `ip`)
    - [RFC 675](http://tools.ietf.org/html/rfc675)
    - [RFC 1122](http://tools.ietf.org/html/rfc1122)
    - [RFC 1123](http://tools.ietf.org/html/rfc1123)
    - [RFC 1812](http://tools.ietf.org/html/rfc1812)
    - [RFC 1958](http://tools.ietf.org/html/rfc1958)
- [DNS](http://en.wikipedia.org/wiki/Dns)
    - purpose
    - resource records (RRs)
    - `A` RR
    - `CNAME` RR
    - `MX` RR
    - recursion
    - authority
    - `dig` - tool
    - [root name servers](http://en.wikipedia.org/wiki/Root_name_server)
    - [RFC 1034](http://tools.ietf.org/html/rfc1034)
    - [RFC 1035](http://tools.ietf.org/html/rfc1035)
- [HTTP](http://en.wikipedia.org/wiki/Http)
    - implementation of the URL
    - `http:// [user [:password] @] host [:port] [/path/to/resource] [?paramters] [#fragment]`
    - request
    - verbs
    - headers
    - response
    - codes
    - cookies
    - `curl` - tool
    - [RESTful pattern]()
    - [RFC 2616](http://tools.ietf.org/html/rfc2616)
    - [SPDY](http://en.wikipedia.org/wiki/SPDY)
    - [QUIC](http://en.wikipedia.org/wiki/QUIC)
    - [HTTP 2.0](http://en.wikipedia.org/wiki/HTTP_2.0)
- [HTTPS](http://en.wikipedia.org/wiki/Https)
    - difference to HTTP
    - [SSL/TLS](http://en.wikipedia.org/wiki/SSL/TLS)
        - hash
        - signature
        - encryption
        - decryption
        - too many RFCs
    - [SNI](http://en.wikipedia.org/wiki/Server_Name_Indication)
    - linked resources (a little bit of HTML)
- [MIME/ContentType](http://en.wikipedia.org/wiki/Content-type)
    - what browsers use it for
    - Content-type header
    - encoding
    - [RFC 2045](http://tools.ietf.org/html/rfc2045)
    - [RFC 2046](http://tools.ietf.org/html/rfc2046)
- Developer Tools (the Network tab)
    - F12 or Ctrl + Shift + I or Cmd + Option + I
    - Getting a page through all stages.

The real focus of the lecture is HTTP.


Practice
--------

1. Find a page that redirects (301 or 302 HTTP code) instead of returning a not found (404 code) for non existant pages.
   Hint: you can try random paths on known hosts.
2. Use the developer tools on a browser to find the HTTP code path of a request to `google.com` (exactly), not `www.google.com` nor `google.com.br`.
3. Find a form that uses GET and another that uses POST.
   Hint: use the inspector (from the developer tools on your browser), and look for a `<form [...] method="METHOD" [...]>` near inputs.
4. Find an action (clicking, hovering, something slightly more complex) that uses PUT or DELETE methods, the action must be reproductible.
   Hint: this one is harder, keep an eye on the Network tab of the develper tools.
5. 

