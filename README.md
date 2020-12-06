# ONLINE LIBRARY MANAGEMENT
`Library functions allows the user to perform basic library administrator functions and displays student details`
## *CONTENTS*
>CLASSES

__This program contains two classes :__

| CLASS      | no. of functions |
| ---------- | ---------------- |
| Student    |    5             |
| Books      |    5             |


>FUNCTIONS
* There are about 14 functions outside the classes

## *WHAT IT DOES*
* This program first shows the user the **MAIN MENU** where they can choose between the three options or can Exit:
    1. Book issue
    1. Book deposit
    1. Administrator menu
* The _book issue_ option enables the user to enter the _students admission number_ and the _book number_ and issue the book to that student. It uses the function :
```C++
void book_issue()
```
* The _book deposit_ option enables the user to enter the _students admission number_ and the _book number_ and the _number of days in which the book is deposited in_ . It gives the fine(in Rs.) as output (if any) and book deposited sucessfully (or) if no book is issued , it asks the user to check. It uses the function :
```C++
void book_deposit()
```
* The _Administrator Menu_ option opens a menu of it's own
    1. Create student record 
    1. Display all students record
    1. Display specific student record
    1. Modify student record
    1. Create book
    1. Display all books
    1. Display specific book
    1. Modify book
    1. Delete book
    1. Back to main menu
