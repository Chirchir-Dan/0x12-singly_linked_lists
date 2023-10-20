0x12. C - Singly linked lists



Concepts

For this project, we expect you to look at this concept:

    Data Structures

Resources

Read or watch:

    Linked Lists
    Google
    Youtube

Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
General

    When and why using linked lists vs arrays
    How to build and use linked lists

Requirements
General

    Allowed editors: vi, vim, emacs
    All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
    All your files should end with a new line
    A README.md file, at the root of the folder of the project is mandatory
    Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
    You are not allowed to use global variables
    No more than 5 functions per file
    The only C standard library functions allowed are malloc, free and exit. Any use of functions like printf, puts, calloc, realloc etc… is forbidden
    You are allowed to use _putchar
    You don’t have to push _putchar.c, we will use our file. If you do it won’t be taken into account
    In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
    The prototypes of all your functions and the prototype of the function _putchar should be included in your header file called lists.h
    Don’t forget to push your header file
    All your header files should be include guarded

More Info

Please use this data structure for this project:

Tasks
0. Print list
mandatory

Write a function that prints all the elements of a list_t list.

    Prototype: size_t print_list(const list_t *h);
    Return: the number of nodes
    Format: see example
    If str is NULL, print [0] (nil)
    You are allowed to use printf


1. List length
mandatory

Write a function that returns the number of elements in a linked list_t list.

    Prototype: size_t list_len(const list_t *h);


2. Add node
mandatory

Write a function that adds a new node at the beginning of a list_t list.

    Prototype: list_t *add_node(list_t **head, const char *str);
    Return: the address of the new element, or NULL if it failed
    str needs to be duplicated
    You are allowed to use strdup


3. Add node at the end
mandatory

Write a function that adds a new node at the end of a list_t list.

    Prototype: list_t *add_node_end(list_t **head, const char *str);
    Return: the address of the new element, or NULL if it failed
    str needs to be duplicated
    You are allowed to use strdup


4. Free list
mandatory

Write a function that frees a list_t list.

    Prototype: void free_list(list_t *head);



