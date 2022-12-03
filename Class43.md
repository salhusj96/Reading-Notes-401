# **What is a Sniffing attack and How can you defend it?**
- sniffing can be performed using an application, hardware devices at both the network and host level. 
- Any network packet having information in plain text can be intercepted and read by the attacker
## **Sniffing motives**
- Getting username an passwords
- Stealing bank related/transaction related information
- Spying on email and chat messages
- Identity theft
## **Types of Sniffing**
- Passive Sniffing
  - occurs at the hub
  - a sniffer device is placed at the hub then all the network traffic can be directly captured by the sniffer
- Active Sniffing
  - a switch learns a CAM table that has the mac addresses of the destinations
  - the switch is able to decide what network packet is to be sent where
  - sniffer will flood the switch with bogus requests so that the CAM table gets full. Once the CAM is full the switch will act as a switch and send the network traffic to all ports
## **Attack Implementations**
- MAC flooding
- DNS cache poisoning
- Evil Twin attack
- MAC spoofing
## **How do you identify a Sniffer?**
- Protocols vulnerable to sniffing attacks
  1. HTTP
  2. TELNET
  3. FTP
  4. POP
  5. SNMP
## **Precautionary measures against Sniffing attacks**
- Connect to trusted networks
- Encrypt! Encrypt! Encrypt!
- Network scanning and monitoring