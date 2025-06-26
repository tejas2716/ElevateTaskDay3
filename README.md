**Welcome to Library Management System**

#Developed by: Tejas Sathe
#MailId - sathetejas111@gmail.com
#Pune, Maharashtra

**Project Description:**
 The Library Management System is a console-based Java application designed to manage library operations such as adding books, 
 registering users, issuing and returning books, and viewing current library records. The system uses Object-Oriented Programming (OOP) principles like encapsulation,
 abstraction, and modularity to ensure a clean, maintainable, and scalable codebase.

#The core functionality is organized into three primary classes:
**1)Book** – Represents individual books with attributes like ID, title, author, and issue status.
**2)User** – Represents library users with attributes like ID and name.
**3)Library** – Acts as the controller to manage books and users, and handles operations such as adding, viewing, issuing, and returning.
 
 All user input is handled through a menu-driven interface, with built-in input validation to ensure a smooth and error-free user experience.

#Objective
To practice **OOP concepts** such as **encapsulation**, **class interaction**, and **data validation**, while building a real-world simulation of a library system using Java.

#Tools & Technologies

- **Language:** Java (JDK 8+)
- **IDE:** VS Code / IntelliJ IDEA / Eclipse
- **Execution:** Terminal / Command Prompt

**Project Structure**

com.elevate_Internship_Day_3/
├── Main.java // Contains the main menu and handles user input
├── Book.java // Book class with ID, title, author, and issued status
├── User.java // User class with ID and name
└── Library.java // Manages books and users, handles operations

**Features**

✅ Add new books  
✅ Add new users  
✅ View all books (with issued/available status)  
✅ View all users  
✅ Issue a book  
✅ Return a book  
✅ Input validation (avoids crash on wrong input)  


**Sample Flow**

===== Library Management System =====
1. Add Book
2. Add User
3. View Books
4. View Users
5. Issue Book
6. Return Book
7. Exit
Choose an option: 1
Enter Book ID: 101
Enter Title: Java Basics
Enter Author: James Gosling
Book added.

**OOP Concepts Applied**
-Concept	Description
-Encapsulation	Data is grouped logically into Book, User, and Library classes
-Abstraction	Menu logic is separated from implementation details
-Modularity	Functions like addBookInput(), issueBookInput() isolate logic
-Validation	No invalid IDs/names allowed; protects program from crashing

**Future Improvements**
-Add login system for users
-Track issue/return history per user
-Search/filter books by title or author
-Store data in files or a database

