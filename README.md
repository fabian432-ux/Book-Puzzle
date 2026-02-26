# Linked List Librarian

## Description
A 4-level text-based puzzle game written in C. The game uses a singly linked list to manage a collection of books. Players must solve riddles by manipulating the linked list directly—sorting nodes, deleting specific elements, and adding new ones based on the internal properties of the books (author, year, color).

## Features
* **Custom Data Structures:** Built entirely using dynamic memory allocation and pointers via a custom C `struct`.
* **Level 1 (Sorting):** Reorder the list of books alphabetically by the author's name.
* **Level 2 (Filtering):** Identify and free the memory of books with non-primary colors.
* **Level 3 (Insertion & Deletion):** Allocate a new node for a custom book and remove books written by non-Russian authors.
* **Level 4 (Uniqueness):** Prune the linked list until no two remaining nodes share the same author, publication year, or color.
* **Hint System:** Each level includes progressive text hints to help the player solve the logic puzzle.

## How to Compile and Run

### Prerequisites
A standard C compiler (like GCC).

### Compilation
Open your terminal and run the following command:
```bash
gcc main.c -o book_puzzle
