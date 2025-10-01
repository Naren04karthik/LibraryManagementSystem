# Library Management System

## Project Overview
The **Library Management System** is a console-based application developed in **Java using Object-Oriented Programming (OOP) principles**. It provides a robust platform to manage library books, members, and transactions efficiently. The system incorporates **classes, objects, inheritance, polymorphism, encapsulation, and exception handling** to ensure modularity and maintainability.

---

## Features
- **Book Management**
  - Add, update, and remove books.
  - Track availability of books in real-time.
  
- **Member Management**
  - Add new library members and maintain their details.
  - Support for different member types (e.g., Student, Faculty) with specific privileges.
  
- **Issue/Return Management**
  - Issue books to members with due dates.
  - Return books and update inventory automatically.
  - Fine calculation for late returns.
  
- **Exception Handling**
  - Custom exceptions for invalid operations, such as issuing unavailable books or invalid member IDs.

- **Interactive Console Interface**
  - Menu-driven interface for easy navigation.
  - Handles invalid inputs gracefully.

---

## OOP Concepts Implemented
- **Classes and Objects**: Each entity (Book, Member, Transaction) is represented as a separate class.  
- **Encapsulation**: Private data members with public getter and setter methods.  
- **Inheritance**: Specialized member types (Student, Faculty) extend a base Member class.  
- **Polymorphism**: Overloaded and overridden methods for book issue/return and fine calculations.  
- **Exception Handling**: Custom exceptions like `BookNotAvailableException`, `MemberNotFoundException`.  
- **Modularity**: Separate packages for Services, Exceptions, and Utilities.

---

