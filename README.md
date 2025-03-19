[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/7TXVPuTD)

# Questions

## 1. Why do we need OOP? What are some major OOP languages?
Object-Oriented Programming (OOP) helps in code reusability, maintainability, and organization using objects and classes.

### Major OOP Languages:
- Java
- C++
- Python
- C#
- Ruby

---
## 2. Interface vs Abstract Class
| Feature            | Interface | Abstract Class |
|--------------------|-----------|---------------|
| Methods           | Only method signatures (no implementation, except default methods in Java 8+) | Can have both abstract methods and concrete methods |
| Inheritance       | Used for defining behavior across unrelated classes | Used for shared behavior in a class hierarchy |

---
## 3. Why do we need `equals()` and `hashCode()`? When to override?
- Used to compare object equality and enable correct hashing.
- Override when creating custom objects that need to be compared logically.

---
## 4. Diamond Problem in Java & How to Fix It
- Occurs in multiple inheritance when a class inherits from two interfaces with the same method.
- **Fix**: Use default methods in interfaces or avoid multiple inheritance of implementations.

---
## 5. Why do we need a Garbage Collector? How does it run?
- Frees memory by removing unused objects to prevent memory leaks.
- Runs automatically but can be triggered manually with `System.gc()`.

---
## 6. Java `static` Keyword Usage
- Used for class-level variables, methods, blocks, and nested classes.
- Belongs to the class, not instances.

---
## 7. Immutability: Definition, Usage, and Implementation
- **Definition**: An immutable object cannot be modified after creation.
- **Where to Use**: String, Wrapper classes, and custom immutable objects.
- **Why**: Ensures thread safety and efficient caching.
- **How**: Use `final` fields and avoid setters.

---
## 8. Composition vs Aggregation
| Feature       | Composition | Aggregation |
|--------------|------------|-------------|
| Association  | Strong (contained object cannot exist without the container) | Weak (contained object can exist independently) |

---
## 9. Cohesion vs Coupling
- **Cohesion**: How well a class’s methods relate to its purpose.
- **Coupling**: Dependency between classes.

---
## 10. Heap vs Stack
| Feature  | Heap | Stack |
|---------|------|-------|
| Stores  | Objects | Method calls and local variables |
| Scope   | Shared among threads | Thread-specific |
| Management | Managed by Garbage Collector | Auto-cleared |

---
## 11. What is an Exception? Types of Exceptions
- **Definition**: An event disrupting program execution.
- **Types**:
  - **Checked**: Must be handled (e.g., `IOException`).
  - **Unchecked**: Runtime errors (e.g., `NullPointerException`).

---
## 12. How to Summarize "Clean Code" in the Shortest Way?
- Simple, readable, maintainable, and follows best practices.

---
## 13. What is Method Hiding in Java?
- Occurs when a subclass defines a static method with the same signature as a static method in the parent class.
- Unlike method overriding, the method call depends on the reference type.

---
## 14. Abstraction vs Polymorphism in Java
| Feature       | Abstraction | Polymorphism |
|--------------|------------|-------------|
| Definition   | Hides implementation details using abstract classes or interfaces | Allows methods to behave differently based on the object type |
| Example     | Abstract classes, Interfaces | Method overriding, Method overloading |
