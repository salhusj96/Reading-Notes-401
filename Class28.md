# **Ethical hacking: Log tampering**
## **The Process**
1. Disable auditing
   - if logging is turned off, there will be no trail of evidence
   - can use the command line favorite, Auditpol, which will not only allow you to disable auditing but will also allow you to see the level of logging that the organization’s system administrator has set
2. Clearing logs
   - Clearlogs.exe
   - Meterpreter
   - Windows Event Viewer
   - Linux systems
3. Modifying logs
   - text editor may be needed to modify logs
4. Erasing command history
   - retained history of bash commands is found in the file ~/.bash_history
---
Source: [Ethical hacking: Log tampering 101](https://resources.infosecinstitute.com/topic/ethical-hacking-log-tampering-101/)