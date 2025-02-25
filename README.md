# CS-305

Q: Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

A: Artemis Financial is a consulting company that develops individualized financial plans for its customers. The financial plans include savings, retirement, investments, and insurance. Artemis Financial wants to modernize its operations. As a crucial part of the success of its custom software, the company also wants to use the latest and most effective software security. The company is seeking Global Rain’s expertise about how to protect the organization from external threats.


Q: What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

A: I reviewed the scenario to interpret the client's needs and potential threats and attacks associated with its application and software security requirements, then referred to the vulnerability assessment process flow diagram and thought about the functionality of the software application to identify which areas of security apply to Artemis Financial’s web application. Then I manually inspected the code, integrated the dependency-check plug-in, and then created an action list that documents how to fix each vulnerability.

Q: Which part of the vulnerability assessment was challenging or helpful to you?

A: I had some difficulty picking out what things from the vulnerability assessment process flow diagram would apply to this problem. Furthermore I had a difficult time figuring out how to generate a vulnerability report after running the static testing.

Q: How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use? 

A: I refactored code to use an algorithm cipher, generated a self-signed certificate using the Java Keytool, and converted to HTTPS protocol. In the future I may continue to use OWASP to generate vulnerability reports.

Q: How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

A: I made sure to sanitize and validate input that was previously entered as raw text.

Q: What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

A: Asked for help from teacher, OWASP dependency check, Eclipse IDE, Command Prompt

Q: Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

A: That I can continue to learn and ask for help when I am running into trouble.
