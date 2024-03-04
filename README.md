# CS-305-
SNHU 2024 CS 305 Final Project 

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?:

Artemis Financial is looking to update and secure their code base to ensure that their customers and employees data and information is secure and up to date with modern standards. They wanted us to add a file verification step to their code base and check for potential vulnerabilities in their dependencies package.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
What part of the vulnerability assessment was challenging or helpful to you?

When I ran the OWASP vulnerability check I suggested to the client to update all outdated packages in their code base. It is important to code securely and to constantly check for potential new security issues so that your data and code base is always locked down as much as it can be. At the end of the day if your data isn't secure then no one will want to use your platform. The most challenging thing to me in the vulnerability assessment was learning how to identify false positives in the report and then to suppress them. It took a lot of research to find what type of things would potentially show up as false positives. 


How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased the layers of security by adding the SHA-256 cipher to the code base making sure that all the data was encrypted to a high standard. I would continue to use the OWASP tool and manually review the code base on a normal basis to maintain a high level of confidence in the security of the application.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I would run the debug functional in my code editor to check for any potential issues in the funciton of the site. After every new update to the code I would re run the de bug and build process to make sure my changes didn't hurt the site in any new ways. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used a lot of external resources when learning how to use these new security features that I have not used before including StackOverflow and online security publications. I am a big believer in reaching out to other developers to bounce ideas off of and to ask questions when running into potential issues during development.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I think showing the additional of the cipher and generating certificates is a great skill to show future employers and I know I am already using these skills in my development job.
