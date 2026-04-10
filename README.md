# Book-management-system
This project is a simple Book Management System in C++ that demonstrates core Object-Oriented Programming (OOP) concepts such as classes, encapsulation, and composition.The system consists of two main classes: Book and Library. The Book class stores individual book details, while the Library class manages a collection of books using a fixed-size array. Users can perform basic CRUD operations including adding, listing, searching, updating, and deleting books through a menu-driven interface. Each book is assigned a unique ID automatically. This project is ideal for beginners to understand class relationships and basic data handling in C++.

📌 Overview

This is a console-based Book Management System implemented in C++. It allows users to manage books efficiently using basic operations such as add, view, search, update, and delete. The program follows Object-Oriented Programming principles for clean and modular design.
🧩 UML Class Diagram Explanation

The UML diagram shows two main classes:

1. 📖 Book Class

Represents a single book.

Attributes:

id: Unique identifier
title: Book title
author: Author name
year: Publication year

Methods:

Getters: getId(), getTitle(), getAuthor(), getYear()
Setters: setTitle(), setAuthor(), setYear()
show(): Displays book details

👉 This class is responsible for storing and handling individual book data.

2. 📚 Library Class

Manages multiple books.

Attributes:

books[CAP]: Array to store books (max 100)
count: Current number of books
nextId: Auto-increment ID generator

Methods:

addBook(): Add a new book
listBooks(): Display all books
findById(int): Find book index
searchBook(): Search book by ID
updateBook(): Modify book details
deleteBook(): Remove a book


