# ONLINE LIBRARY MANAGEMENT
`Library functions allows the user to perform basic library administrator functions and displays student details`

## *DEVELOPMENT*
`This was fully developed in Turbo C++ compiler`

## *CONTENTS*
>CLASSES

__This program contains two classes :__

| CLASS      | no. of functions |
| ---------- | ---------------- |
| Student    |    5             |
| Books      |    5             |


>FUNCTIONS

 There are about 14 functions outside the classes

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
            * This option allows the user to enter the *admission number* and the *name of the student* and displays the output as **STUDENT RECORD CREATED** . It asks if we want to add more record. It uses the function :
            ```C++
            void write_student()
            ```
     1. Display all students record
            * This option displays the list of  _admission number of the student_ , _name of the student_ and if any book is issued from the book_issue() function. It uses the functions:
            ```C++
            void display_alls()
            ```
     1. Display specific student record
            * This option gets the _admission number_ as the input and displays the _admission number_ , _student name_ and the _no. of books issued_ as output. The function used here is:
            ```c++
            void display_sps(charn[])
            ```
     1. Modify student record
            * This option gets the _admission number_ as the input and displays the existing details of the student and asks us to enter the new details of the student , ie. _admission no._ and _student name_ . It gives the output as **Record updated** The function used is:
            ```C++
            void modify_student()
            ```
     1. Delete student record
            * This option allows us to delete the student. It asks the _admission no._ of the student and gives the output as **Record deleted**. The function used here is:
            ```C++
            void delete_student()
            ```

     1. Create book
            * This option allows us to enter the _book no._ , _name of the book_ and the _author's name_ to create a new book in the record. It gives the output as **Book created** . It uses the function :
            ```C++
            void write_book()
            ```
     1. Display all books
            * This option displays the _book number_ , _book name_ and the _author_ of the books. It uses the function:
            ```C++
            void display_allb()
            ```
     1. Display specific book
            * This option asks us to enter the _book no._ as the input and displays the _book no._ , _book name_ and the _author name_ of that specific book. It uses the function :
            ```C++
            void display_spb(char n[])
            ```
     1. Modify book
            * This option get the _book no._ as the input and then displays the _book no._, _book name_ and the _author name_ . It then asks us to enter the **New details of the book** and gets the _book no._, _modify book name_ and the _modify author name_ as input from the user and displays __Record updated__ . It uses the function:
            ```C++
            void modify_book()
            ```
     1. Delete book
            * This option gets the _book no._ of the book that you want to delete and displays the output as **Record deleted**. It uses the function :
            ```C++
            void delete_book()
            ```
     1. Back to main menu
            * This option takes us back to the main menu
