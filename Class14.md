# **IDS and IPS**
## **What are they?**
- Intrusion Detection and Prevention Systems
- **IDS;** a visibility tool that sits off to the side of the network and monitors traffic and consists of a management console and sensors
  - When sensors encounter something that matches up to a previously detected attack signature, they report the activity to the console
  - can notify security personnel of infections, spyware or key loggers, as well as accidental information leakage, security policy violations, unauthorized clients and servers, and even configuration errors
- **IPS;** similar to an IDS, except that they are able to block potential threats as well
  - monitors, logs and reports activities, similarly to an IDS
  - also capable of stopping threats without the system administrator getting involved
- Network Intrusion Detection System (NIDS) and Host Intrusion Detection System (HIDS)
  - complementary systems that differ by the position of the sensors: network-based and host-based
  - Network-based sensors have a quicker response than host-based sensors and they are also easier to implement
  - NIDS can also detect attacks that an HIDS will miss because it looks at packet headers in real-time
## **Benefits**
- Can Be Tuned to Specific Content in Network Packets
- Can Look at Data in the Context of the Protocol
- Can Qualify and Quantify Attacks
- Make It Easier to Keep Up With Regulation
- Can Boost Efficiency
## **Disadvantages**
- Will Not Prevent Incidents By Themselves
- Experienced Engineer Is Needed to Administer Them
- Do Not Process Encrypted Packets
- IP Packets Can Still Be Faked
- False Positives Are Frequent
- Susceptible to Protocol Based Attacks
- Signature Library Needs to Be Continually Updated to Detect the Latest Threats
---
Source: [The Pros & Cons of Intrusion Detection Systems](https://www.rapid7.com/blog/post/2017/01/11/the-pros-cons-of-intrusion-detection-systems/)