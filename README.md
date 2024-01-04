# Bookstore-management-system
A basic c++ project of a bookstore management system using the basic concepts of DSA i,e linked list, binary search tree and sorting

-->The program uses a doubly linked list to manage the book details, providing functionalities like insertion, deletion, searching, and editing.

-->It implements file handling to save and load book details, ensuring persistence of data across program executions.

-->The program offers a user-friendly interface with a menu-driven approach, allowing users to perform various operations on the book store.

Member Functions:
-CreateNode(): Adds a new book node to the end of the doubly linked list.

-Display(): Displays all the books sorted by their names using Bubble Sort.

-Bsearch(): Performs a binary search to find a book by its name.

-DeleteAll_Books(): Deletes all the books from the store.

-DeleteBooks(): Deletes a specific book based on user input.

-BubbleSort(): Sorts the books by their names using the Bubble Sort algorithm.

-EditContacts(): Edits the details (name and price) of a specific book.

-Filesave(): Saves the book details to a file named "Book_store.txt".

-reopenCB(): Reopens the file "Book_store.txt" and loads the book details back into the linked list.
