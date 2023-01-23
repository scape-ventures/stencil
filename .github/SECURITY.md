# Security Policy

_Last modified 2023-01-01_



**This following Security Policy outlines security procedures and general policies 
we take to ensure the safety and security of the Open Source projects of Scape Ventures, as found on our GitHub repositories at: [https://github.com/scape-ventures](https://github.com/scape-ventures).**




**Table of Contents**
  * [Security Contact](#security-contact)
  * [Security Conventions](#security-conventions)
  * [Vulnerability Reporting](#vulnerability-reporting)
  * [Disclosure Policy](#disclosure-policy)



## Security Contact

We take security seriously and are committed to protecting our users' data. 
If you have any questions or concerns, please contact us at:
**[security@scape.ventures](mailto:security@scape.ventures)**.

```
security@scape.ventures
```

## Security Conventions


1. **Access Control** \
Access to our repository is restricted to authorized individuals and teams. 
Passwords are required for all accounts and are regularly rotated. 
Where possible, Two-factor Authentication is also required for all accounts.

2. **Vulnerability Reporting** \
We have a vulnerability reporting procedure in place, please see the: 
['Vulnerability Reporting'](#vulnerability-reporting) section in this document.

3. **Third-Party Code** \
We take care to use only reputable third-party libraries and frameworks, 
and keep them updated to the latest version. Any vulnerabilities in 
third-party code will be addressed as soon as possible.

4. **Encryption** \
All sensitive data and communications are encrypted whenever and whereever 
possible.

5. **Backups** \
Regular backups of important data are taken to ensure it can be recovered in 
case of a security incident.

6. **Auditing** \
We regularly audit our repository for potential security issues using code 
scanning tools.

7. **Response Plan** \
We have a plan in place for responding to security incidents, including how 
to contain, eradicate, and recover from a security incident.






## Vulnerability Reporting

Security is of the highest importance and yhe Scape Ventures team takes all 
security vulnerabilities very seriously. 
If you discover a potential security vulnerability in our code, please report 
it to us privately, to minimize negative implications before it has been fixed.

We very much appreciate your efforts to improve the security of our open source 
software and responsible disclosure and will make every effort to acknowledge 
your contributions. 

Please report (suspected) security vulnerabilities with its details, by 
emailing our Security Team at:

**[security@scape.ventures](mailto:security@scape.ventures)**. 

IMPORTANT: Do not file public issues on GitHub for security vulnerabilities


>> #### Proposed Email Content
Provide a descriptive subject line and in the body of the email include the following information:
- Basic identity information, such as your name and your affiliation or company.
- Detailed steps to reproduce the vulnerability (POC scripts, screenshots, and compressed packet captures are all helpful to us).
- Description of the effects of the vulnerability and the related hardware and software configurations, so that the Security Team can reproduce it.
- How the vulnerability affects Harbor usage and an estimation of the attack surface, if there is one.
- List other projects or dependencies that were used in conjunction in order to produce the vulnerability.


We will investigate all reports and tou will receive a response from the lead 
maintainer as soon as possible, indicating the next steps in handling your report.
If the issue is confirmed, we will release a patch as soon as possible, 
depending on complexity but historically within a few days.
After the initial reply to your report, the Security Team will endeavor 
to keep you informed of the progress towards a fix and full announcement, 
and may ask for additional information or guidance.

## Disclosure Policy

When the Security Team receives a security bug report, they will assign it
to a primary handler. This person will coordinate the fix and release
process, involving the following steps:

  * Confirm the problem and determine the affected versions.
  * Audit code to find any potential similar problems.
  * Prepare fixes for all releases still under maintenance.
  * Release the fixes as fast as possible.


