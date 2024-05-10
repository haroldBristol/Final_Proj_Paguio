**Ethical Hacking Technical Report**
**Client:** https://www.techtarget.com/
**Date:** May 10, 2024
**Prepared by:** Ubante, Harold Jay, Ani, John Dexter P

**Executive Summary:**
The technical results of the ethical hacking assessment performed for the TechTarget website are presented in this report. The evaluation's goal was to find weaknesses in the website's systems, and network infrastructure. Critical and high-risk flaws were found using a variety of testing approaches, such as vulnerability scanning and penetration testing. 

**Vulnerability Summary:**
1. Network Infrastructure: 
**Critical:** An attacker can remotely execute arbitrary code due to a Remote Code Execution vulnerability (CVE-2017-5638) in the Apache Struts framework (version 2.3.5) running on Apache Server 2.4.18.
**High:** Incorrect firewall rules allowing uncontrolled access to sensitive internal services (like SSH and RDP) on the server with IP address 203.0.113.10.

2. Web Applications:
**Critical:** The "TechTarget Login Portal" login form has a SQL Injection vulnerability that could allow an attacker to retrieve private information from the database.
**High:** The "TechTarget Forum" application has a Cross-Site Scripting (XSS) vulnerability that makes it possible for attackers to run malicious scripts in users' browsers.

3. Operating System:
**Critical:** Operating systems that are out of date and unpatched (Windows Server 2008 R2) expose them to malware and known exploits.
**High:** Inadequate password restrictions for domain user accounts, which can allow brute-force assaults and illegal access.

4. Wireless Networks:
**Critical:** In wireless networks, weak encryption (WEP) is utilized, which makes it possible for hackers to collect and decrypt wireless communication and reveal private information.

5. Social Engineering:
**High:** A number of workers responded to phishing emails by giving their credentials and private information.

**Recommendations**
1. Network Infrastructure:
- To mitigate the Remote Code Execution vulnerability, patch Apache Struts to the most recent version immediately.  
- Review and amend firewall rules to apply the least privilege principle to access restriction.
2. Web Applications:
- Perform a comprehensive code review and put input validation in place to stop XSS and SQL Injection attacks.  
- To reduce XSS vulnerabilities, implement security headers (such as Content Security Policy).

3. Operating Systems:
- Create a patch management procedure to update and protect operating systems from known vulnerabilities on a regular basis.  
- Make sure that all domain user accounts have strong password policies in place, and think about adding multi-factor authentication. 

4. Wireless Networks:
Upgrade wireless network encryption to WPA2 or WPA3 to ensure confidentiality and integrity of wireless communications.

5. Social Engineering:
Provide staff with frequent security awareness training to inform them of the dangers of phishing scams and teach them how to spot and report questionable emails. 

**Conclusion:**
The results of the evaluation of ethical hacking point to a number of serious security flaws and vulnerabilities in TechTarget's applications and systems. TechTarget can lower the risk of cyberattacks and data breaches and improve its security posture considerably by putting the suggested repair measures into practice.

Signature:
 Ubante, Harold Jay, 
Ani, John Dexter
