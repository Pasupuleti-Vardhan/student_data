# Student Data Management System (Linked List)

A console-based **Student Data Management System** implemented in **C** using the **Linked List** data structure for dynamic memory allocation and efficient record management.

## Features
* **Add Student Record:** Dynamically inserts a new student node into the linked list.
* **Display Records:** Traverses the linked list to display all stored student details.
* **Search Student:** Searches for a student record by roll number or name.
* **Update / Delete Record:** Modifies existing student details or deletes a node and frees its memory.
* **Dynamic Memory Management:** Uses pointers and dynamic allocation (`malloc`/`free`) to grow or shrink storage as records change.

## Project Structure
* `main.c` – Main driver program containing the menu interface and linked list operations.
* `header.h` – Header file defining the student node structure (`struct`) and function prototypes.

## How to Compile and Run
1. Clone the repository:
   git clone https://github.com
   cd student_data

2. Compile the source code using GCC:
   gcc main.c -o student_data

3. Run the executable:
   ./student_data
