1. [ ] Explain what a token is used for.
<answers>
 It's is an open standard (RFC 7519) that defines a simple way for securely transmitting information between client and server as a JSON object.

2. [ ] What steps can you take in your web apps to keep your data secure?
<answers>


3. [ ] Describe how web servers work.
<answers>
Web Servers are basically simple computer programs that dispense the web page when they are requested using the web client. The machines on which this program run are usually called as a server, with both the names web server and server almost used interchangeably.

Simple process consists of 4 steps, they are:

i. Obtaining the IP Address from domain name: Our web browser first obtains the IP address the domain name (for e.g., for this page the domain name is www.geeksforgeeks.org) resolves to. It can obtain the IP address in 2 ways-
By searching in its cache.
By requesting one or more DNS (Domain Name System) Servers.
Note: Any website is assigned an IP address when it is first created on web server.

ii. Browser requests the full URL : After knowing the IP Address, the browser now demands a full URL from the web server.

iii. Web server responds to request: The web server responds to the browser by sending the desired pages, and in case, the pages do not exist or some other error occurs, it will send the appropriate error message.
For example:
You may have seen Error 404, while trying to open a webpage, which is the message sent by the server when the page does not exist.
Another common one is Error 401 when access is denied to us due to incorrect credentials, like username or password, provided by us.

iv.Browser displays the web page: The Browser finally gets the webpages and displays it, or displays the error message.

4. [ ] Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.
<answers>
Create = PUT
Retrieve = GET
Update = POST
Delete = DELETE