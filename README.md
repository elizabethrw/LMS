# CEG-4110 Project Overview

## Project Title: 
Library Management System

## Team Name: 
Team One

## Team Members: 
Elizabeth Wright, Trevor Bouse, Liam Williams-Henninger

## Project Synopsis: 
The library management system will track the status of all of the books and customers.

## Concept of Operation: 
The system is designed to be used by a working librarian. The system will have information such as which books individuals are renting, whether individuals have late fees, whether a book is available for rent or not, etc.


-	The system shall have a log of all users.
-	The system shall have a log of all books.
-	The system shall track date and time.
-	The status of all books shall be accessible (via title, author, or ID number) and updateable, such as:
    -	Whether the book is currently being borrowed
    -	Whether the book is damaged
-	The system shall have the ability to add/remove books from the library’s system.
-	The status of users shall be accessible (via either last name or ID number) and updateable, such as:
    -	The number of books a user is borrowing
    -	The amount of late fees a user has (if the user has late fees)
    -	Whether the user is allowed to borrow a certain book.
        -	A user can not borrow a book either if that book is unavailable, if the user has too many books borrowed, or if the user has too many late fees.
-	The system shall have the ability to add/remove users and books from the library’s system.

The system will accept user inputs from the terminal and update its records based on those inputs.

## Estimate of the Effort 
Focusing on requirements, design, writing the code, and code and unit testing are all steps that will be taking in writing the library management system. Anticipated components of the project are listed below.

Anticipated Components:
1. Classes
 - Book
 - User
2. Functions
 - Find Book Object
 - Create Book Object
 - Delete Book Object
 - Find User Object
 - Create User Object
 - Delete User Object
 - Track Date
 - Update Book Object's Status (Manual)
 - Update User Object's Status (Manual)
 - Update Book Object's Status (Time)
 - Update Book Object's Status (Time)
3. Keyboard Input (Main)
 - Request What the User Wants to Do
 - Call Functions Based on Input
 - Close Software Based on Input
 - GUI
 
## Basis of Estimate

![BOE](https://user-images.githubusercontent.com/77339445/188673473-be277ffe-0875-4f9c-b8a8-cd55d825e987.png)

## Assumptions
1. 10 SLOC per hour per person productivity factor.
2. The basis of estimate includes the Unit Test code count.
3. The productivity factor is the time to develop the unit test.
4. Integration and Test time is included in the 10 SLOC per hour productivity factor.
5. Minimal design documentation is anticipated and included in the 10 SLOC estimate. The following identifies potential design documentation:
- Data structure used to store Book object and User Object (and why that data structure is the most efficient choice)
- What information each Book object and User Object needs to hold
- GUI format
5. Only the developers will review the code and other related documentation.
6. The code will be developed and tested on a Windows 10 computer using the VSCode Development Environment with Doxygen.
