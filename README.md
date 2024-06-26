
# InterviewQuestions

This project is for me to store all relevant interview questions I come across for studying. I will store study questions here at first, 
then eventually move them to a database, implement a backend, then implement a frontend

# Table of contents
<ol>
<li>Java</li>
<li>BackEnd</li>
<li>FrontEnd</li>
<ol>
<li>HTML</li>
<li>CSS</li>
</ol>
<li>Case Study 1</li>
</ol>

## Java
Why is Java popular? 

It is popular because it is an object oriented language and it has platform independence

What is platform independence?

I can build a Java program once anywhere, and it can run on any operating system. 

Explain:

When Java files are complied, we get Java class files. These class files have 
bytecode that a JVMs(Java Virtual Machine) will convert into 
executable instructions for the respective Operating System.



## BackEnd 

## FrontEnd
<ol>
<li>What are goes in the head element?</li>
<ul>
<li>title: title of the doc</li>
<li>style</li>
<li>meta</li>
<li>link</li>
<li>script</li>
<li>base</li>
</ul>
<li>
What are some basic design elements?</li>
<p>size, color, line, texture</p>

<li>What is load balancing?</li>
<p>Distribution of all incoming network traffic across backend servers</p>

<li>What does NPM stand for?</li>
<p>Node Package Manager</p>

<li>What is scope?</li>
<p>It is how variables are accessed/referenced based on the location in the code
Ex: a function variable will cease to exist once a function is left.
a global variable will always be visible</p>

<li>What is CrossScripting?</li>
<p>An attack where malicious script is 
injected into a web application viewed by other users</p>
<li>What is SOLID?</li>
<ol>
<li>
Single Responsibility Principle (SRP):
This principle states that a class should have only one reason to change. 
In other words, a class should have a single responsibility or job. 
This helps keep classes focused, making them easier to understand, maintain, and extend.
</li>
<li>
Open-Closed Principle (OCP):
The Open-Closed Principle suggests that software entities (such as classes, modules, or functions) should be open for extension but closed for modification. This means that you should be able to extend the behavior of a system without altering its source code.
</li>
<li>
Liskov Substitution Principle (LSP):
This principle states that objects of a superclass should be replaceable with objects of a subclass without affecting the correctness of the program. In other words, a subclass should be able to substitute for its superclass without altering the desirable properties of the program.
</li>
<li>
Interface Segregation Principle (ISP):
The Interface Segregation Principle suggests that clients should not be forced to depend on interfaces they do not use. It encourages the creation of smaller, specific interfaces rather than large, general-purpose ones. This helps to prevent "fat" interfaces that contain more methods than necessary.
</li>
<li>
Dependency Inversion Principle (DIP):
The Dependency Inversion Principle advocates that high-level modules should not depend on low-level modules. 
Instead, both should depend on abstractions (e.g., interfaces or abstract classes). 
Additionally, abstractions should not depend on details; rather, details should depend on abstractions.
</li>
</ol>
<br>
<li>What is an IIFE?</li>
<p>Immediately Invoked Function Expression: Executes immediately after creation</p>
</ol>

### HTML - HyperText Markup Language
<ol>
<li>What is an attribute in HTML?</li>
<p style="color: red">Attributes are properties that can be added to an HTML tag 
to change the way it behaves/displays. <br>
For example: the "style" attribute was added to change the text color to red
</p>
<li>What are meta tags in HTML?</li>
<p>Meta tags are tags that go inside the head tag used for the header<br>
Example: charset="UTF-8", name="description"</p>
</ol>

### CSS - Cascade Style Sheet
<ol>
<li>What are different selectors used in CSS?</li>
<ol>
<li>universal targets the whole page: *</li>
<li>element targets a specific tag: ul</li>
<li>id targets an id name: #</li>
<li>class targets a class name: .</li>
</ol>
</ol>

### Case Study 1
Question: You have been hired as a Quality Engineer at a software development company that specializes in developing mobile applications. The company has recently released a new mobile app that has received mixed reviews from users. 
While some users appreciate its features and functionality, others have reported encountering bugs and usability issues.

Problem: The reviews state there are bugs and usability issues that the users are experiencing with the new app. 

2 Impacts: This is hurting user satisfaction and market success shown by the mixed reviews

Ways to move forward: Analyze the reviews, to identify how many different possible issues there are. 
Have the ability to leave tags with a review, preferably established tags, to make it easier to locate the issue.
We can send out surveys if it is possible, or have a ticket/bug system in place, having customers address specific questions.
Have our testers run through the application.