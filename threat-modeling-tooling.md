# The Role of Tooling in Threat Modeling, by [Zoe Braiterman](https://twitter.com/zbraiterman)

The practical value of threat modeling is about “People and collaboration over processes, methodologies, and tools”, as stated in the [Threat Modeling Manifesto](https://www.threatmodelingmanifesto.org) and various discussions amongst practitioners.  However, tooling certainly plays a role in the productive threat modeling. 


## Some useful features of software used for threat modeling 

### Threat Modeling as Code

Threat modeling as code enables developers to turn what’s in their job description, coding, into graphical representations of the systems they’re building that provide context for threat modeling activities. 

This category of tooling includes [pytm](https://owasp.org/www-project-pytm), an OWASP project led by [Izar Tarandach](https://twitter.com/izar_t).

Pytm is a Pythonic framework that achieves the following to facilitate threat modeling:

* Enable developers with the  to easily generate data flow diagrams or sequence diagrams, using [dot](https://graphviz.gitlab.io/) or [PlantUML](https://plantuml.com/)
* Allow security experts to supply threats to the system, based on vulnerabilities
* Generate a report that includes diagrams and findings


### More on automated reporting 

Potential threats that may impact a system are not limited to security threats. They also include privacy and compliance related threats. 

Adaptive tooling empowers users with automated reporting of these various types of threats to enable users to properly understand and mitigate the risks that face the systems within their organizations. 

For example, [Irius Risk](https://www.iriusrisk.com), allow users to create reports, including [compliance reports](https://www.iriusrisk.com/resources-blog/product-update-release-4.4), among the [analytics and reporting](https://www.iriusrisk.com/advanced-analytics-and-reporting) features the product includes.  


### What this means for you?

Some considerations in making decisions your team / organization may include the following.

* **The users of the threat modeling software:**  Developers? Security professionals? Product managers? Consider the goals and level of technical expertise of each user persona. 
* **The desired types of outputs:**  What types of visual representations, reporting, analytics and integration will be useful for your case?
* **The ongoing discussion and cross-functional collaboration it facilitates:**  What type of meaningful discussion is the tooling, and its outputs, to facilitate?


# Conclusion / Key Takeaways
