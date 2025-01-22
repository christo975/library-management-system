# Library Management System  

The **Library Management System** is a simple console-based Java application that allows users to manage basic library operations such as adding, viewing, searching, and deleting books. This project is ideal for beginners who want to explore object-oriented programming (OOP) concepts and Java collections.  

---

## Features  

- **Add Book**: Add new books by entering their ID, title, and author.  
- **View Books**: Display the entire collection of books in the library.  
- **Search Book**: Search for a book by its title.  
- **Delete Book**: Remove a book from the collection using its ID.  
- **Exit**: Safely terminate the application.  

---

## How It Works  

1. **Book Class**  
   The `Book` class defines the structure of a book with attributes such as `id`, `title`, and `author`. It also includes a `toString()` method for displaying book details.  

2. **Library Class**  
   The `Library` class manages the collection of books using an `ArrayList`. It includes methods for adding, viewing, searching, and deleting books.  

3. **Main Class**  
   The `LibraryManagementSystem` class contains the main menu for user interaction. It uses the `Scanner` class to handle user input and calls methods from the `Library` class to perform operations.  

---

## Requirements  

- **Java Development Kit (JDK)**: Version 8 or higher.  
- **IDE**: IntelliJ IDEA, Eclipse, or any other Java IDE (optional).  
- **Compiler**: Ensure `javac` is installed to compile the code.  

---

## Setup and Execution  

1. Clone or download the project to your local system.  
2. Open the project in your Java IDE or terminal.  
3. Create a file named `LibraryManagementSystem.java` and paste the code into it.  
4. Compile the project:  
   ```bash  
   javac LibraryManagementSystem.java  
