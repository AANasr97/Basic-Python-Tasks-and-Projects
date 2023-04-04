# Library Management System

![image.png](attachment:image.png)

Harry works in the library and is tired of maintaining paper records. He wants to digitize the library's operations and needs a program to do so. This project aims to provide a solution to Harry's problem.

## The Library Class

The project defines a `Library` class that represents a library object. The `Library` class has four methods:

* `__init__(self, name, booksList)`: Initializes a `Library` object with a name and a list of books.
* `displayAvailableBooks(self)`: Displays the available books in the library.
* `lendBook(self, book, user)`: Allows a user to lend a book if it is available and updates the books list and lended books dictionary accordingly.
* `addBook(self, book)`: Allows a librarian to add a book to the library and updates the books list accordingly.
* `returnBook(self, book)`: Allows a user to return a book they have lended and updates the books list and lended books dictionary accordingly.

## Usage

The project includes three instances of the `Library` class to demonstrate its functionality:

* `myLibrary`: The first instance is created with a list of three books, and the methods are called to test the different scenarios.
* `universityLibrary`: The second instance is also created with a list of three books and its methods are tested in the same way as `myLibrary`.
* `Harry`: The third instance is created with a list of five books and a program loop is initiated that allows a user to choose from five options: display available books, lend a book, add a book, return a book, or exit the program. The loop continues until the user chooses to exit.