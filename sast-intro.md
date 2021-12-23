# Developer-Centered Security


## What is a web application vulnerability?

A [vulnerability](https://owasp.org/www-community/vulnerabilities/) is a hole or a weakness in an application that allows an attacker to cause harm to the stakeholders of an application.


## Discovering new web app vulnerabilities

Hopefully, newly discovered vulnerabilities (also called "0-days"), are reported by ethical hackers, in a responsible way.

* [National Vulnerability Database](https://nvd.nist.gov)
* [Snyk Open Source Vulnerability Database](https://security.snyk.io)

## [Static Application Security Testing (SAST) tools](https://owasp.org/www-community/Source_Code_Analysis_Tools), such as [Snyk](https://snyk.io/) scan your applications for known vulnerabilities


## Scans projects for:

* Dependencies
* Source code


## What's returned (referencing a sample SQL Injection vulnerability found in my fork of [CSPF-Founder's JavaVulnerableLab demo application](https://github.com/CSPF-Founder/JavaVulnerableLab)).

* Vulnerabilities and license issues found in dependencies
* Vulnerabilities, and severity score per vulnerability found in code ![](/images/snyk_code_java_vulnerable_lab_sqli_score.png)
* Description, file and line number of each discovered vulnerability ![](/images/snyk_java_sqli_data_flow_example.png)
* Remediation advice
* [Need-to-know educational content](https://learn.snyk.io/lessons/sql-injection/java/) for each discovered vulnerability  ![](/images/snyk_learn_prompt.png)


... And continuous alerts and updates ![](/images/snyk-vulnerability-email-alert.png)
