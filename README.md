# Cucumber-with-Selenium_Behaviour-Driven-Development-Tutorial
**Behavior-driven development is a software development process that is derived from Test-Driven Development (TDD) concept.**


BDD simply focuses on:
*	**Where** to start in the process
*	**What** to test and what not to test
*	**How much** to test in one go
*	**What** to call the tests
*	**How** to understand why a test fails

In this tutorial I have implemented in my project a BDD tool known as **Cucumber**. Cucumber tool is based on the Behavior Driven Development process that bridges the gap between non-developers and developers. As it uses a plain text format called **Gherkin** it makes the code understandable for non-developers (for example for clients). To make the testing phase even easier I also took advantage of **Selenium Framework** for automating web browser. Before starting out with the project the following libraries must be referenced inside the project file. 

**Selenium jar files:** (Downloaded from Selenium Official Website)
* Selenium-server-standalone

**Cucumber jar files** (Downloaded from Maven Repository)
* Cucumber-core
* Cucumber-html
* cobertura code coverage
* Cucumber-java
* Cucumber-junit
* Cucumber-jvm-deps
* Cucumber-reporting
* Hemcrest-core
* Gherkin
* Junit

![alt text](https://i.ibb.co/4wqjD3x/Altug-Project-Organisation.png)


Tested **scenario** was the Reset functionality of the login form placed inside the demo website that is available at http://demo.guru99.com/V4/

In the output I wanted to see the following:

* Launch browser.
* Demo site is loaded.
* Username and password I provided in the Step definiton are placed on the login page.
* All values are resetted.

![alt text](https://i.ibb.co/xmjx6z3/Altug-Feature-File.png)

![alt text](https://i.ibb.co/fHfxNw7/Altug-Runner-File.png)

![alt text](https://i.ibb.co/YBhK2mQ/aaa.png)

![alt text](https://i.ibb.co/w7Nv2X9/Altug-Test-Result.png)

![alt text](https://i.ibb.co/YWmN9fQ/Altug-Junit.png)

![alt text](https://i.ibb.co/NjJ2w9c/altug-output.png)
