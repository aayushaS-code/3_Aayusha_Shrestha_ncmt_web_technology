CHAPTER 1: AN OVERVIEW OF THE INTERNET AND THE WEB

Group A: Short Questions (2 Marks)

1. Define the term “Protocol” in the context of the Internet.
A protocol is a set of rules and standards that define how data is transmitted, received, and processed over the Internet between devices.
Example: HTTP, FTP, TCP/IP.

2. What is the primary difference between a Web Browser and a Search Engine?
A Web Browser is software used to access and display web pages.
Example: Chrome, Firefox
A Search Engine is a service that helps users find information on the web.
Example: Google, Bing

3. Define the World Wide Web (WWW).
The World Wide Web (WWW) is a system of interlinked web pages and resources accessed through the Internet using web browsers and URLs.

4. Distinguish between a static web page and a dynamic web page.
| Static Web Page    | Dynamic Web Page         |
| ------------------ | ------------------------ |
| Content is fixed   | Content changes          |
| Same for all users | Different for users      |
| Uses only HTML/CSS | Uses server-side scripts |
| No database used   | Database used            |


Group B: Long Questions (4 Marks)

5. Explain the client–server architecture of the web with a neat diagram.
The client–server architecture is a model in which the tasks are divided between clients and servers.
A client is a device or application (such as a web browser) that requests services or resources.
A server is a powerful computer that stores web pages and responds to client requests.

When a user enters a URL in the browser, the browser sends an HTTP request to the web server. The server processes the request and sends back an HTTP response containing the requested web page.

This architecture allows efficient data sharing and centralized control of resources.
Neat Diagram:
+-----------+        HTTP Request        +------------+
|  Client   |  ---------------------->  |   Server   |
| (Browser) |                            | (Web Host) |
+-----------+        HTTP Response       +------------+

6. Describe the functions of the following Internet services: Email, FTP, and VoIP.
a. Email (Electronic Mail):
Used to send and receive messages over the Internet.
Supports text, attachments, images, and documents.
Works using protocols like SMTP, POP3, and IMAP.

b. FTP (File Transfer Protocol):
Used to upload and download files between computers.
Commonly used for website file management.
Allows transfer of large files efficiently.

c. VoIP (Voice over Internet Protocol):
Used for voice and video communication over the Internet.
Converts voice signals into digital data packets.
Examples include WhatsApp calls, Skype, and Zoom.

7. “The Internet is a network of networks.” Elaborate on this statement explaining how packet switching works.
The Internet is called a network of networks because it consists of millions of interconnected private and public networks worldwide, such as LANs, MANs, and WANs.

Packet Switching:
In packet switching, data is broken into small units called packets.
Each packet contains the destination address.
Packets may travel through different paths across the network.
At the destination, packets are reassembled in the correct order.

Advantages of Packet Switching:
Efficient use of network resources.
Faster data transmission.
More reliable communication.
Thus, packet switching enables different networks to communicate effectively, making the Internet a global network of networks.


Group C: Scenario-Based Questions (5 Marks)

8. A startup company wants to host a website that displays the same information to all visitors and requires very low maintenance costs.However, they are being advised to use a dynamic website. As a consultant, would you agree? Justify your answer.

As a consultant, I would not agree with the advice to use a dynamic website.
The startup’s requirement is to display the same information to all visitors and keep maintenance costs very low. A static website is more suitable because:

Static websites show fixed content to all users.
They do not require a database or server-side scripting, reducing hosting and development costs.
Maintenance is minimal as there is no backend logic.
Dynamic websites are recommended only when frequent content updates, user interaction, or personalization are required, which is not the case here.

9. A user types www.google.com into their browser, but the browser displays a ”Server Not
Found” error, even though the internet connection is active. However, accessing the site
via 142.250.190.46 works. Diagnose the problem and explain the underlying technology
that failed.
Diagnosis:
The problem is with the Domain Name System (DNS).
The website opens when the IP address (142.250.190.46) is used directly, but fails when using www.google.com. 
This indicates that:
The internet connection is active.
The web server is reachable.
The DNS is unable to translate the domain name into an IP address.

Underlying Technology Failure:
DNS is responsible for converting human-readable domain names into machine-readable IP addresses.
www.google.com  →  DNS Server  →  142.250.190.46
If DNS fails or is misconfigured, the browser cannot locate the server, resulting in a “Server Not Found” error.

10. A multinational corporation wants to share sensitive inventory data with specific suppliers
but does not want this information available to the general public. Explain which network
type (Intranet, Extranet, or Internet) they should implement and why
The corporation should implement an Extranet.

Justification:
An Intranet is limited to internal employees only.
The Internet is public and not secure for sensitive data.
An Extranet allows controlled access to external parties such as suppliers.

Why Extranet is Suitable:
Provides secure access to selected suppliers.
Protects sensitive inventory data.
Uses authentication and authorization mechanisms.
Supports collaboration without exposing data to the public.

Conclusion:
An Extranet is the most appropriate network type for secure, restricted, and controlled data sharing with suppliers.
