Online Bookstore Management System
A dynamic and interactive Java-based e-commerce simulation for managing an online bookstore, showcasing advanced functionalities for both users and administrators. This project extensively leverages various data structures for optimized operations.

Features
User Functionalities
Sign Up and Login: Register and log in with secure credentials.
Browse Books:
Sort by rating or price.
Search by author, genre, or rating threshold.
Manage Cart:
Add books to the cart and proceed to checkout.
Remove books from the cart.
Wishlist Management:
Save books for later consideration.
Move books from wishlist to cart.
Order History:
View a complete history of purchased books.
Admin Functionalities
Manage Books:
Add, edit, or remove books.
View Purchase History:
Check user purchase records.
Manage Users:
Add, edit, or remove user accounts.
Data Structures Used
This project implements and demonstrates the following data structures:

ArrayList:

Used for storing and managing the list of books.
Facilitates dynamic resizing and fast random access for the book collection.
HashMap:

Stores user data (username -> Customer object) for quick lookup and efficient user management.
Stack:

Maintains a history of user purchases to allow order tracking in LIFO (Last In First Out) order.
PriorityQueue:

Used for sorting books dynamically by:
Rating (highest first).
Price (lowest first).
LinkedList:

Handles the user cart and wishlist, allowing fast insertion and removal operations.
Streams (Java 8):

Used for filtering and searching books by author, genre, or rating.
How to Run the Project
Requirements:

Java Development Kit (JDK) 8 or later.
A terminal or IDE like IntelliJ IDEA, Eclipse, or VS Code.
Steps:

Compile the program:
bash
Copy code
javac OnlineBookStore.java
Run the program:
bash
Copy code
java OnlineBookStore
Program Flow:

Main Menu:
Choose to log in as a user, admin, or browse books as a guest.
User Dashboard:
Access cart, wishlist, and purchase history.
Admin Dashboard:
Manage books and users, or view purchase histories.