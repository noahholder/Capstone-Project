<h1>Capstone Project: The Importance of Company Digital Security</h1>

<h2>Description</h2>
Project consists of performing reconnaissance, identifying targets and running scans, identifying vulnerabilities, threat assessment, and technical reports.


<h2>Perform Reconnaissance</h2>
Introduction:
The task at hand requires building a robust profile on the target, Artemis. This profile will include the target's technology stack, email addresses, phone numbers, resumes, and more. To accomplish this task, we will use various tools and methods to obtain publicly available information. In this deliverable, we will provide an overview of the tools and methods that will be used, and we will categorize them into passive and active tools.


Passive Tools:
Passive tools are those that do not require any interaction with the target. These tools mainly rely on publicly available information. Below are some of the passive tools that we will use:
1. Google Search: We will use Google search to look for any publicly available information about Artemis, including company information, social media profiles, and blog posts.


2. LinkedIn: LinkedIn is a social media platform that can be used to search for professionals, companies, and job postings. We will use LinkedIn to gather information about Artemis, including the company's employees, job postings, and company information.


3. Glassdoor: Glassdoor is a job board that provides information about companies, including company reviews, salaries, and interview questions. We will use Glassdoor to gather information about Artemis, including employee reviews and salaries.


4. GitHub: GitHub is a platform for software development. We will use GitHub to look for any publicly available repositories associated with Artemis, which may provide information about the technology stack that the company uses.


5. WHOIS Lookup: WHOIS Lookup is a tool that can be used to obtain information about domain names, including the registration information. We will use WHOIS Lookup to gather information about Artemis' domain names.


Active Tools:
Active tools require interaction with the target. These tools may include social engineering or probing the target's network. Below are some of the active tools that we will use:
1. Social Engineering: Social engineering involves manipulating individuals to provide information that they would not typically disclose. We may use social engineering to gather information about Artemis, including email addresses and phone numbers.


2. Port Scanning: Port scanning is a technique used to discover open ports on a computer network. We will use port scanning to gather information about Artemis' network infrastructure.


3. Email Tracking: Email tracking involves embedding a unique code into an email message, which enables the sender to track when and how many times the recipient opens the email. We will use email tracking to gather information about the email addresses associated with Artemis.


4. Password Spraying: Password spraying is a technique used to guess passwords by attempting a few commonly used passwords against a large number of usernames. We will use password spraying to gather information about Artemis' email accounts.


5. Social Media Scraping: Social media scraping involves gathering information from social media platforms using automated tools. We will use social media scraping to gather information about Artemis' social media profiles.


Conclusion:
In summary, the above tools and methods will be used to build a robust profile on Artemis. We have categorized these tools into passive and active tools. Passive tools do not require interaction with the target and rely on publicly available information, while active tools require interaction with the target. By using these tools and methods, we aim to obtain as much publicly available information about Artemis as possible.


<h2>Identify Targets and Run Scans</h2>
The tools and techniques that are used to perform host discovery and enumeration include the following:

Tool: Nmap
Purpose: Obtain information on hosts and the services and operating systems they are running.
How to use: Nmap can be used to perform network scans and identify active hosts on a network by sending packets to target hosts and analyzing their responses. Nmap has a wide range of options and can be used for tasks such as port scanning, OS detection, and vulnerability assessment.


Tool: Ping
Purpose: Determine whether a host is reachable on a network.
How to use: Ping is a simple tool that sends an ICMP echo request to a target host and waits for a response. It can be used to check if a host is up and running by sending a series of ping requests and analyzing the responses.


Tool: Netcat
Purpose: Obtain information on open ports and services on a host.
How to use: Netcat is a network utility that can be used to scan for open ports on a host by sending packets to the target host and analyzing the responses. It can also be used to connect to and communicate with services running on a host, such as HTTP servers or databases.


Technique: Passive reconnaissance
Purpose: Gather information on a target network or host without actively interacting with it.
How to use: Passive reconnaissance involves collecting information from publicly available sources, such as search engines, social media, and WHOIS databases. This can provide valuable information on a target network or host without generating any network traffic or alerting the target.


Tool: DNS Enumeration
Purpose: Obtain DNS records and domain names associated with a target IP address or hostname.
How to use: DNS enumeration involves querying DNS servers to obtain DNS records such as A records, MX records, and TXT records. This can be done using command-line tools such as "dig" or "nslookup", or using a tool such as DNSRecon or dnsenum.


Tool: ARP Scan
Purpose: Obtain the MAC addresses of hosts on a network.
How to use: ARP (Address Resolution Protocol) is a protocol used to map IP addresses to MAC addresses on a network. An ARP scan involves sending an ARP request to all hosts on the network and seeing which ones respond with their MAC address. This can be done using the "arp -a" command on Windows, or using a tool such as Nmap or Angry IP Scanner.

<h2>Identify Vulnerabilities</h2>
Vulnerability scanning is an important process for identifying weaknesses in a system or network. A vulnerability scanner is a tool that is used to identify known vulnerabilities in software, operating systems, and network devices. In this document, we will discuss the tools and techniques that can be used for vulnerability scanning.

Tools and Techniques:

Tenable Nessus

Tenable Nessus is one of the most popular vulnerability scanning tools used by security professionals. It can scan multiple operating systems, databases, applications, and virtualized environments. Nessus can detect and prioritize vulnerabilities based on severity levels. Nessus can be installed on Windows, Linux, or macOS operating systems.
To use Nessus, we will need to install the Nessus scanner and then create a scan policy that defines the type of scan we want to perform. The policy can be customized to include or exclude certain hosts, ports, and protocols. We can also schedule the scans to run at specific times. Nessus will generate a report of the vulnerabilities it finds.

Pros:
–Comprehensive vulnerability scanning capabilities
–Regular updates to its vulnerability database
–Wide range of plugins to scan for vulnerabilities in various systems and 
applications
–Customizable scan templates to meet specific needs
–Integration with various third-party tools and solutions
Cons:
–Can be expensive for larger deployments
–Requires some technical expertise to set up and configure

OpenVAS

OpenVAS is an open-source vulnerability scanning tool that can detect known vulnerabilities in networks and hosts. OpenVAS can scan multiple operating systems, databases, and applications. OpenVAS can be installed on Linux or Unix operating systems.
To use OpenVAS, we will need to install the OpenVAS server and client. We can then configure the scan policies to define the types of scans we want to perform. We can also schedule the scans to run at specific times. OpenVAS will generate a report of the vulnerabilities it finds.

Pros:
–Free and open-source
–Comprehensive vulnerability scanning capabilities
–Regular updates to its vulnerability database
–Customizable scan templates to meet specific needs
–Integration with various third-party tools and solutions
Cons:
–Requires some technical expertise to set up and configure
–Not as user-friendly as some commercial tools

NMap

Nmap is a network exploration and security auditing tool. It can detect open ports, services, and operating systems on a network. Nmap can also be used to identify vulnerabilities in network devices. Nmap can be installed on Windows, Linux, or macOS operating systems.
To use Nmap, we will need to specify the IP addresses of the hosts we want to scan. We can then configure the scan options to specify the type of scan we want to perform. Nmap will generate a report of the hosts it finds and the vulnerabilities it detects.

Pros:
–Free and open-source
–Comprehensive network scanning capabilities
–Customizable scan options to meet specific needs
–Scripting capabilities to automate tasks
–Integration with various third-party tools and solutions
Cons:
–Requires some technical expertise to use effectively
–Can generate a lot of noise and false positives

Nikto

Nikto is a web server scanner that can detect vulnerabilities in web applications. Nikto can detect known vulnerabilities in web servers and web applications. Nikto can be installed on Windows, Linux, or macOS operating systems.
To use Nikto, we will need to specify the URL of the web application we want to scan. We can then configure the scan options to specify the type of scan we want to perform. Nikto will generate a report of the vulnerabilities it finds.

Pros:
	–Free and open-source
	–Comprehensive web application scanning capabilities
	–Customizable scan options to meet specific needs
	–Scripting capabilities to automate tasks
	–Integration with various third-party tools and solutions
	Cons:
	–Requires some technical expertise to use effectively
	–Can generate a lot of noise and false positives

Burp Suite

Burp Suite is a commercial web application scanner that can be used to identify potential vulnerabilities in web applications. Burp Suite can scan web applications for a range of vulnerabilities, including SQL injection, cross-site scripting, and other common web application vulnerabilities. The tool offers a range of features, including customizable scan options, scripting capabilities, and reporting.


Pros:
–Comprehensive web application scanning capabilities
–Customizable scan options to meet specific needs
–Scripting capabilities to automate tasks
–Integration with various third-party tools and solutions
–User-friendly interface
Cons:
–Requires a license for the full range of features
–Can be expensive for larger deployments
–Not suitable for non-web-based applications
In conclusion, vulnerability scanning is an essential process for identifying weaknesses in a system or network. In this document, we have discussed five tools that can be used for vulnerability scanning, including Tenable Nessus, OpenVAS, Nmap, Nikto, and Burp Suite. Each of these tools has its own strengths and weaknesses, and the choice of tool will depend on the specific requirements of the organization. It is important to note that no tool can provide 100% security, and vulnerability scanning should be just one part of a comprehensive security program. Regular vulnerability scanning and patching of vulnerabilities can help to reduce the risk of a security breach.

<h2>Threat Assessment</h2>
Vulnerability Assessment Report

Scenario 1: Unpatched RDP is exposed to the internet
Description of the vulnerability: Unpatched RDP (Remote Desktop Protocol) exposes the system to remote attacks, allowing an attacker to gain unauthorized access to the system.
Operating systems/versions affected: Windows Server 2008, Windows 7, Windows 8, Windows 8.1, Windows 10, Windows Server 2012, Windows Server 2012 R2, Windows Server 2016, Windows Server 2019.
Risks of attempting to exploit: The attacker could gain unauthorized access to the system, execute code remotely, download/upload files, create user accounts, and escalate privileges.
Risk: The attacker could use RDP brute-force attacks or exploit known RDP vulnerabilities to gain access to the system. Once inside, the attacker can steal sensitive data, install malware, pivot to other systems, and use the compromised system to launch further attacks on the network.
Blocking mechanisms: Network segmentation, strong passwords, multi-factor authentication, disabling RDP access from the internet, using VPN.
Password cracking: Use tools like Hashcat, John the Ripper, or Hydra to brute-force RDP passwords.
Remediation action: Install the latest security patches for RDP, disable RDP access from the internet, implement network segmentation, enforce strong passwords and multi-factor authentication.
CVSS score: 9.8 (Critical)


Scenario 2: Web application is vulnerable to SQL Injection
Description of the vulnerability: SQL Injection (SQLi) occurs when an attacker injects malicious SQL code into a web application's input fields, allowing them to gain unauthorized access to the database.
Operating systems/versions affected: Any web application that uses SQL databases.
Risks of attempting to exploit: The attacker could extract sensitive data from the database, modify, or delete data, execute arbitrary commands, and gain unauthorized access to the system.
Risk: The attacker can use automated SQLi tools to scan the web application for vulnerabilities, and then exploit them to gain unauthorized access to the database. Once inside, the attacker can exfiltrate sensitive data, escalate privileges, and install malware on the server.
Blocking mechanisms: Input validation, parameterized queries, using an ORM (Object Relational Mapping) framework, web application firewalls.
Password cracking: N/A
Remediation action: Implement input validation, use parameterized queries or an ORM framework, enforce least privilege access to the database, use a web application firewall to detect and block SQLi attempts.
CVSS score: 7.5 (High)


Scenario 3: Default password on Cisco admin portal
Description of the vulnerability: Default passwords on the Cisco admin portal allow an attacker to gain unauthorized access to the network infrastructure.
Operating systems/versions affected: Cisco networking equipment.
Risks of attempting to exploit: The attacker could gain unauthorized access to the network infrastructure, change the device's configuration, monitor network traffic, and intercept sensitive data.
Risk: The attacker can use tools like Shodan to identify Cisco devices with default passwords, then use the credentials to gain access to the admin portal. Once inside, the attacker can reconfigure the device, install backdoors, and use the compromised device to launch further attacks on the network.
Blocking mechanisms: Change the default passwords, use strong passwords, use multi-factor authentication, restrict access to the admin portal.
Password cracking: N/A
Remediation action: Change the default passwords, use strong passwords, use multi-factor authentication, restrict access to the admin portal.
CVSS score: 9.8 (Critical)


Scenario 4: Apache web server vulnerable to CVE-2019-0211
Description of the vulnerability: Apache web server version 2.4.0 to 2.4.38 is vulnerable to CVE-2019-0211, a vulnerability that allows an attacker to cause a Denial of Service (DoS) by sending specially crafted requests to the server.
Operating systems/versions affected: Apache web server version 2.4.0 to 2.4.38.
Risks of attempting to exploit: The attacker could cause a DoS attack on the server, making it unavailable to legitimate users.
Risk: The attacker can use tools like Metasploit to exploit the vulnerability and send malicious requests to the server, causing it to crash or become unresponsive. Once the server is down, legitimate users will not be able to access the resources hosted on the server, causing disruption to business operations.
Blocking mechanisms: Applying the patch or upgrading the Apache web server to a newer version, using a Web Application Firewall (WAF) to detect and block malicious requests.
Password cracking: N/A
Remediation action: Apply the patch or upgrade the Apache web server to a newer version that has the vulnerability fixed, use a Web Application Firewall (WAF) to detect and block malicious requests.
CVSS score: 7.5 (High)

<h2>Reporting</h2>
Detailed Technical Report:

A. Cover Page:
Title: "Detailed Technical Report for Artemis Cybersecurity Assessment"
Date: [Insert Date]
Prepared for: [Insert Client Name]
B. Table of Contents:
Executive Summary
Scope of Work
Project Objectives
Assumptions
Timeline
Summary of Findings
Vulnerabilities
Threat Analysis
Recommendations
C. Scope of Work:
This report presents the results of a cybersecurity assessment conducted for Artemis, a [Insert Company Type] based in [Insert Location].
The scope of the assessment included [Insert Details of Assessment, e.g. network infrastructure, internal systems, external facing systems, etc.].
The purpose of the assessment was to identify vulnerabilities and assess the threat landscape faced by Artemis.
D. Project Objectives:
The objectives of the cybersecurity assessment were as follows:
Identify vulnerabilities in Artemis' systems and infrastructure.
Assess the threat landscape faced by Artemis.
Provide recommendations for mitigating identified vulnerabilities and improving overall cybersecurity posture.
E. Assumptions:
It is assumed that all systems and networks included in the scope of the assessment were in their normal operating states during the assessment period.
It is also assumed that all information provided by Artemis regarding their systems and networks was accurate and complete.
F. Timeline:
The cybersecurity assessment was conducted over a period of [Insert Timeframe].
G. Summary of Findings:
A total of [Insert Number] vulnerabilities were identified during the assessment.
Of these vulnerabilities, [Insert Number] were rated as high severity, [Insert Number] as medium severity, and [Insert Number] as low severity.
The threat landscape faced by Artemis includes [Insert Threats, e.g. phishing attacks, malware, etc.].
H. Vulnerabilities:
A list of all vulnerabilities identified during the assessment is provided below, along with a description of each vulnerability and the recommended action for mitigating it.
I. Threat Analysis:
An analysis of the threats faced by Artemis is provided below, including an overview of the tactics, techniques, and procedures (TTPs) used by threat actors, as well as the potential impact of these threats on Artemis.
J. Recommendations:
Based on the findings of the assessment, the following recommendations are made for improving Artemis' cybersecurity posture:
[Insert Recommendation 1]
[Insert Recommendation 2]
[Insert Recommendation 3]
