# SoftwareSecurity

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that develops personalized financial plans for its clients, including savings, retirement, investments, and insurance. The company sought to modernize its software, particularly to secure its public web interface and protect sensitive financial information. My task was to identify security vulnerabilities in their existing application and implement solutions to enhance the software's security, ensuring that it met current standards for secure communication and data protection.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I was thorough in identifying and documenting the security vulnerabilities within Artemis Financial’s application. I conducted a detailed manual review and utilized a static analysis tool to uncover potential risks such as SQL injection, XSS, and CSRF vulnerabilities. Coding securely is crucial because it protects sensitive data from unauthorized access and ensures the integrity and availability of services. Strong software security practices help maintain customer trust, comply with regulatory requirements, and prevent costly breaches, thus contributing to the company's reputation and financial stability.

3. Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the vulnerability assessment was ensuring that all identified vulnerabilities were accurately addressed without introducing new issues during the refactoring process. However, this challenge was also helpful as it deepened my understanding of secure coding practices and the importance of thorough testing post-refactor.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by implementing prepared statements to prevent SQL injection, using output encoding to mitigate XSS risks, and introducing anti-CSRF tokens. Additionally, I upgraded outdated dependencies that posed security risks. In the future, I would continue using tools like Maven Dependency-Check for early detection of vulnerabilities and employ comprehensive testing frameworks to assess and validate the effectiveness of mitigation techniques.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I ensured the functionality and security of the code by conducting thorough testing, including unit tests, integration tests, and security-focused tests. After refactoring, I re-ran static analysis tools and performed manual code reviews to verify that no new vulnerabilities were introduced. This approach helped maintain the integrity and security of the application.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I utilized tools such as Maven Dependency-Check for static analysis and secure coding practices like input validation, output encoding, and the use of strong encryption algorithms. These resources and practices will be invaluable in future assignments, particularly in projects that require a focus on software security and vulnerability mitigation.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignment, I would showcase my ability to conduct a thorough vulnerability assessment, implement secure coding practices, and document the entire process in a clear and professional manner. This demonstrates not only my technical skills but also my commitment to delivering secure and reliable software solutions, which is highly valuable to any employer in the tech industry.






