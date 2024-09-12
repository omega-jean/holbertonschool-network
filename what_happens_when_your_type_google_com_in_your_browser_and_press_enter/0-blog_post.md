## What happens when you type https://www.google.com in your browser and press Enter?
When you type a URL, like https://www.google.com, in your browser and press Enter, a series of complex processes occurs in the background to
display the web page. Let’s break down each step of this journey in detail:

## 1. DNS Request
The first step is to translate the human-readable domain name (e.g., www.google.com) into a computer-understandable IP address, such as 142.250
180.142. This is done through the Domain Name System (DNS), which acts as a phone book for the internet. If your browser doesn’t already know the
IP address from a previous visit, it queries a DNS server to find the correct IP address.

## 2. TCP/IP
Once the IP address is found, your browser initiates a connection using the Transmission Control Protocol (TCP) over the Internet Protocol (IP)
TCP/IP is the fundamental communication protocol of the internet. It ensures that data is broken into small packets, transmitted over the network
and correctly reassembled at the destination.

## 3. Firewall
During the connection, the request passes through several layers of security, including firewalls. Firewalls are network security systems designed
to block malicious traffic and allow legitimate requests. They ensure that the communication between your browser and Google's server is secure.

## 4. HTTPS and SSL
Because the URL starts with https://, the communication between your browser and Google's server is encrypted. HTTPS stands for Hypertext Transfer
Protocol Secure, and it uses Secure Sockets Layer (SSL) protocols to encrypt data during transmission, preventing unauthorized people from reading
and modifying this information.

## 5. Load-balancer
Once the secure connection is established, the request reaches Google's infrastructure, which consists of many servers spread across the globe.
The request is directed to one of Google's data centers by a load balancer. The load balancer ensures that traffic is distributed efficiently,
preventing a single server from being overloaded with too many requests.

## 6. Web server
When the request arrives at the chosen data center, it is first processed by a web server. The web server is responsible for handling HTTP/HTTPS
requests and providing the appropriate resources (such as HTML, CSS, JavaScript, and images) that make up the web page.

## 7. Application server
Then, if the web page involves dynamic content, the request can be forwarded to an application server. This server handles the business logic,
often interacting with a database to retrieve the data needed to generate the page's dynamic content.

## 8. Database
For custom or dynamic web pages, the application server may need to retrieve or store data in a database. For example, when you search on Google,
the database stores and retrieves the index of web pages relevant to your query. Google's powerful databases and indexing systems provide the most
accurate search results quickly.

## Conclusion
In just a few seconds, when you press "Enter" after typing https://www.google.com, a series of complex, yet smooth processes take place to deliver
the requested web page to you. From DNS resolution to securing the connection over HTTPS, load balancing and interacting with databases, the web
infrastructure is incredibly robust and sophisticated.
