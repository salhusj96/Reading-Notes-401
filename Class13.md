# **Reverse Proxy**
## **What is it?**
- a server that sits in front of web servers and forwards client's (e.g. web browser's) requests to those web servers
- increases security performance and reliability
## **What is a Proxy?**
- A normal proxy is a server that sits infront of a group of client machines
- acts as a middle-man between the services on the internet and the computers its protecting
  - can be used to get around the restrictions the limited access some organizations use
  - can also be used for the opposite, and block a group of users from accessing certain sites
  - can increase your anonymity online, where only the proxy IP address is visible 
## **How is it different?**
- A proxy server sits infront of one or more web servers, intercepting requests from clients
- A reverse proxy sits in front of an origin server and ensures that no client ever communicates directly with that origin server
## **The Benefits**
- Load Balancing: When a website gets millions of views a day the proxy server can distribute the traffic among different servers.
- **Protection from Attacks:** A web site or service never needs to reveal the IP address of their origin servers. Makes it hard to leverage an attack aginst them.
- **Global Server Load Balancing (GSLB):** Distributes the traffic to different servers around the world.
- **Caching:** It can cache and save data so that connections to it can be made faster.
- **SSL Encryption:** It can be configured to decrypt all incoming requests and encrypt all outgoing responses.
---
Source: [Reverse Proxy](https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/)