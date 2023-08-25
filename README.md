# AI-Learning-Projects
It is just a bunch of mini exercises so that i can improve myself in the field of python language

1)  Create a class called "Person" with attributes like name, age, and address. 
    Implement methods to set and get these attributes, and display information about the person.

    Create a class called "Student" that inherits from the "Person" class. Add additional attributes like student ID, major, and GPA. 
    Implement methods to set and get these attributes, and display information about the student.

    Create a class called "BankAccount" that represents a bank account with attributes like account number, account holder's name, and balance. 
    Implement methods to deposit, withdraw, and display balance, while encapsulating the account balance to prevent direct access.

2)  Problem:

    You have been hired to develop a library system for a local library. The library has books, each with a title, author, genre, and availability status.
    The library also has members who can borrow books from the library. Each member has a name, address, and a list of borrowed books.
    
    Your task is to implement a library system using Object-Oriented Programming (OOP) and read and write concepts in Python. Create the following classes:
    
    1. Book:
    - Attributes: title (string), author (string), genre (string), is_available (bool)
    - Methods:
      - `__init__(self, title, author, genre)`: Initializes a book object with the given title, author, genre, and sets availability status to True.
      - `display_info(self)`: Displays information about the book, including title, author, genre, and availability status.
      - `setAvailable(self)`: Marks the book as unavailable (sets is_available to False) if is_available is True and vice versa.
    
    2. Member:
    - Attributes: name (string), address (string), borrowed_books (list)
    - Methods:
      - `__init__(self, name, address)`: Initializes a member object with the given name, address, and an empty list for borrowed books.
      - `display_info(self)`: Displays information about the member, including name, address, and the list of borrowed books.
      - `borrow_book(self, book)`: Allows the member to borrow a book by adding it to the list of borrowed books.
      - `return_book(self, book)`: Allows the member to return a book by removing it from the list of borrowed books.
    
    3. Library:
    - Attributes: books (list), members (list)
    - Methods:
      - `__init__(self)`: Initializes a library object with empty lists for books and members.
      - `add_book(self, title, author, genre)`: Adds a book to the library's list of books.
      - `add_member(self, name, address)`: Adds a member to the library's list of members.
      - `display_books(self)`: Displays information about all the books in the library.
      - `display_members(self)`: Displays information about all the members in the library.
      - `borrow_book(self, book_title, member_name)`: Allows a member to borrow a book from the library by updating the book's availability status and adding it to the member's list of borrowed books.
      - `return_book(self, book_title, member_name)`: Allows a member to return a book to the library by updating the book's availability status and removing it from the member's list of borrowed books.
    
    IMPORTANT: All of these datas must be written in the text file named 'data.txt' and your program should be able to access data just by reading the file.
    
    Your solution should demonstrate the use of classes, objects, attributes, methods, encapsulation, and other OOP principles.
    Test your solution with sample scenarios, such as adding books and members, displaying book and member information, borrowing and returning books, and
    handling cases where books are not available or members try to borrow or return books that do not exist.

4)  Exercise 1: Email Validator with Decorator and Regex
    Write a Python class called EmailValidator that can validate email addresses using regular expressions. Implement the following:
    
    Use a class decorator to add a regular expression pattern as a class attribute.
    Implement a property decorator to get and set the regular expression pattern.
    Write a method called validate(email) that returns True if the email matches the pattern and False otherwise.
    
    Exercise 2: Get Next Line
    Write a Python generator function called file_reader that reads a text file line by line. Implement the following:
    
    Accept a file path as a parameter when calling the generator function.
    Open the file in read mode and iterate over its lines.
    Yield each line as a string.
    
    Exercise 3: Counter Closure
    Write a closure function called counter that counts the number of times it has been called. Implement the following:
    
    The closure function should return a nested function.
    The nested function should increment a counter variable each time it is called.
    The closure function should return the nested function.
    
    Exercise 4: Person Class with Property
    Create a Python class called Person with the following properties:
    
    name: a private instance variable for the person's name.
    Implement a getter method using the @property decorator to retrieve the person's name.
    Implement a setter method using the @name.setter decorator to set the person's name.
    
    Exercise 5: Password Validator with Decorator
    Write a Python function called password_validator that validates a password string using regular expressions. Implement the following:
    
    Use a function decorator to check if the password meets certain criteria.
    The criteria should include at least one uppercase letter, one lowercase letter, and one digit.
    Return True if the password meets the criteria, and False otherwise.
