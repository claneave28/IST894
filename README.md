# IST894 - Carl Laneave's Portfolio 
[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/claneave28) [![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carl-laneave/) <a href="mailto:claneave28@gmail.com?subject=Hi Carl"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a> 

![Github Stats](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=claneave28&theme=dark) 

<hr/>

# Portfolio 

Welcome to my Cybersecurity Portfolio for IST894! This repository showcases the technical expertise and accomplishments throughout my journey in my masters program. Here, you'll find a collection of coding projects, detailed architecture diagrams, and completed assignments, all reflecting my commitment to mastering the intricacies of cybersecurity.



# Coding Projects ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
### IST555 - State Modeling ([Repo](https://github.com/claneave28/intelligent_agent_ist555))
- **Description:** Developed a state modeling python framework that would review potential impacts to supply chain based on supply and demand.

- **Key Features:**
  * Dynamically generated Wiki using Sphnix.
  * Global classes to create re-usability on a variance of parameters and inputs.
  * Written exclusively in Python and deployed using GitHub Actions.
  * Yaml input files to control overall inputs into mutable variables

# Architecture Diagrams ![](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) 
### Network Security Architecture ([Diagram](https://github.com/claneave28/network-design/blob/main/overall_network.png))
- **Description:** Presented a comprehensive network security architecture incorporating firewalls, intrusion detection/prevention systems, and secure network segmentation.

- **Notable Elements:**
  * Implementation of VPNs for secure remote access.
  * Setup of VLANs for multisite connectivity
  * Overall full network design of an enterprise with remote locations

### Serverless Security Architecture ([Diagram](https://github.com/claneave28/AWS-Serverless-Architecture-Model/blob/master/AutomationFramework_arch.png))
- **Description:**  An AWS based microservice application that is designed to do event driven management and remediation on potential security events.
- **Notable Elements:**
  * Immediate evaluation of events in real time
  * Ability to include an exceptions table to avoid issues with applications approved for certain configurations
  * Fully fed into dynamodb and then pressed to Athena, allowing for easy querying on events

### Packer Golden Image AMI Architecture ([Diagram](https://github.com/claneave28/AWS-Serverless-Architecture-Model/blob/master/AutomationFramework_arch.png))
- **Description:**  An AWS based microservice application that is designed to create, test and bootstrap a hardened ami image to be used across multiple cloud environments.  
- **Notable Elements:**
  * Complete tracking of security fixes and their related Benchmark
  * Cloud Agnostic - Can run the same security bootstrapping regardless of public cloud provider
  * Full end-to-end testing and tracking prior to deployment to the organization.

# Product Review ![](https://img.shields.io/badge/Product-Reviews-blue)
### Cyber Range Evaluation ([Evaluation](Cyber-Range-Evaluation/))

- **Description:**
Reviewed multiple different vendors to identify which fit the need of our mock organization based on key contributing metrics of evaluation

# <img src="images/img.png" width="45" height="45"> PSU Assignments  ([Master Folder](Labs/))
### Lab 1
- **Description:** During the execution of this lab, an evaluation was done to test the basics of vulnerability against a theoretically vulnerable host.  In doing so, the tool Openvas was used to execute a generalization of common vulnerabilities related both back to CVEs as well as common attack vectors.  To accomplish testing on a more expansive level and to eliminate the possibility of false positives, a username, and SSH credentials were provided to execute such attacks as brute force.  This also for a clearer vision into how attackers would emulate their own reconnaissance against our internal host and systems.  Through these executions, I was able to create multiple reports that can be directly fed to our internal team to handle any possible security flaws as well as identification of steps for remediation and overall severity. 


- **Key Components:**
  * PenTest+ Vulnerability Scans
  * PenTest+ Metasploit Framework

### Lab 2
- **Description:** During the execution of this lab, an evaluation was done to test the ability of using Ncat to create an open backdoor to our potential victim.  In this attack, Metasploit is used to load a reverse TCP payload exploit.  This exploit allows us to attack the victim and from this reverse shell, upload our malicious script.  Once the malicious script is executed, Ncat can be used to open a listener port and with an escalated permissions user, such as root, to create a session allowing for a complete compromise of the instance.


- **Key Components:**
  * Using Ncat as a Trojan
  * Credential Harvesting with SET
  * SQL Injection Chained Exploitation
  * Covert Channels/Evasion

### Lab 3
- **Description:** During the execution of this lab, an evaluation was done to test the importance of protecting ICS and SCADA Networks.  Through the usage of Modbus, we can emulate an active ICS environment and allow us to attempt different plc scans and attacks.  We also use Nmap to scan the active environments to see open ports and services on Modbus.  Including other actions are the usage of a honey pot to track the traffic and actions of potential attackers.  Metasploit being the most used tool and application, the attempted reverse TCP shells are tracked using Metasploit payloads.  Furthermore, the ability to see and scan ICS environments shows the importance of air gaping environments to prevent potential attackers from scanning or attacking ap possible vulnerability in our ICS networks.


- **Key Components:**
  * Scanning ICS/SCADA Networks
  * Attacking the Infrastructure
  * Firewall Rules for SCADA
  * SNORT SCADA Rules
  * SCADA Honeypots

### Lab 4
- **Description:** During the execution of this lab, an evaluation was done to show different flags that both Nmap as well as Hping3 can execute.  This type of Nmap scans all users to focus directly on individual ports, and a range of ports, as well as saving the executed results as multiple different format types, such as XML.  Furthermore, technology was used in execution to scan key networking ports for open accessibility using networking types such as UDP, TCP, SYN, ACK, and more.  These networking capabilities are critical functions to both individual and enterprise-level networking.  Through using the technology of Nmap, results were captured of scans of key ports into files such as XML as well as greppable files, which will allow security engineers to quickly analyze the results of open ports.  Beyond even scanning open ports, Nmap provides the ability to analyze scans to capture important information such as software versioning and OS usage for the host.  This information provides critical insight into a host and their network and instance design. 
	Using the CLI Hping, analyzes can be done even further on Network information, such as TCP/IP.  This analysis can provide deep dives into scan results on a network level as well as provide important information on the diagnosed scans. 
By having a strong understanding of Nmap and its flags, attackers as well as security analysts can quickly assess the network vulnerabilities of their enterprises.  Even more important, it's important to understand what attackers can do with these scans, such as using Nmap's ability to do automated vulnerability scanning while doing the network scans.  Through this gained knowledge, security engineers can do their own internal scans and quickly see any potential vulnerabilities and address them prior to any attackers executing their attacks.


- **Key Components:**
  * Nmap and Hping

### Lab 5
- **Description:** During the execution of this lab, an evaluation was done to test the ability of cross site scripting.  XSS is an attack using the client side by injecting malicious code.  These actions occur when malicious code is pushed into web applications in which the ability to leverage data theft and user information from the site.  Technologies such as cookie session manipulation as well as back door programs such as trojans are used in the overall site XSS attack.
When evaluating XSS, it’s important to understand the different types of attacks that can occur.  This includes reflected, stored, and DOM-Based attacks.  Each type of attack uses open principles on the site that allow the injection of code.  With reflected, information can be sent directly through HTML forms that allow for manipulation of the requests going to the server from the client side of the house.  With the stored attacks, attackers can submit data in a stored fashion that allows them to put malicious links and trojans directly on the front end for other clients to ingest through XSS.  Lastly, the DOM method uses technology to find DOM method alerts and calls such as GET/POST that can be manipulated to take code into the calls and continuing malicious attacks from the client into the host/server.
 


- **Key Components:**
  * Cross-Site Scripting (XSS)
  * File Inclusion and Cross-Site Request Forgery (CSRF)
  * HTML & SQL Injections

### Lab 6
- **Description:** During the execution of this lab, an evaluation was done to test attacks in IDOR.  IDOR is an access control vulnerability that looks to find objects that are on the internal several that are open to accessibility. Through these attacks, attackers can extract information from the internal object itself.  The other focus was around Directory traversal, which is an attack that is used to find restricted directories on a server and access them.  This attack uses misconfigured permissions on the actual server which can be exploited by potential attackers to access critical files as well as modify them to gain access to the server itself.  
Through the usage of OWASP Zap, attacks can be emulated on localhost environments through dynamic SSL certificates to emulate actual websites in a lab environment.  Once that was completed, an emulated site of Bwapp was used to attempt different types of attack vectors on an insecure site. The vulnerability executions done included both web request modifications and injected Linux commands.  Since the data itself was never sanitized as well as the permission modules on the objects/directories were never properly set, attackers could use the web application to access these files and folders.  Through this access, attackers can traverse the server as if they were on it using the permission model that is on the actual web application.  
	To avoid these types of attacks, proper permissions must be implemented on both the objects as well as the directories for reading and writing permissions.  Improper permissions allow attackers to use the host's own web application against them to escalate and traverse through their server.


- **Key Components:**
  * Common Attack Types - Insecure Direct Object Reference and Directory Traversal

### Lab 7
- **Description:** During the execution of this lab, an evaluation was done to test the ability of different types of web vulnerabilities on a website.  Web vulnerabilities are a critical path that many attackers can take in trying to access your servers and instances.  There are several types of different web vulnerabilities including XSS reflection attacks, XSS stored attacks, SQL injections and file traversing.
XXS, or cross site forgery attacks, fall into many subcategories.  In testing the first, which is the XSS reflection attacks, attackers will feed HTML code into a form since there is no protection against it.  Through this, attackers can make server requests, execute malicious code, and more.  Sanitization of said forms is critical as without it, it leaves the web application vulnerable to attacks.
Cross-site forgery stored attacks are like reflection attacks except that they are stored values.  This could include something such as a blog, in which a potential attacker could add information beyond simple text.  An example used in this lab was around submitting malicious links through a stored attack.  The said attacker can use HTML to create a phishing link that will be stored on the site and used to phish other visitors to the site.  Since it is on a blog of the site itself, it appears to be part of the site, which the attackers can use to their advantage.
Another attack reviewed is the SQL attack.  SQL attacks were at one time one of the most common methods of web vulnerability attacks.  This attack is accomplished by using illegal chars in a form such as ‘to get out of the text box and move into SQL querying language of the actual database.  Since again, the data is not sanitized prior to doing the query, attackers can escape and run their own queries against the database.  A simple query, such as 1=1 will return all true values, which is all the items in the database itself.  It is critical to eliminate the ability to send non-alphanumeric characters as well as sanitize data prior to doing any type of query.
The last attack is file traversing, which is changing the HTML crumb of a called file on the server to a new crumb and using the system directories in the call.  This is done when improper file and file structure permissions are done on the site.  Attackers can change through files and directories by changing the slug in the web URL.  Many URLs point to files on a system, and if not properly configured can be manipulated to traverse throughout the entire server's web directories.  These types of attacks allow attackers to not only see critically important secret files but also explore and add in their own shell remote commands. 


- **Key Components:**
  * Web Vulnerabilities
  * Secure and Insecure Protocols
  * Network Security and Diagnostics

### Lab 8
- **Description:** Developed a comprehensive incident response plan for a simulated security incident.
During the execution of this lab, an evaluation was done of Steganography as well as Cryptography. Throughout the lab, different types of Cryptography were tested to show how files and images can host secrets that required different types of decryptions to access.  The most common tool used for encryption as well as decryption was done through OpenSSL.  OpenSSL allows for the creation of many different types of Cryptography.  This includes DESC ECB, DES CBC, AES CBC, AES ECB, and more.  These different types of ciphertext encryption methods are critical in the protection of sensitive data in a file.
There was also an evaluation of image metadata using Steghide, a tool popular for its ability to do steganography on hidden data inside of images.  Hidden data inside images can be found when using Steghide CLI as well as hide data into the images themselves.  Not only does Steghide allow for hiding information in an image, but it also allows for doing it in audio files as well.  
Lastly, it's important to review that there are many different cryptographic algorithms that are used through OpenSSL Ciphers.  These ciphers are all important algorithms to understand as any time data needs to be protected, these different types of cryptographic algorithms can provide different types of encryptions.  Through understanding how each algorithm works, a security engineer can get a better understanding of how to encrypt a file, which algorithm to select, and how to access that said data for future usage


- **Key Components:**
  * Cryptography
  * AAA

### Lab 9
- **Description:** The purpose of this lab was to go through the different legalities, as well as scenarios, that are related to cyber security as well as forensics.  The focus, which is around the 4th amendment, is around evidence collection, legality of data, civil versus criminal cases and examples of cases related to each domain and subject.
The 4th amendment in the Constitution is designed to protect people from unreasonable searches as well as seizures.  This is important to cyber security professionals as it directly correlates to how evidence may be collected and/or handled.
The first part of the lab focuses on what is considered a civil law case versus a criminal law case.  A civil law case is a non-criminal case involving property rights while a criminal is a violation of law. Once the type of case has been determined, the next step is around discovery.  Discovery as discussed is the process in which each side of the case obtains direct evidence related to the case itself.  This occurs pre-trial to allow the defendants and plaintiffs to prepare for evidence presented at the trial. Another key part discussed was what a warrant means in the authorization of search and seizure of property. 
Legal issues around cybersecurity are extremely tough in many regards.  For one, evidence and forensics as discussed have to be handled at the highest level.  Copies can be dismissed as the data copied may not hold its original integrity. Furthermore, if the tool used to do the forensics is new or not standard, the review can be dismissed such as it was in the Casey Anthony case around her Firefox search history.  In this case, the security team used a non-validated tool to do their forensics which was called into question and caused the evidence to be dismissed.  Key pieces of evidence such as her search history could not be used in court.
Another heavy focus was on probable cause and consent of search. Things such as wiretapping and recording conversations have several rules and laws around it.  If someone is yelling in the street for all, that is legal to record.  However, if you are having a private conversation in your home, that cannot be recorded without a warrant.  Furthermore, data sent that is encrypted is protected unless there is probable cause to review it.  Otherwise, there is no way for someone to intercept that data legally.
As cybersecurity researchers, professionals, and engineers, it's critical to understand the gathering, handling, and usage of digital evidence.  Furthermore, it is important to understand the law clearly, as to avoid doing something inadvertently illegal or disruptive to a case.  This field is still ever-growing and challenging when it comes to cyber legality.  We as cyber security professionals must continue to grow, learn, and adapt to the laws around technology and digital evidence if we are to be successful in our roles.


- **Key Components:**
  * Digital Evidence and Legal Issues

### Lab 10
- **Description:** In this lab, the tools and procedures related to computer forensics were evaluated.  Starting with the processes, as well as challenges that go into collecting digital evidence.  This was discussed at length through the labs including handling data, using data in criminal cases, and intellectual property investigations.
An example of usage during intellectual property was around the discussion of digital evidence captured when songs were being illegally downloaded.  In this case, the music companies had to prove how the downloads affected their overall business and distribution while at the same time proving that the downloader did not actually own the CDs. This type of IP law and forensics investigations focused on determining damage when IP was stolen.
Another example that was investigated was around collecting digital evidence in criminal cases.  The lab talked about how to transfer data to drivers, how to do it with speed, tracking of data being saved, and how to handle said copied data in court.  For example, as was discussed in the lab, when a digital forensics security engineer comes to court, they must only bring evidence related to that case.  If they bring, for example, a notebook containing information on other cases it then becomes part of the case itself.
Lastly, the lab talked about how digital forensics data was used in court.  An example they spoke about was timestamps.  While timestamps can be manipulated by malware, it is not always the case.  Many times, if a timestamp is manipulated, it is from the original offender trying to hide information.  So, when defending your findings, it's important to understand that yes, timestamps could be manipulated, but the reality is that it is not a common action.
Collecting, handling, and managing digital forensics evidence is a key part of any security investigation.  Not only is it important to understand how to do everything related to data, but also how it needs to be represented in court and pertaining to the law.  The success of any computer forensics relies on this understanding and processes to be successful.


- **Key Components:**
  * Computer Forensics Investigations

### Lab 11
- **Description:** In this lab, the tools and procedures related to the leadership chain in cybersecurity were discussed.  In this discussion, we evaluated the different types of leadership roles and their relations to the cybersecurity field. 
Looking at the different roles and responsibilities, it's clearly laid out that at the top is the CISO, who is the chief information security officer.  While there are other ways to describe a CISO based on the organization size, the CISO still was at the top of the security leadership chain. 
In this leadership, each leader was designed to provide guidance and committee for decision points in the organization.  A key to note though, is that things such as ISO-27001 certification were not a requirement of the CISO to complete, but more on the organization itself for example.  While the CISO itself would still lead the overall direction of the enterprise when it came to cybersecurity.
One of the keys of focus for leadership was that of building a trusting, secure, and stable environment for the organization.  STS, or stability, for example, was a driving scope of the leadership model that cybersecurity leaders would lead.  Furthermore, to be a successful leader, it was important that the cyber security leadership team had the trust of their subordinates and organization.  Through trust and stability, cybersecurity leaders had the capacity to implement a secure environment around the organization.


- **Key Components:**
  * Cybersecurity senior management and information security governance (ISG)

### Lab 12
- **Description:** In this lab, we evaluate the usage of capturing logs of a potential attacker through the usage of a honey pot.  Attacker and attacker patterns can be tracked into logs using a fake website, server, etc. known as a honey pot.  These honey pots are separate and isolated away from an actual server and allow blue team and security teams to watch and analyze potential attacker methods.
Once these logs are captured, they will need to be stored in a way that protects them from being removed, read, or stolen.  This is done through the usage of encryption.  In the first method, the files are encrypted using an SHA1 key, that once completed, is stored in the application KeePass.  KeePass is a local password manager client that can be used to store important information, including hash and encryption keys, to prevent attackers from accessing our log files.
The last method of protection was through the usage of a hash key.  Hash keys are another way to encrypt log files and prevent them from being intercepted or read by potential attackers.  Any security engineer or blue team member must understand how to protect, transport, and work with logs.  
 

- **Key Components:**
  * CySA+ Infrastructure Management
  * CySA+ Log, SIEM, and Email Analysis

<hr/>

# Appendix 

### CyberSecurity Roles and Required Skills:

| Job Title                     | Description                                                                                                | Required Skills                                                |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| **Security Analyst**          | Monitors systems for security breaches, investigates incidents, and implements security measures.            | Threat analysis, incident response, knowledge of security tools. |
| **Penetration Tester**        | Conducts simulated cyber attacks to identify vulnerabilities; requires ethical hacking skills.              | Ethical hacking, vulnerability assessment, programming skills.   |
| **Incident Responder**        | Responds to security incidents, analyzes and mitigates impact, and implements strategies for prevention.    | Incident response, forensics, knowledge of security frameworks.  |
| **Security Engineer**         | Designs, implements, and manages security systems; ensures the integrity and confidentiality of data.      | Network security, encryption, knowledge of security protocols.   |
| **Security Consultant**       | Provides expert advice, conducts risk assessments, and assists in developing and implementing security solutions. | Risk management, consulting skills, knowledge of compliance standards. |
| **Security Architect**        | Designs secure computer systems, networks, and applications; establishes security policies and standards.   | System architecture, cryptography, security framework knowledge. |
| **Cybersecurity Manager**     | Oversees cybersecurity strategy, manages teams, and ensures the implementation of effective security policies. | Leadership, strategic planning, communication skills.           |
| **SOC Analyst**               | Monitors, analyzes, and responds to security alerts in real-time; works in a Security Operations Center (SOC). | SIEM tools, incident detection, knowledge of threat landscapes. |
| **Network Security Engineer** | Focuses on securing network infrastructure, including firewalls, VPNs, and intrusion detection/prevention systems. | Network protocols, firewall management, security architecture. |
| **Threat Intelligence Analyst**| Gathers and analyzes information about cyber threats to provide timely intelligence for decision-making.    | Threat intelligence platforms, analysis tools, industry knowledge. |

<img src="images/img_1.png">

### Final Notes on IST894

  Throughout my program in cybersecurity analytics, I have learned and mastered several different skills.  Whether it was threat modeling, predictive analysis, SIEMS or general vulnerability testing, the program of IST 894 wrapped it all up into a single class of skills.  
  
In this course, all of my master's program skills were put to the test in simulated scenarios that an IT Security professional would face day to day.  One of the things that really helped to tether everything together was doing actual hands on labs that were reflective of each scope of work learned.

Overall, by learning a large scope of skills and processes related to cybersecurity, we have been taught to be well-rounded security professionals and also what to expect in our day to day.
The cybersecurity field is ever evolving, and it is impossible to cover every single topic even in a masters program.  What my capstone did teach me is to take the skills I have acquired by learning through application and continue to expand on them.
Acquiring a masters is just the beginning, as my drive to continue to learn will directly impact and direct my future professional career. 
I am happy to have completed this program and become part of the Penn State alumni.  #WEARE
#### Author: Carl Laneave (cjl29@psu.edu) 
<b><i>Penn State University Graduate Program, CyberSecurity Analytics, 2023</i></b>




