# **Applying The CIA Triad To Your Enterprise File Transfer**
## **The CIA Triad**
- Confidentiality
  - confidentiality refers to the principle of restricting access to or knowledge of certain pieces of information to certain individuals
- Integrity
  - pertains to the principle of preventing data from being tampered
    - can be compromised during data transfers through man-in-the-middle attacks
- Availability
  - ensuring that data is available to end-users and applications, when and where they need it
## **Encryption Solutions**
- Encryption renders data unreadable, preserving that data's confidentiality
  - can become readable again only after it's decrypted
- Encryption solutions are usually grouped into two categories:
  - Data-at-rest; file-level encryption, OpenPGP
  - Data-in-transit; SSL (FTPS, HTTPS) or SSH (SFTP)
- To achieve data integrity in your file transfers, you can use hash functions and digital signatures, security elements that are readily available in secure file transfer protocols like FTPS, HTTPS, SFTP
# **What Are MD5, SHA-1, and SHA-256 Hashes**
## **Hashes**
- products of cryptographic algorithms designed to produce a string of characters
- have a fixed length, regardless of the size of the input data
  - MD5, SHA-1, and SHA-256 are all different hash functions
    - prefer SHA-256 when possible
- "While hashes can help you confirm a file wasn’t tampered with, there’s still one avenue of attack here. An attacker could gain control of a Linux distribution’s website and modify the hashes that appear on it, or an attacker could perform a man-in-the-middle attack and modify the web page in transit if you were accessing the website via HTTP instead of encrypted HTTPS."
---
Sources: [Implementing the CIA Triad](https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet)

[What are Hashes](https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/)