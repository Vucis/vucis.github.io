# https://vucis.github.io/data.ttl
HTTP/2 200 
server: GitHub.com
content-type: text/turtle; charset=utf-8
last-modified: Thu, 05 Mar 2026 08:13:37 GMT
access-control-allow-origin: *
strict-transport-security: max-age=31556952
etag: "69a93b31-1ac"
expires: Thu, 05 Mar 2026 08:25:10 GMT
cache-control: max-age=600
x-proxy-cache: MISS
x-github-request-id: F148:F4C16:CC63DF:CF2E7D:69A93B8E
accept-ranges: bytes
age: 0
date: Thu, 05 Mar 2026 08:15:11 GMT
via: 1.1 varnish
x-served-by: cache-bru1480039-BRU
x-cache: MISS
x-cache-hits: 0
x-timer: S1772698511.925846,VS0,VE117
vary: Accept-Encoding
x-fastly-request-id: ffd74db579346c52fa1674c2ca7ef531ad83e43d
content-length: 428

Content-Type: The content type:text/turtle; charset=utf-8 header correctly identifies the file as an RDF Turtle document, ensuring semantic web parsers can process it.

CORS: The access-control-allow-origin: * header allows any external web application to fetch and reuse this Linked Open Data.

HTTPS: The HTTP/2 protocol and strict-transport-security (HSTS) header ensure the data is delivered over a secure, encrypted connection.

Caching: GitHub Pages uses a CDN (Varnish) with cache-control: max-age=600 (10-minute cache) and an etag to allow clients to efficiently check for updates.

Compression: The vary: Accept-Encoding header indicates the server supports compression. It isn't applied in this specific response, likely because the file is very small (428 bytes) or my curl command didn't explicitly request it.

