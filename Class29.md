# **Threat Modeling**
## **Objectives of Threat Modeling**
- a family of activities for improving security by identifying threats, and then defining countermeasures to prevent, or mitigate the effects of, threats to the system
- A threat model typically includes:
  - Description of the subject to be modeled
  - Assumptions that can be checked or challenged in the future as the threat landscape changes
  - Potential threats to the system
  - Actions that can be taken to mitigate each threat
  - A way of validating the model and threats, and verification of success of actions taken
## **Four Question Framework**
- What are we working on?
- What can go wrong?
- What are we going to do about it?
- Did we do a good job?
---
# **STRIDE**
- **Spoofing**
  - when someone claims to be a person or system they are not
- **Tampering**
  - modifying data in such a way that detractsa from its reliability
- **Repudiation**
  - when an application or system does not adopt controls to properly track and log users' actions
- **Information Disclosure**
  - leakage of data or information that may compromise a system, users, or customers
- **Denial of Service**
  - makes a system unreachable by exploiting resources so they can’t be used for legitimate purposes
- **Elevation of Privilege**
  - malicious user escalates their ability to act within a system