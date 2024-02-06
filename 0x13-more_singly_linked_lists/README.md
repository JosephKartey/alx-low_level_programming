# Linked List Operations in C

This repository contains C functions that perform various operations on a `listint_t` linked list. Each function is designed to handle specific tasks related to manipulating linked lists. Below is an overview of each function:

1. **Print List**
   - File: `0-print_listint.c`
   - Description: Prints all the elements of a `listint_t` linked list and returns the number of nodes in the list.

2. **List Length**
   - File: `1-listint_len.c`
   - Description: Returns the number of elements in a `listint_t` linked list.

3. **Add Node at the Beginning**
   - File: `2-add_nodeint.c`
   - Description: Adds a new node at the beginning of a `listint_t` linked list. Returns the address of the new element or `NULL` if the function fails.

4. **Add Node at the End**
   - File: `3-add_nodeint_end.c`
   - Description: Adds a new node at the end of a `listint_t` linked list. Returns the address of the new element or `NULL` if the function fails.

5. **Free List**
   - File: `4-free_listint.c`
   - Description: Frees a `listint_t` linked list.

6. **Free List (with Head Set to NULL)**
   - File: `5-free_listint2.c`
   - Description: Frees a `listint_t` linked list and sets the head to `NULL`.

7. **Pop Head**
   - File: `6-pop_listint.c`
   - Description: Deletes the head node of a `listint_t` linked list. Returns 0 if the list is empty, otherwise returns the head node's data.

8. **Get Node at Index**
   - File: `7-get_nodeint.c`
   - Description: Locates a given node at a specific index in a `listint_t` linked list. Returns the located node or `NULL` if the node does not exist.

9. **Sum List**
   - File: `8-sum_listint.c`
   - Description: Returns the sum of all the data (`n`) of a `listint_t` linked list. Returns 0 if the list is empty.

10. **Insert Node at Given Position**
    - File: `9-insert_nodeint.c`
    - Description: Inserts a new node at a given position in a `listint_t` linked list. Returns the address of the new node or `NULL` if it fails.

11. **Delete Node at Index**
    - File: `10-delete_nodeint.c`
    - Description: Deletes the node at a given index of a `listint_t` linked list. Returns 1 if successful, -1 if it fails.

12. **Reverse List**
    - File: `100-reverse_listint.c`
    - Description: Reverses a `listint_t` linked list using a maximum of one loop and two variables. Returns a pointer to the first node of the reversed list.

13. **Print List Safely**
    - File: `101-print_listint_safe.c`
    - Description: Prints a `listint_t` linked list safely, handling lists containing loops. Returns the number of nodes in the list.

14. **Free List Safely**
    - File: `102-free_listint_safe.c`
    - Description: Frees a `listint_t` linked list safely, handling lists containing loops. Returns the size of the list that was freed and sets the head to `NULL`.

15. **Find the Loop**
    - File: `103-find_loop.c`
    - Description: Finds the loop contained in a `listint_t` linked list using a maximum of two variables. Returns the address of the node where the loop starts or `NULL` if no loop is found.

