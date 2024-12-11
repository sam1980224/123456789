**Java Mock Exam (50 Questions)**

---

### **1. Git**

**Question 1:** What command is used to stage all changes in a Git repository for commit?

**Answer:** `git add .`

**Question 2:** What does the `git clone` command do?

**Answer:** It creates a copy of an existing repository.

**Question 3:** What is the purpose of `.gitignore`?

**Answer:** To specify files and directories that should be ignored by Git.

**Question 4:** How do you view the commit history in Git?

**Answer:** `git log`

**Question 5:** What does `git merge` do?

**Answer:** Combines changes from different branches into a single branch.

---

### **2. Entities**

**Question 6:** What is an entity in Java?

**Answer:** An entity is a class that represents a table in a database, with fields corresponding to columns.

**Question 7:** What annotation is commonly used to declare a class as an entity in Java?

**Answer:** `@Entity`

**Question 8:** In Clean Architecture, where do entities reside?

**Answer:** In the core domain layer.

**Question 9:** How does Java ensure entities are serializable?

**Answer:** By implementing the `Serializable` interface.

**Question 10:** What is a primary key in the context of entities?

**Answer:** A unique identifier for each record in a table.

---

### **3. Java Basics**

**Question 11:** What is the entry point for any Java application?

**Answer:** The `main` method (`public static void main(String[] args)`).

**Question 12:** How do you declare a constant in Java?

**Answer:** Using the `final` keyword.

**Question 13:** What is the difference between `==` and `.equals()`?

**Answer:** `==` checks reference equality, while `.equals()` checks value equality.

**Question 14:** What is the default value of an uninitialized `int` in Java?

**Answer:** `0`

**Question 15:** How are arrays declared in Java?

**Answer:** `int[] arr = new int[5];`

---

### **4. Object-Oriented Programming (OOP)**

**Question 16:** What are the four pillars of OOP?

**Answer:** Encapsulation, Inheritance, Polymorphism, and Abstraction.

**Question 17:** What is method overloading?

**Answer:** Defining multiple methods with the same name but different parameter lists.

**Question 18:** How is method overriding achieved in Java?

**Answer:** By providing a new implementation for a method in a subclass using the `@Override` annotation.

**Question 19:** What is the purpose of the `this` keyword?

**Answer:** To refer to the current instance of the class.

**Question 20:** What is the difference between an abstract class and an interface?

**Answer:** An abstract class can have implemented methods, while an interface cannot (before Java 8).

---

### **5. Interfaces**

**Question 21:** How do you declare an interface in Java?

**Answer:** Using the `interface` keyword.

**Question 22:** Can interfaces have constructors?

**Answer:** No, interfaces cannot have constructors.

**Question 23:** What is a marker interface?

**Answer:** An interface with no methods, used to signal information to the JVM.

**Question 24:** Can a class implement multiple interfaces?

**Answer:** Yes, a class can implement multiple interfaces.

**Question 25:** What happens if a class implements two interfaces with methods of the same signature?

**Answer:** The class must provide a single implementation for the method.

---

### **6. Java Swing & Unit Testing**

**Question 26:** What is the purpose of the `JFrame` class in Java Swing?

**Answer:** It provides a window to host components in a GUI.

**Question 27:** What annotation is used to mark a test in JUnit?

**Answer:** `@Test`

**Question 28:** How do you simulate a button click in a Swing application?

**Answer:** Using the `doClick()` method on a `JButton`.

**Question 29:** What does the `assertEquals` method in JUnit do?

**Answer:** Checks if two values are equal.

**Question 30:** What is a test suite in JUnit?

**Answer:** A collection of test cases that can be executed together.

---

### **7. SOLID Principles**

**Question 31:** What does the “O” in SOLID stand for?

**Answer:** Open/Closed Principle.

**Question 32:** What is the Liskov Substitution Principle?

**Answer:** Subtypes must be substitutable for their base types without altering the correctness of the program.

**Question 33:** How does the Dependency Inversion Principle promote decoupling?

**Answer:** By depending on abstractions rather than concrete implementations.

**Question 34:** What is the Single Responsibility Principle?

**Answer:** A class should have only one reason to change.

**Question 35:** What is Interface Segregation Principle?

**Answer:** Clients should not be forced to depend on interfaces they do not use.

---

### **8. Exceptions**

**Question 36:** How do you declare a method that throws an exception?

**Answer:** By adding `throws ExceptionType` in the method signature.

**Question 37:** What is the difference between checked and unchecked exceptions?

**Answer:** Checked exceptions must be handled or declared, while unchecked exceptions do not require explicit handling.

**Question 38:** What is the parent class of all exceptions in Java?

**Answer:** `Throwable`

**Question 39:** What happens if an exception is not caught in a program?

**Answer:** The program terminates abnormally.

**Question 40:** How do you create a custom exception?

**Answer:** By extending the `Exception` or `RuntimeException` class.

---

### **9. Design Patterns**

**Question 41:** What is the Singleton pattern?

**Answer:** A design pattern that ensures only one instance of a class exists.

**Question 42:** What is the Factory Method pattern?

**Answer:** A pattern that provides an interface for creating objects, allowing subclasses to alter the type of objects created.

**Question 43:** What is the Strategy pattern?

**Answer:** A pattern that enables selecting an algorithm's behavior at runtime.

**Question 44:** What is the Observer pattern?

**Answer:** A pattern where an object (subject) notifies other objects (observers) of state changes.

**Question 45:** What is the Builder pattern?

**Answer:** A pattern that constructs complex objects step by step.

---

### **10. Regex**

**Question 46:** Write a regex to match an email address.

**Answer:** `^[\w.%+-]+@[\w.-]+\.[a-zA-Z]{2,}$`

**Question 47:** Write a regex to match a string starting with a digit.

**Answer:** `^\d.*`

**Question 48:** Write a regex to match a string that contains only lowercase letters.

**Answer:** `^[a-z]+$`

**Question 49:** Write a regex to match a phone number in the format (XXX) XXX-XXXX.

**Answer:** `^\(\d{3}\) \d{3}-\d{4}$`

**Question 50:** Write a regex to match a password with at least one uppercase letter, one digit, and one special character.

**Answer:** `^(?=.*[A-Z])(?=.*\d)(?=.*[@#$%^&+=]).{8,}$`

---

This is the unhidden version of the mock exam. Let me know if you need any further adjustments!

