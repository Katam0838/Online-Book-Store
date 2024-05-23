# Online Book Store

## Introduction
The **Online Book Store** is a web-based application designed for managing books, authors, categories, customers, and orders. This project allows an admin to add, edit, and delete entries for books, authors, categories, customers, and orders. It includes functionalities to view lists of books, authors, categories, customers, and orders.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Setup](#setup)
3. [Database Configuration](#database-configuration)
4. [Running the Application](#running-the-application)
5. [File Structure](#file-structure)
6. [Usage](#usage)
   
## Prerequisites
Before you begin, ensure you have the following software installed:
- [XAMPP](https://www.apachefriends.org/index.html) (for Apache, MySQL, PHP)
- Web Browser (e.g., Chrome, Firefox)
- Sublime Text (or) Visual Studio Code

## Setup
1. **Clone the Repository**
   ```bash
   https://github.com/Katam0838/Online-Book-Store.git
2. **Naviagte to project directory**
cd online-book-store
3. **Database Configuration**
- Start XAMPP: Launch the XAMPP Control Panel and start Apache and MySQL.
- Create Database: Open http://localhost/phpmyadmin/, create a new database named online_book_store.
- Import Database: Import the online_book_store.sql file from the database directory.
4. **Running the Application**
- Move Project to XAMPP Directory: Copy the project folder to the htdocs directory in your XAMPP installation directory.
- Access the Application: Open your browser and navigate to http://localhost/online-book-store/.
5. **Features**
- Books Management: Add, edit, view, and delete books, including managing stock quantity and price.
- Categories Management: Add, edit, view, and delete book categories.
- Authors Management: Add, edit, view, and delete authors.
- Customers Management: Add, edit, view, and delete customers.
- Orders Management: Add, edit, view, and delete orders.
