# RISK-MANAGEMENT-WITH-FAIR
Risk management and risk quantification  Stay tuned


# Risk Assessment

My collection of files from my studies.

This will determine the risk to Mass Driver Research, Inc.

This will cover the 4 main risk assessment parameters of FAIR and the OWASP top ten definitions.

Table of Contents
=================

   * [Risk Assessment](#risk-assessment)
   * [Introduction to assessing risk with the FAIR model.](#introduction-to-assessing-risk-with-the-fair-model)
         * [What is Fair?](#what-is-fair)
         * [How does Fair work?](#how-does-fair-work)
         * [When can I use Fair?](#when-can-i-use-fair)
      * [4 Main Risk Assessment Parameters of FAIR](#4-main-risk-assessment-parameters-of-fair)
         * [Other FAIR Definitions](#other-fair-definitions)
      * [Definitions of the OWASP Top 10](#definitions-of-the-owasp-top-10)

# Introduction to assessing risk with the FAIR model

### What is Fair?
FAIR is an internationally accepted quantitative risk analysis framework that describes what risk is, how it works and how to quantify it.
The main selling point of FAIR focuses on demonstrating the financial results of cyber security risk.


### How does Fair work?
Fair helps you make sound decisions from measured cyber security risk assessment.
The way the measurements work, is that you take the results of a pentest or some other security assessment and you assess the results; you take the found vulnerabilities and try to determine the attack surface, probability of an attack, and how hard is it to exploit and from there you can draw conclusions that can summarized into financial impact TL;DRs.


### When can I use Fair?

Once you've compiled quantifiable information on the client's infrastructure.


## 4 Main Risk Assessment Parameters of FAIR

Definitions: 

* Threat capability: is the estimated capability of the threat agent or agents.

* Contact frequency: Frequency of encountering the risk.

* Probability: Likelihood of the threat causing damage.

* Resistance Strength: How difficult it is to exploit.

### Other FAIR Definitions

* Threat Agent Model

People, things, *or* groups of either.

Not all threats imply malicious intent, either.

# # Definitions of the OWASP Top 10

OWASP tracked the breaches and incidents of major governments and organizations.

They compiled the top ten most common causes of breaches.

There is a broad consensus from security experts that these are the most statistically likely vulnerabilities to affect an infrastructure, application, or human-mediated processes.

It is important to read about them and stay up to date because they create significant security vulnerabilities that are likely to affect your organization’s ability to maintain confidentiality, integrity, and availability.

If you don't read about them, you stay in the dark on the most important and common vulnerabilities. You can be more easily breached as a result, thus causing you to lose the respect of your customers, ownership, and other important stakeholders.
    
	• Injection - > Inject unauthorized or foreign code into a piece of software to get it to do something it was not otherwise authorized to perform.
Metaphor: https://xkcd.com/327/
    
	• Broken Authentication - > Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.
Metaphor: Being able to use your neighbor's key to access your house.
    
	• Sensitive Data Exposure - > Application functions related to authentication and session management are often implemented incorrectly, allowing attackers to compromise passwords, keys, or session tokens, or to exploit other implementation flaws to assume other users’ identities temporarily or permanently.
Metaphor: Not using a condom.
    
	• XML External Entities (XXE) - > Many web applications and APIs do not properly protect sensitive data, such as financial, healthcare, and PII. Attackers may steal or modify such weakly protected data to conduct credit card fraud, identity theft, or other crimes. Sensitive data may be compromised without extra protection, such as encryption at rest or in transit, and requires special precautions when exchanged with the browser.
Metaphor: Foreign saboteurs in the base!
    
	• Security Misconfiguration - > Security misconfiguration is the most commonly seen issue. This is commonly a result of insecure default configurations, incomplete or ad hoc configurations, open cloud storage, misconfigured HTTP headers, and verbose error messages containing sensitive information. Not only must all operating systems, frameworks, libraries, and applications be securely configured, but they must be patched/upgraded in a timely fashion.
Metaphor: Electrician miswires the house (Could burn down or electrocute you)!
    
	• Cross-Site Scripting (aka XSS) - > XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create HTML or JavaScript. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.
Metaphor: Alex Jones as your neighbors! https://www.youtube.com/watch?v=XRSg6MS5xqA
    
	• Insecure Deserialization - > Insecure deserialization often leads to remote code execution. Even if deserialization flaws do not result in remote code execution, they can be used to perform attacks, including replay attacks, injection attacks, and privilege escalation attacks.
Metaphor: Someone taints your package en route (received an opened package from amazon!)
    
	• Broken Access Control - > Restrictions on what authenticated users are allowed to do are often not properly enforced. Attackers can exploit these flaws to access unauthorized functionality and/or data, such as access to other users’ accounts, view sensitive files, modify other users’ data, change access rights, etc.
Metaphor: Bank robber can pretend to be you, and get the same access to your bank account!

	• Using components with known vulnerabilities - > Components, such as libraries, frameworks, and other software modules, run with the same privileges as the application. If a vulnerable component is exploited, such an attack can facilitate serious data loss or server takeover. Applications and APIs using components with known vulnerabilities may undermine application defenses and enable various attacks and impacts.
Metaphor: Using a broken condom.

	• Insufficient logging and monitoring - > Insufficient logging and monitoring, coupled with missing or ineffective integration with incident response, allows attackers to further attack systems, maintain persistence, pivot to more systems, and tamper, extract, or destroy data. Most breach studies show time to detect a breach is over 200 days, typically detected by external parties rather than internal processes or monitoring.
Metaphor: Toddler runs out into traffic when the parent stops monitoring it.



