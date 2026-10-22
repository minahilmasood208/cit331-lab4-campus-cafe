# HTTP observations (Lab 4, Task 1)
 
| Question | My answer |
|----------|-----------|
| Request method for index.html 
| GET |
| Status code with Disable cache ticked | 200 OK |
| Status code on a normal reload
| 304 Not Modified |
| Status code for /nothing-here.html | 404 Not Found |
| Value of the Content-Type response header | text/html;charset=utf-8 |
| Remote Address (IP and port) | 127.0.0.1:5500 |
| Protocol in the address bar (http or https) | http |
 
## Why is this address http and not https?
(The address uses HTTP because Live Server uses it by default to run websites locally. HTTPS requires encryption and a TLS certificate, which are not configured for this local server.)
