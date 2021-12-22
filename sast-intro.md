# SAST Intro


## What is a web application vulnerability?

A [vulnerability](https://owasp.org/www-community/vulnerabilities/) is a hole or a weakness in an application that allows an attacker to cause harm to the stakeholders of an application.


## Discovering new web app vulnerabilities

Hopefully, newly discovered vulnerabilities (also called "0-days"), are reported by ethical hackers, in a responsible way.

* [National Vulnerability Database](https://nvd.nist.gov)
* [Snyk Open Source Vulnerability Database](https://security.snyk.io)

## [Static Application Security Testing (SAST) tools](https://owasp.org/www-community/Source_Code_Analysis_Tools), such as [Snyk](https://snyk.io/) scan your applications for known vulnerabilities


## What's returned, based on a scan

For dependencies:
* Vulnerabilities
* License issues


For source code:
* Vulnerabilities, and severity score per vulnerability
* File and line number of each discovered vulnerability
* [Need-to-know educational content](https://learn.snyk.io/) for each discovered vulnerability


... And provides continuous alerts and updates ![](/images/snyk-vulnerability-email-alert.png)
