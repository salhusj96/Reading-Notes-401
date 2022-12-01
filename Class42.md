# **What is Mimikatz?**
- an open-source application that allows users to view and save authentication credentials such as Kerberos tickets
- works with the current release of Windows and includes a collection of different network attacks to help assess vulnerabilities
- Attackers commonly use Mimikatz to steal credentials and escalate privileges because in most cases, endpoint protection software and antivirus systems will not detect or delete the attack
## **What can Mimikatz do?**
- **Pass-the-hash:** Windows used to store password data in an NTLM hash. Attackers use Mimikatz to pass that exact hash string to the target computer to log in. Attackers don’t even need to crack the password — they just need to use the hash string as-is
- **Pass-the-ticket:** Newer versions of Windows store password data in a construct called a ticket. Mimikatz provides functionality for a user to pass a Kerberos ticket to another computer and log in with that user’s ticket
- **Overpass-the-hash (pass-the-key):** Yet another flavor of the pass-the-hash, but this technique passes a unique key obtained from a domain controller to impersonate a user
- **Kerberoast golden tickets:** This is a pass-the-ticket attack, but it’s a specific ticket for a hidden account called KRBTGT, which is the account that encrypts all of the other tickets. A golden ticket provides you with non-expiring domain admin credentials to any computer on the network.
- **Kerberoast silver tickets:** Another pass-the-ticket, but a silver ticket takes advantage of a feature in Windows that makes it easy for you to use services on the network. Kerberos grants a user a ticket-granting server (TGS) ticket, and a user can use that ticket to authentic to service accounts on the network
- **Pass-the-cache:** Finally an attack that doesn’t take advantage of Windows! A pass-the-cache attack is generally the same as a pass-the-ticket, but this one uses the saved and encrypted login data on a Mac/UNIX/Linux system.
## **How do you defend against Mimikatz?**
- Restrict admin privileges.
- Disable password-caching.
- Turn off debug privileges.
- Configure additional local security authority (LSA) protection.