# Library Management

--- 

### Context

The Highschool Francesc De Borjamoll has ordered us to implement the loan management of its library. This implies a management of the books and the teachers and students that are being given a loan.

During a series of interviews and meetings with staff, we have gathered the following functionalities to automate:

- The app will be used by the librarian and the library users.

- An admin user can do actions related to the app configuration (create users, modify some parameters...)

- The librarian and the users can perform actions over books (check for availability, reserve a book...) the actions will be limited to the role of the user.

- The librarian will manage the loans and books. The app will allow to register loans and returns and check for books state. Could also register new books, modify the info and retire them.

- The system will carry on all the operations done by the users. Also will keep the state of the operations (passed, active...)

- Teachers and students could do: 
    - reserve a book
    - prereserve a book
    - check the state of the books (borrowed, prereserved...)

- Also could do the following physical actions:
    - ask for a loan
    - return a book

- To do al loan both teachers and students have to go to the library, take the book and ask for a loan. The librarian will use the app to assign the loan of the book to the user. The number of books that a user can have will depend if he is a teacher or a student.

- The teachers can use deposit loans, this means that the teacher will have the book until somebody requests it (teacher or student).

- The users can reserve books with the app:
    - 
    - 
- The default state for a user is active...

- From the fine...
---

### Multimodule java project managed with maven 

This project is a multimodule maven project. At first we start with a simple project that represents the domain of our system.
