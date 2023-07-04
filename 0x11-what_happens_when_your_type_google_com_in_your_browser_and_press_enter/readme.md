# A JOURNEY BEHIND THE SCENES

#### What Happens When You Type “https://www.google.com” in Your Browser?

When you type “https://www.google.com” in your browser’s address bar and press Enter, a seemingly simplest act initiates a complex sequence of events behind the scenes. In this blog, we will unravel the steps involved in this process, shedding light on the crucial components that make  your web browsing experience seamless and secure.

### DNS Request

The first step is the Domain Name System(DNS) request. Your browser send a query to a DNS resolver, such as your Internet Service Provider(ISP’s) DNS server or a public DNS server like Google DNS, asking for the IP address associated with “www.google.com”. The resolver then checkers its cache for the IP address. If it doesn’t find, it queries other DNS servers until it obtains the IP address of the Google’s server.

### TCP/IP

Once the DNS resolver provides the IP address, your browser establishes a Transmission Control Protocol(TCP) connectioin with the server. TCP breaks down the date into packets, ensuring reliable and order transmission. These packets contain information about the source and destination IP addresses and port numbers.

### Firewall

Before reaching the server, the packets must pass through firewalls, which acts as a security barrier. Firewalls examine incoming traffic, filtering out potentially malicious packets or unauthorized access attempts. Firewalls play a crucial role in protecting the server and network infrastructure from cyber threats.

### HTTPS/SSL

When you typed “https://” before the website Uniform Resource Locator(URL), you enabled secure communication. Hypertext Transfer Protocol Secure(HTTPS) encrypts the data exchanged between your browser and the server, safeguarding it from  eavesdropping and tampering. HTTPS relies on Secure Sockets Layer(SSL) or Transport Layer Secure(TLS) protocols, which ensure that connection is authenticated and encrypted.

### Load Balancer

In high-traffic scenarios, websites like Google employ load balancer to distribute incoming request across multiple servers. Load balancer enhance performance and prevent any single server from being overwhelmed. They consider factors like server load, response times, and availability to intelligently direct incoming traffic.

### Web Server

Once the load balancer determines the appropriate server, it forwards the TCP packets to the web server responsible for hosting the requested page. In the case of Google, a vast infrastructure for web servers handle incoming requests from all over the world. The Web server processes the request and generates the corresponding HTML, CSS, and Javascript files.

### Application Server

Complex websites, such as Google, often rely on application servers to hangle dynamic content and preform more advanced processing.
These server execute the server-side code necessary for generating personalized responses based on user interactions. They can access databases, external APIs, and other resources to provide real-time information

### Database

For websites with dynamic content or user-specific data, a database is employed to store and retrieve information. Application servers interact with databases to fetch and update data based on user requests. In Google’s case databases store indexed information, including search results, user preferences, and more, enabling quick and efficient retrieval

To conclude, the seemingly effortless act of typing “https://www.google.com” and pressing Enter sets in motion a complex series of events involving the DNS requests, TCP/IP connections, firewalls, HTTPS encryption, load balancing, web servers, application servers, and databases. Understanding this intricate process allows us to appreciate the sophisticated infrastructure and security mesures that power our web browsing experiences.

