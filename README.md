# CS305-Final-Project

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Artemis Financial is a financial consulting company that wants to modernize their operations. They want the most up to date and effective software security. Their main goal is to add a level of security to their file verification on their website. 

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**

I was able to implement SHA-256 cryptographic hashing in their pre existing code to fulfill their needs for a secure web application. Secure coding is essential especially in this field because it protects the sensitive financial data from unauthorized access. Because of the field Artemis Financial is in, even the slightest security breach is very bad due to their handling of retirement plans and investment data. Sotware security directly effects the companies well-being by creating trust between the company and its clients.

**Which part of the vulnerability assessment was challenging or helpful to you?**

The hardest part of this assignment was getting a secure webpage. After having created a selfsigned certificate, the browser would still explicitly show the page was unsecure. After having created the certificate and updating the dependencies, everything ended up working out in the end. 

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

The dependencies were mostly solved with updating them as most were out of date. For the ones there weren't fixed with updates, they were false positives, so I suppressed those as they weren't critical. In the future I would take a deep dive into each vulnerability and figure out how critical each one is and address each one based on how critical they are. 

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

After implementing the SGA-256 checksum functionality, I used several verification methods to ensure the application was both functional and secure. After refactoring the code I used a vulnerability checker to see if there were any new or remaining vulnerabilities needing to be addressed.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

The keytool utility used seems like something that will prove helpful in the future. It was my first time using it and it was a very pleasant learning experience. The dependency check also seems reliable and something I can utilize in the future.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

I would show a future employer exactly what was worked on in this final project. Everything we learned throughout this class was put to use in this final project and having most of the tools and resources being new to me, this entire class was very useful to me. From the implementations to the certificate creating and updating of dependencies, it is all something I think I can use to showcase my skills and knowledge.
