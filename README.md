# **Library Management System**

*The Library Management System is designed to allows users to browse, borrow, return, and explore a collection of books.*   
*This system houses a database that contains a list of books, a list of users, and a list of authors.*

## User interaction

**Menu Preview (Command-Line):**  
*Users start by choosing the function they wish to use, by entering the number associated with the option.*
```   
        Welcome to the Library Management System!

        Main Menu:
        1. Book Operations
        2. User Operations
        3. Author Operations
        4. Quit
```
<br />
<br />

**1. User Operations:** *This is where new users can be added along with their necessary details:*
```
    Welcome to the user operations!
    
    User Operations:
    1. Add a new user
    2. View user details
    3. Display all users
    4. Main menu
```
Once the user chooses an option they can enter or view details depending on which number they select. Example below:
```
    User Operations:
    1. Add a new user
        What is the new users name?: Jane Doe
        What is the new users ID number?: 1234
    2. View user details
        Here are the user details!
        Name: John Doe, ID # 1234 borrowed the following books:
        Name: Jane Doe, ID # 5678 borrowed the following books:
    3. Display all users
        Here are the users in the list!
        John Doe has an ID of 1234
        Jane Doe has an ID of 1234
    4. Main menu
```
*Users need to be added first before moving forward to the following Operations:*
```
would you like to edit another contact? (y/n):
"y" will prompt them to enter the contact they would like to edit
"n" will send the user back to the menu list
```
<br />
<br />

**2. Book Operations:** *Opens the Book Operations menu where users pick which option they would like to choose. Example below:*

```
    Welcome to the books section!
    
    Book Menu:
    1. Add a new book 
    2. Borrow a book
    3. Return a book
    4. Search for a book
    5. Display all books 
    6. Main menu         
```
*Each choice collects and displays different details pertaining to the book menu. As seen below: *

```
    Book Menu:
    1. Add a new book
        What is the title of the book you would like to add?: "To Kill a Mockingbird"
        Who is the author for '"To Kill a Mockingbird"'?: Harper Lee
        What is the ISBN for '"To Kill a Mockingbird"'?: 123
        What is the genre for '"To Kill a Mockingbird"'?: Fiction
        What is the publication date for '"To Kill a Mockingbird"'?: 08/11/1960
    2. Borrow a book
    3. Return a book
    4. Search for a book
    5. Display all books 
    6. Main menu   
```
<br />
<br />

**3. Delete a contact:** *This function is where users can delete an existing contact:* 
```
Who would you like to delete from your list?:
```
*Once the user chooses the contact they would like to delete it will take them back to the menu list*
<br />
<br />

**4. Search for a contact:** *Searching for a contact in this function will allow the user to input the contact they are looking for, as seen below:*
```
Please enter the name of the contact you are searching for:
```
*After the user enters the contacts name, the contacts information will then be displayed:*
```
John Doe lives at 123 main, Email: johndoe@yahoo.com
```
<br />
<br />

**5. Display all contacts:** *When a user chooses this option all contacts will be displayed:* 
```
Here are your current contacts:
(contacts will display here)
```
<br />
<br />

**6. Export contacts to a text file** *This function will allow the user to export their contact and a new text file containing them will be created.*

## Invalid Input

**Error Messages:** *If a user attempts to input or execute something that is not within the application's capabilities or requirements, the application would generate an error message for the user, as seen below:*
```
Invalid Input.. Try again! ༼ つ ◕_◕ ༽つ
```
**Possible Causes:** *The error message shown above could occur due to various reasons, such as entering a non-existent contact, entering an invalid email, or encountering a technical glitch.*

**Resolution:** *To resolve the issue, the user would need to review their input, ensure that it meets the application's capabilities, and correct any mistakes they may have inputted.*

## Authors

**This application was a group effort created by:**     

*Chris Fletcher* https://github.com/cfletcher84

*Savannah Lyles* https://github.com/Savvy325
