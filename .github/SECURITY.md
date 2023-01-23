# Security Policy

_Last modified 2023-01-01_

This following Security Policy outlines security procedures and general policies 
we take to ensure the safety and security of the Open Source projects of 
Scape Ventures, as found on our GitHub repositories at: 
[https://github.com/scape-ventures](https://github.com/scape-ventures).


**Contact** \
We take security seriously and are committed to protecting our users' data. 
If you have any questions or concerns, please contact us at:
**[security@scape.ventures](mailto:security@scape.ventures)**.

**Table of Content** \
  * [Security Conventions](#security-conventions)
  * [Vulnerability Reporting](#vulnerability-reporting)
  * [Disclosure Policy](#disclosure-policy)


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

The Scape Ventures team takes all security vulnerabilities very seriously. 
If you discover a potential vulnerability in our code, please report it to us. 
We very much appreciate your efforts to improve the security of our open source 
software and responsible disclosure and will make every effort to acknowledge 
your contributions. 

Please report (suspected) security vulnerabilities by emailing the 
Scape Ventures team at:

**[security@scape.ventures](mailto:security@scape.ventures)**. 


We will investigate all reports and tou will receive a response from the lead 
maintainer as soon as possible, indicating the next steps in handling your report.
If the issue is confirmed, we will release a patch as soon as possible, 
depending on complexity but historically within a few days.
After the initial reply to your report, the security team will endeavor 
to keep you informed of the progress towards a fix and full announcement, 
and may ask for additional information or guidance.


## Disclosure Policy

When the security team receives a security bug report, they will assign it
to a primary handler. This person will coordinate the fix and release
process, involving the following steps:

  * Confirm the problem and determine the affected versions.
  * Audit code to find any potential similar problems.
  * Prepare fixes for all releases still under maintenance.
  * Release the fixes as fast as possible.


