# ChatApp - Part 1: User Authentication System
**Developer:** Ngcebo Magagula
**Project Version:** 1.0.0
**Date:** April 2026

## 1. Project Overview
This Java-based Chat Application (Part 1) focuses on a secure **User Authentication System**. The goal is to provide a robust gateway where users must register with strict data integrity rules before they are granted access to the application.

The project is built using a **Modular Design** pattern to ensure a clean separation between the user interface (Console), the business logic (Validation), and quality assurance (Unit Testing).

## 2. Feature Implementation
I have implemented specific validation logic to ensure that user data meets high security and formatting standards:

| Feature | Requirement | Logic Implementation |
| :--- | :--- | :--- |
| **Username** | Underscore + Max 5 chars | `checkUserName()` ensures the username contains `_` and validates length. |
| **Password** | Complexity Rules | `checkPasswordComplexity()` verifies at least 8 chars, one uppercase, one digit, and one special character. |
| **Phone Number** | SA Format | `checkCellPhoneNumber()` validates the `+27` prefix and length limit. |
| **Authentication**| Secure Login | `loginUser()` performs a secure equality check against stored credentials. |
| **Unit Testing** | Verified Code | `LoginTest.java` uses JUnit to automate the testing of all logic methods. |

## 3. How to Run the Application
1. **Open the Project:** Load the `com.mycompany.chatapp` package into your IDE (NetBeans, IntelliJ, or Eclipse).
2. **Execute Main:** Run `ChatApp.java`.
3. **Register:** Follow the console prompts. If you enter invalid data, the app will provide specific feedback.
4. **Login:** Once successfully registered, enter your credentials to see the personalized welcome message.
5. **Run Tests:** Right-click `LoginTest.java` and select "Run File" or "Test File" to view the JUnit report.

   ## 📺 Project Presentation
You can watch the full technical walkthrough and demonstration of this application on YouTube:

**Link:** [Watch the Presentation Here](https://youtu.be/6yxX21c1gg4)

---

## 4. References (Harvard Style)
* **Bloch, J.** 2018. *Effective Java*. 3rd ed. Boston: Addison-Wesley.
* **Deitel, P.J. & Deitel, H.M.** 2017. *Java: How to Program, Early Objects*. 11th ed. Upper Saddle River: Pearson Education.
* **Oracle.** 2026. *Class String*. [Online]. Available at: https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/String.html [Accessed 13 April 2026].
* **Vogel, L.** 2021. *Unit Testing with JUnit - Tutorial*. [Online]. Available at: https://www.vogella.com/tutorials/JUnit/article.html [Accessed 13 April 2026].

