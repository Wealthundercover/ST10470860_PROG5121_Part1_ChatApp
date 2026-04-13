ChatApp Project - Part 1
Project Description
This Java-based Chat Application (Part 1) focuses on a secure User Authentication System. It handles user registration with strict validation rules, secure data storage within the application's runtime, and a login verification system.

The project follows a Modular Design pattern, separating the user interface (ChatApp.java), the business logic (Login.java), and automated quality assurance (LoginTest.java).

Features
Registration Validation:

Username: Must contain an underscore (_) and be no more than 5 characters.

Password: Minimum 8 characters, containing at least one uppercase letter, one number, and one special character.

Phone Number: Must start with the South African international code +27 and be 13 characters or fewer.

Authentication: Verifies user-entered credentials against stored registration data.

Unit Testing: Comprehensive JUnit tests ensure the validation logic is bug-free.

Getting Started
Prerequisites
JDK 11 or higher.

An IDE (NetBeans, IntelliJ, or Eclipse).

JUnit 4 library (for running tests).

How to Run
Run ChatApp.java to start the console application.

Follow the prompts to register a new user.

If registration is successful, proceed to login using the same credentials.

To verify logic integrity, run LoginTest.java as a Unit Test file.

References (Harvard Style)
Note: Ensure you replace [Year] with the current year of your studies.

Deitel, P.J. and Deitel, H.M. [Year]. Java: How to Program, Early Objects. 11th ed. Upper Saddle River: Pearson Education.

Farrell, J. [Year]. Java Programming. 9th ed. Boston: Cengage Learning.

Oracle. [Year]. Java Platform, Standard Edition 11 API Specification. [Online]. Available at: https://docs.oracle.com/en/java/javase/11/docs/api/index.html [Accessed 13 April 2026].

Schildt, H. [Year]. Java: The Complete Reference. 11th ed. New York: McGraw-Hill Education.
