Valerie J. Smith 
CS-305 Software Security Course
```
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client?
What issue did they want you to address?
     Artemis Financial is a fictional company that is requesting assistance with modernizing their operations
     and want to ensure that the software that they utilize contains current and effective software security.
What did you do particularly well in identifying their software security vulnerabilities? Why is it important 
to code securely? What value does software security add to a company’s overall wellbeing?
     Identifying the company’s needs for a recommended algorithm cipher and providing the status of their code against
     known security vulnerabilities via the use of the Maven OWASP tools are features that I was successful with.  
     The code presented for inspection was not up to date with the latest security challenges and provided a lot of
     potential for improvement.  It is important to code securely and to incorporate security measures in today’s 
     applications as there is a higher risk of security attacks by hackers than ever before.  The value that software
     security adds to a company’s well being is to ensure that their data and systems are secure and that their client’s
     are protected against malicious attackers.  This also protects the reputation of the company and guards 
     against financial loss.
What about the process of working through the vulnerability assessment did you find challenging or helpful?
     I found it very helpful to be able to view a report of the vulnerabilities present in the code using the
     Maven OWASP plugin.  This tool is very easy to use and provides a report that can be opened in the browser.
     From that report, each known vulnerability that is found can be further investigated and researched. This 
     tool creates a new report with every build of the code and makes it easy to ensure that new vulnerabilities
     are not introduced.
How did you approach the need to increase layers of security? What techniques or strategies would you use in the 
future to assess vulnerabilities and determine mitigation techniques?
     The layers of security implemented for this client included ensuring the use of the OWASP tool, the addition of 
     a hash cipher, the conversion to https from http with the addition of a self-signed certificate, and manual code 
     reviews as compared the Java best practices.  I found all of the information to be very helpful and a good 
     learning experience that I wish I would’ve had the chance to learn sooner. The OWASP tool would be a top 
     recommendation for a client in this similar situation as it is used in the development stages and provides
     a good opportunity for the developers to ensure that the code is secure before it is deployed in the production
     environment. 
               
How did you ensure the code and software application were functional and secure? After refactoring code, how did you
check to see whether you introduced new vulnerabilities?
     Ensuring that the code and software application were functional and secure required adding each addition to
     the code in one section at a time while ensuring that the adding functionality would produce the desired result.
     Utilizing the OWASP vulnerability tool before and after each addition ensured that new security vulnerabilities
      were not introduced to the code.
What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
     Coding practices such as input validation, spring security for endpoints, and proper error and exception handling 
     are useful and will be applied to future assignments.  The resources about using the Java Keytool are extremely 
     valuable to any Java developer and are in high demand for Java applications.
Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge,
and experience. What from this particular assignment might you want to showcase to a future employer?
     I would showcase to a future employer the ability to use the Java Keytool to work with various security certificates 
     and be able to demonstrate how to implement them into an application. As a developer that has worked as a software engineer
     for seven years, there are still those out there even at the senior developer level that do not know these tools and
     do not understand how to work with security certificates in a Java application.  The next item I would showcase would 
     be the ability to scan existing code with the OWASP plugin with Maven. This is a powerful tool that can assist the 
     development team with creating and refactoring code in a safe and secure way.  Both of these tools are highly valuable
     in today’s world of coding that need to be implemented to protect the potential employer’s company against malicious threats. 

```
