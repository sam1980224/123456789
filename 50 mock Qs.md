**Java Mock Exam (50 Questions)**

---

### **1. Git**

**Question 1:** What command is used to stage all changes in a Git repository for commit?

<details><summary>Answer</summary>
`git add .`
</details>

**Question 2:** What does the `git clone` command do?

<details><summary>Answer</summary>
It creates a copy of an existing repository.
</details>

**Question 3:** What is the purpose of `.gitignore`?

<details><summary>Answer</summary>
To specify files and directories that should be ignored by Git.
</details>

**Question 4:** How do you view the commit history in Git?

<details><summary>Answer</summary>
`git log`
</details>

**Question 5:** What does `git merge` do?

<details><summary>Answer</summary>
Combines changes from different branches into a single branch.
</details>

---

### **2. Entities**

**Question 6:** What is an entity in Java?

<details><summary>Answer</summary>
An entity is a class that represents a table in a database, with fields corresponding to columns.
</details>

**Question 7:** What annotation is commonly used to declare a class as an entity in Java?

<details><summary>Answer</summary>
`@Entity`
</details>

**Question 8:** In Clean Architecture, where do entities reside?

<details><summary>Answer</summary>
In the core domain layer.
</details>

**Question 9:** How does Java ensure entities are serializable?

<details><summary>Answer</summary>
By implementing the `Serializable` interface.
</details>

**Question 10:** What is a primary key in the context of entities?

<details><summary>Answer</summary>
A unique identifier for each record in a table.
</details>

---

### **3. Java Basics**

**Question 11:** What is the entry point for any Java application?

<details><summary>Answer</summary>
The `main` method (`public static void main(String[] args)`).
</details>

**Question 12:** How do you declare a constant in Java?

<details><summary>Answer</summary>
Using the `final` keyword.
</details>

**Question 13:** What is the difference between `==` and `.equals()`?

<details><summary>Answer</summary>
`==` checks reference equality, while `.equals()` checks value equality.
</details>

**Question 14:** What is the default value of an uninitialized `int` in Java?

<details><summary>Answer</summary>
`0`
</details>

**Question 15:** How are arrays declared in Java?

<details><summary>Answer</summary>
`int[] arr = new int[5];`
</details>

---

### **4. Object-Oriented Programming (OOP)**

**Question 16:** What are the four pillars of OOP?

<details><summary>Answer</summary>
Encapsulation, Inheritance, Polymorphism, and Abstraction.
</details>

**Question 17:** What is method overloading?

<details><summary>Answer</summary>
Defining multiple methods with the same name but different parameter lists.
</details>

**Question 18:** How is method overriding achieved in Java?

<details><summary>Answer</summary>
By providing a new implementation for a method in a subclass using the `@Override` annotation.
</details>

**Question 19:** What is the purpose of the `this` keyword?

<details><summary>Answer</summary>
To refer to the current instance of the class.
</details>

**Question 20:** What is the difference between an abstract class and an interface?

<details><summary>Answer</summary>
An abstract class can have implemented methods, while an interface cannot (before Java 8).
</details>

---

### **5. Interfaces**

**Question 21:** How do you declare an interface in Java?

<details><summary>Answer</summary>
Using the `interface` keyword.
</details>

**Question 22:** Can interfaces have constructors?

<details><summary>Answer</summary>
No, interfaces cannot have constructors.
</details>

**Question 23:** What is a marker interface?

<details><summary>Answer</summary>
An interface with no methods, used to signal information to the JVM.
</details>

**Question 24:** Can a class implement multiple interfaces?

<details><summary>Answer</summary>
Yes, a class can implement multiple interfaces.
</details>

**Question 25:** What happens if a class implements two interfaces with methods of the same signature?

<details><summary>Answer</summary>
The class must provide a single implementation for the method.
</details>

---

### **6. Java Swing & Unit Testing**

**Question 26:** What is the purpose of the `JFrame` class in Java Swing?

<details><summary>Answer</summary>
It provides a window to host components in a GUI.
</details>

**Question 27:** What annotation is used to mark a test in JUnit?

<details><summary>Answer</summary>
`@Test`
</details>

**Question 28:** How do you simulate a button click in a Swing application?

<details><summary>Answer</summary>
Using the `doClick()` method on a `JButton`.
</details>

**Question 29:** What does the `assertEquals` method in JUnit do?

<details><summary>Answer</summary>
Checks if two values are equal.
</details>

**Question 30:** What is a test suite in JUnit?

<details><summary>Answer</summary>
A collection of test cases that can be executed together.
</details>

---

### **7. SOLID Principles**

**Question 31:** What does the “O” in SOLID stand for?

<details><summary>Answer</summary>
Open/Closed Principle.
</details>

**Question 32:** What is the Liskov Substitution Principle?

<details><summary>Answer</summary>
Subtypes must be substitutable for their base types without altering the correctness of the program.
</details>

**Question 33:** How does the Dependency Inversion Principle promote decoupling?

<details><summary>Answer</summary>
By depending on abstractions rather than concrete implementations.
</details>

**Question 34:** What is the Single Responsibility Principle?

<details><summary>Answer</summary>
A class should have only one reason to change.
</details>

**Question 35:** What is Interface Segregation Principle?

<details><summary>Answer</summary>
Clients should not be forced to depend on interfaces they do not use.
</details>

---

### **8. Exceptions**

**Question 36:** How do you declare a method that throws an exception?

<details><summary>Answer</summary>
By adding `throws ExceptionType` in the method signature.
</details>

**Question 37:** What is the difference between checked and unchecked exceptions?

<details><summary>Answer</summary>
Checked exceptions must be handled or declared, while unchecked exceptions do not require explicit handling.
</details>

**Question 38:** What is the parent class of all exceptions in Java?

<details><summary>Answer</summary>
`Throwable`
</details>

**Question 39:** What happens if an exception is not caught in a program?

<details><summary>Answer</summary>
The program terminates abnormally.
</details>

**Question 40:** How do you create a custom exception?

<details><summary>Answer</summary>
By extending the `Exception` or `RuntimeException` class.
</details>

---

### **9. Design Patterns**

**Question 41:** What is the Singleton pattern?

<details><summary>Answer</summary>
A design pattern that ensures only one instance of a class exists.
</details>

**Question 42:** What is the Factory Method pattern?

<details><summary>Answer</summary>
A pattern that provides an interface for creating objects, allowing subclasses to alter the type of objects created.
</details>

**Question 43:** What is the Strategy pattern?

<details><summary>Answer</summary>
A pattern that enables selecting an algorithm's behavior at runtime.
</details>

**Question 44:** What is the Observer pattern?

<details><summary>Answer</summary>
A pattern where an object (subject) notifies other objects (observers) of state changes.
</details>

**Question 45:** What is the Builder pattern?

<details><summary>Answer</summary>
A pattern that constructs complex objects step by step.
</details>

---

### **10. Regex**

**Question 46:** Write a regex to match an email address.

<details><summary>Answer</summary>
`^[\w.%+-]+@[\w.-]+\.[a-zA-Z]{2,}$`
</details>

**Question 47:** Write a regex to match a string starting with a digit.

<details><summary>Answer</summary>
`^\d.*`
</details>

**Question 48:** Write a regex to match a string that contains only lowercase letters.

<details><summary>Answer</summary>
`^[a-z]+$`
</details>

**Question 49:** Write a regex to match a phone number in the format (XXX) XXX-XXXX.

<details><summary>Answer</summary>
`^\(\d{3}\) \d{3}-\d{4}$`
</details>

**Question 50:** Write a regex to match a password with at least one uppercase letter, one digit, and one special character.

<details><summary>Answer</summary>
`^(?=.*[A-Z])(?=.*\d)(?=.*[@#$%^&+=]).{8,}$`
</details>

---

This is formatted to display collapsible answers in a Markdown-compatible viewer. Let me know if you need help with rendering or additional modifications!
