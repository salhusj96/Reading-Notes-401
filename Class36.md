# **Cross-site scripting**
## **What is cross-site scripting (XSS)?**
- a web security vulnerability that allows an attacker to compromise the interactions that users have with a vulnerable application
- allows an attacker to circumvent the same origin policy, which is designed to segregate different websites from each other
- allow an attacker to masquerade as a victim user, to carry out any actions that the user is able to perform, and to access any of the user's data
- attacker might be able to gain full control over all of the application's functionality and data
## **How does XSS work?**
- works by manipulating a vulnerable web site so that it returns malicious JavaScript to users
- When the malicious code executes inside a victim's browser, the attacker can fully compromise their interaction with the application
## **What are the types of XSS attacks?**
- **Reflected XSS**, where the malicious script comes from the current HTTP request
- **Stored XSS**, where the malicious script comes from the website's database
- **DOM-based XSS**, where the vulnerability exists in client-side code rather than server-side code