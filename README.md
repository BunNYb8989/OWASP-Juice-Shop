# OWASP-Juice-Shop

Task 1
Open for business!

Within this room, we will look at OWASP's TOP 10 vulnerabilities in web applications. You will find these in all types of web applications. But for today we will be looking at OWASP's own creation, Juice Shop!


![vjfcwid](https://github.com/user-attachments/assets/93d08f2b-a2e0-4f24-a5cf-be682172bfba)


Juice Shop is a large application so we will not be covering every topic from the top 10.

We will, however, cover the following topics which we recommend you take a look at as you progress through this room.

<------------------------------------------------->

Injection

Broken Authentication

Sensitive Data Exposure

Broken Access Control

Cross-Site Scripting XSS



Task 2
Let's go on an adventure!

Before we get into the actual hacking part, it's good to have a look around. In Burp, set the Intercept mode to off and then browse around the site. This allows Burp to log different requests from the server that may be helpful later. 

This is called walking through the application, which is also a form of reconnaissance!
![YFWDP5v](https://github.com/user-attachments/assets/0a472eeb-65e9-4c9a-8cc5-b1c6740a66a9)


Question #1: What's the Administrator's email address?

admin@juice-sh.op

![AzJ3FAM](https://github.com/user-attachments/assets/73203c15-3c33-4995-8db4-16e35f74a18c)

Question #2: What parameter is used for searching? 

q

![RCFw2tB](https://github.com/user-attachments/assets/02714aee-763b-42d9-b720-918be08b4889)

If we google "replicator" we will get the results indicating that it is from a TV show called Star Trek

Question #3: What show does Jim reference in his review? 

Star Trek


Task 3
Inject the juice

![uwXqDdH](https://github.com/user-attachments/assets/ef23dbdd-26ae-413b-9f28-0e6767efd8c9)

This task will be focusing on injection vulnerabilities. Injection vulnerabilities are quite dangerous to a company as they can potentially cause downtime and/or loss of data. Identifying injection points within a web application is usually quite simple, as most of them will return an error. There are many types of injection attacks, some of them are:

SQL Injection

SQL Injection is when an attacker enters a malicious or malformed query to either retrieve or tamper data from a database. And in some cases, log into accounts.

Command Injection

Command Injection is when web applications take input or user-controlled data and run them as system commands. An attacker may tamper with this data to execute their own system commands. This can be seen in applications that perform misconfigured ping tests. 

Email Injection

Email injection is a security vulnerability that allows malicious users to send email messages without prior authorization by the email server. These occur when the attacker adds extra data to fields, which are not interpreted by the server correctly. 

Question #1: Log into the administrator account!

































Task 4
Who broke my lock?!

























Task 5
AH! Don't look!
































Task 6
Who's flying this thing?












































Task 7
Where did that come from?
























































Task 8
Exploration!
