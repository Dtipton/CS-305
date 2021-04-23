# CS-305

1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The client was Artemis Financial, They develop indiviudlized financial palns for savings, retierment, investments, and insurance. They were looking to add a file verificaiton step to help ensure secure communications.

2. What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I think I did a good job helping set up the SHA-256 encryption so that the files were secure overall. Secure code is important so that you can reduce the chance of someone being able to access personal files or company documents that can contain social security information or bank numbers. The vaule this brings is two fold, it allows your customers a sense of security and allows you to worry less about someone stealing information and leading to lawsuits.

3. What about the process of working through the vulnerability assessment did you find challenging or helpful?

I found the process of setting up the maven project to be the hardest. It was the first time I've ever setup a web application in the Java language before.

4. How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques

I worked my way from the bottom to the top trying to think of issues that could arrise if someone got through each layer. In the future I would make more use of CVE databases to help find better solutions to the threats.

5. How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

I ensured was functional and secure by both doing static and dynamic testing to look any use cases that could fail along with checkind dependencies for any new vulnerablities.


6. What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

Maven for sure, the amount of tools that you can use and just the general building of projects through it is very nice and will help a lot I think.

7. Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would probably show that I can run dependency checks and that I know how to build certificates if needed.
