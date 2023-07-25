# HowTheWebWorksExercise
In your own terms, define the following terms:

What is HTTP? Hyper Text Transfer Protocol - it is how clients get data from a server or sends to a server.
What is a URL? Uniform Resource Locator- the address for an internet site.
What is DNS? Domain Name System- converts URLs in to IP addresses
What is a query string? The query string allows you to pass key-value pairs into the URL.  It assigns values to specified paramaters. ex. title=Query_string&action=edit
What are two HTTP verbs and how are they different? GET - get data from the server that doesn't change the servers data.  POST - sends data that changes on the server
What is an HTTP request? An HTTP request is a request from a client to a server which follows the HTTP protocol; requesting a web page
What is an HTTP response? An HTTP response is a response from a server to a client which follows the HTTP protocol ; sending back the website information
What is an HTTP header? Give a couple examples of request and response headers you have seen.
Headers provide additional information about the request or the response.  examples:
Request headers: Host, User-Agent, Accept, Cookie, Cache-Control
Response headers: Content-Type, Last-Modified, Set-Cookie, Cache-Control
What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
Your browser “resolves” the name into an IP address using DNS
Your browser makes a request to that IP address, including headers (info about browser, any previous cookies, and other things)
The server sends a response (typically, HTML, with a status code (200 if it was sucessful)
The browser makes a DOM from that HTML, and finds any other resources needed (images, CSS, JavaScript, etc)
The browser makes separate HTTP requests for those resources and receives response from the server for each
