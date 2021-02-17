**secure-design-hackathon**
A collaborative activity for people to learn high level product security concepts, building upon their diverse skillsets and backgrounds



** General structure of a Hackathon**

1. Explain to participants what we expect them to submit for their solutions
2. Participants form teams and work on their solutions (with access to their team members and our mentorship over Slack, or another team communications platform.
3. Participants submit their solutions, and present at a later date (perhaps after a week or two). 


Assignment:   You are advising a development team in designing a web app that will accept payments to a non-profit organization. 

Things for participants to consider and explain in written form:

* What controls will you put into place to protect storage and transmission of cardholder data?
* What kinds of cardholder data will be processed from users?
* How will you encrypt that data, in transit and at rest? Why?
* To whom will you grant access to what cardholder data (refer to your answer to the previous question)?
* Web application firewall (WAF) configuration considerations
* What are some potential data privacy concerns, and what are some steps you would take to protect users’ data? Consider regulatory requirements, and steps you would take to implement them.



Deliverables participants may want to submit:

Threat modeling visuals (attack tree, data flow diagram, textual representation). You may also submit as pull request to the OWASP Threat Model Cookbook:  https://github.com/OWASP/threat-model-cookbook 
A questionnaire for a potential development team (along with possible answers and explanations for your choice of questions)
A list of answers to the questions we pose. 
Architectural diagrams (for more advanced participants)
Wireframes or user stories 


Very basic threat modeling related questions to answer:

* What are you building (Referencing your answers to the above questions)?
* What can go wrong?
* What could be overlooked or not addressed?
* How would you attack it?
* Have you read a news story lately that suggests an attack?
* What are you going to do about that?
* Did you do a good enough job?
