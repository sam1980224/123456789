Here is the current list for **Java Side Knowledge**:

1. **StringBuilder and Memory Allocation**  
   - This is because `StringBuilder` is a mutable class, and Java requires explicit use of the `new` keyword to allocate memory for mutable objects.

2. **API Overview**  
   - API explains how to use a programming library or class by describing the available methods, parameters, and return types.

3. **Garbage Collection**  
   - Garbage Collection -> is the process by which the JVM automatically deallocates memory for objects that are no longer reachable or used in a program.

4. **Java Arrays vs. Python Lists**  
   - **Fixed Size**: Java arrays have a fixed length, while Python lists are dynamic.  
   - **Type Safety**: Java arrays must contain elements of the same type, whereas Python lists can hold mixed types.  
   - **Primitive Storage**: Java arrays can store primitives, while Python lists store objects.

5. **Aliasing**  
   - **Mutable Objects:** Aliases can lead to side effects because changes affect all references.  
   - **Immutable Objects:** Changes create new objects, leaving original references unaffected.

6. **Instance Variables in Java and Python**  
   - Java's instance variables = Python's attributes.

7. **Class Variables Analogy**  
   - A **class variable** (static) in Java is analogous to a Python class attribute that is shared across all instances.

8. **Public / Private Comparison to Python**  
   - In Python, a single underscore (`_`) at the start of a variable name is used to indicate that it is private by convention.  
   - Java uses explicit access modifiers (`public`, `private`) for this purpose. Private variables cannot be accessed from outside the class, unlike public ones.

9. **Inheritance**  
   - In Java, the `extends` keyword is used for inheritance:  
     ```java
     class Child extends Parent {
         // Child inherits methods and variables from Parent
     }
     ```  
   - Use the `abstract` keyword to mark a class or method as abstract:  
     ```java
     abstract class AbstractClass {
         abstract void someMethod(); // Abstract methods have no body
     }
     ```

10. **Super() Key Confusion Resolve**  
    - When the parent (or "mother") class has a constructor that requires input parameters to initialize its instance variables, the child class must call `super()` with the appropriate arguments to satisfy the parent's constructor. Without this explicit call, the compiler will raise an error because Java does not know how to initialize the parent class's instance variables.

11. **Polymorphism Example**  
    - Example of polymorphism in use:  
      ```java
      abstract class Animal {
          abstract void makeSound();
      }

      class Dog extends Animal {
          @Override
          void makeSound() {
              System.out.println("Woof!");
          }
      }

      class Cat extends Animal {
          @Override
          void makeSound() {
              System.out.println("Meow!");
          }
      }

      Animal[] animals = {new Dog(), new Cat()};
      for (Animal animal : animals) {
          animal.makeSound(); // Calls the appropriate method dynamically
      }
      ```

12. **Abstract Class Code Immersion**  
    - Example of an abstract class with concrete and abstract methods:  
      ```java
      abstract class Animal {
          String name; // Instance variable

          public Animal(String name) {
              this.name = name;
          }

          abstract void makeSound();

          public void eat() {
              System.out.println(name + " is eating.");
          }
      }

      class Dog extends Animal {
          public Dog(String name) {
              super(name);
          }

          @Override
          void makeSound() {
              System.out.println(name + " says Woof!");
          }
      }
      ```

13. **Interface Immersion Code Block**  
    - Example of implementing multiple interfaces:  
      ```java
      interface Flyable {
          void fly();
      }

      interface Swimable {
          void swim();
      }

      class Duck implements Flyable, Swimable {
          @Override
          public void fly() {
              System.out.println("Duck is flying!");
          }

          @Override
          public void swim() {
              System.out.println("Duck is swimming!");
          }
      }
      ```

14. **Instanceof in Polymorphism**  
    - The `instanceof` operator checks whether an object is an instance of a particular class or implements a specific interface, enabling safe type casting.

15. **Array Declaration and Upcasting**  
    - Example of array declaration and upcasting:  
      ```java
      Animal[] animals = {new Cat(), new Dog(), new Axolotl()}; // Upcasting here
      ```

Let me know if you'd like to add or revise anything! 😊
