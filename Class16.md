# **Capital One Data Breach**
## **Who?**
- Paige Thompson (AKA 'Erratic', former AWS Engineer)
## **What?**
- 'Erratic' uses TOR (The Onion Router) to attempt connections, develop command scripts and other readiness activities. Multiple connections were made to connect to the servers, download pilot files to test out the end-to-end scenarios
- Posted 700 folders worth of customer data to their public GitHub page, incl. IP address of a specific AWS Server
## **When?**
- Jan. 2019 to Jul. 2019
## **How?**
- Three commands utilized in the attack:
  - **Get Credentials** - First command when executed obtained security credentials known as ****-WAF-Role account (an IAM account) for an elevated role access AWS Web Application Firewall (WAF)
  - **List Buckets** - Second command, when executed, used the security credentials *****-WAF-Role account to list files and folders (aka S3 buckets)
  - **Download Files** - Third command, when executed used the *****-WAF-Role account to download files that were accessible by the credentials.
## **Conclusion?**
- resulted from a flawed configuration performed as part of the bank’s security responsibilities and discrete from the underlying AWS-secured infrastructure
- Misconfiguration and excessive permissions can cause catastrophic losses, and the Financial Institution
experience is only one of many known cases
- On July 29, 2019, the FBI arrests Paige Thompson