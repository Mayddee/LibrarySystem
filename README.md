# LibraryApp

## Overview
LibraryApp is a simple console-based library management system written in Java. It allows users to manage books, register users, lend and return books, and perform various library-related operations.

##  Features
-  Add a book to the library
-  Search for books by keyword
-  List all books in the library
-  Remove a book from the library
-  Register new users
-  Lend books to users
-  Receive returned books
-  Show books borrowed by a user
-  List all registered users

##  Prerequisites
-  Java Development Kit (JDK) 8 or later
-  Eclipse IDE (or any other Java-compatible IDE)

##  Installation
1. Clone or download the project:
   ```sh
   git clone https://github.com/your-username/LibraryApp.git
   ```
2. Open Eclipse IDE.
3. Select **File** > **Import** > **Existing Projects into Workspace**.
4. Choose the root directory of the project and click **Finish**.
5. Ensure the Java compiler compliance level is set correctly in **Project Properties > Java Compiler**.
6. Run the `LibraryApp.java` file.

## 🏃‍♂ Usage
When the program starts, it will display a menu with options:
1. Add a book
2. Search for a book
3. Show all books
4. Remove a book
5. Add a user
6. Lend a book to a user
7. Receive a returned book
8. Show books borrowed by a user
9. Show list of users
10. Exit

Users can interact with the menu by entering the corresponding number for each action.

###  Example
```sh
Добро пожаловать в библиотеку!
Выберите действие:
1. Добавить книгу
2. Найти книгу
3. Показать все книги
...
Введите ID книги для удаления: 101
Книга удалена.
```

##  Project Structure
```
LibraryApp/
│── src/
│   ├── LibraryApp.java   # Main class with the menu
│   ├── Library.java      # Library management logic
│   ├── Book.java         # Book entity class
│   ├── User.java         # User entity class
│── README.md            # Documentation
```

##  Contributing
Contributions are welcome! If you wish to improve this project, feel free to fork the repository and submit pull requests.

##  License
This project is open-source and can be used freely for learning and development purposes.

##  Contact
If you have any questions or suggestions, feel free to reach out via GitHub issues.

---
 Don't forget to give this project a star if you found it useful!

