# **Getting Started with ZAP**
## **Security Testing Basics**
- Software security testing is the process of assessing and testing a system to discover security risks and vulnerabilities of the system and its data
- A common breakout
  - **Vulnerability Assessment** – The system is scanned and analyzed for security issues
  - **Penetration Testing** – The system undergoes analysis and attack from simulated malicious attackers.
  - **Runtime Testing** – The system undergoes analysis and security testing from an end-user.
  - **Code Review** – The system code undergoes a detailed review and analysis looking specifically for security vulnerabilities.
## **Penetration Testing**
- Penetration Testing (pentesting) is carried out as if the tester was a malicious external attacker with a goal of breaking into the system and either stealing data or carrying out some sort of denial-of-service attack
  - has the advantage of being more accurate because it has fewer false positives
  - also used to test defence mechanisms, verify response plans, and confirm security policy adherence
- Automated pentesting is an important part of continuous integration validation
  - helps to uncover new vulnerabilities as well as regressions for previous vulnerabilities in an environment which quickly changes
## **Pentesting Process**
- **Explore** – The tester attempts to learn about the system being tested. This includes trying to determine what software is in use, what endpoints exist, what patches are installed, etc. It also includes searching the site for hidden content, known vulnerabilities, and other indications of weakness.
- **Attack** – The tester attempts to exploit the known or suspected vulnerabilities to prove they exist.
- **Report** – The tester reports back the results of their testing, including the vulnerabilities, how they exploited them and how difficult the exploits were, and the severity of the exploitation.
## **Introducing ZAP**
- Zed Attack Proxy (ZAP) is a free, open-source penetration testing tool being maintained under the umbrella of the Open Web Application Security Project (OWASP)
  - designed specifically for testing web applications and is both flexible and extensible.
- **“man-in-the-middle proxy.”** It stands between the tester’s browser and the web application so that it can intercept and inspect messages sent between browser and web application, modify the contents if needed, and then forward those packets on to the destination