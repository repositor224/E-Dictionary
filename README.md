# E-Dictionary
This project is an e-dictionary program made through Windowbuilder for help students memorize Java syntax. The program includes functions where students can add, delete, edit, merge, switch between databases, etc. along with outputting the syntax in dictionary into a PDF form. There is also a few sample syntax for each account user when the user registrates an account inside the e-dictionary program so that it gives an example to the user in terms of how to use the program. The project is also used as my ITGS IA (Internal Assessment) for my IB Diploma, in which I scored a 26/30 (before moderation).

This program uses Eclipse Windowbuilder for the front end, with the DB Browser for SQLite program as the back-end used for database storage. A relational database is implemented.

## Breakdown

The four sections of the dictionary are cover_page (doc), documentation, product and screencast:

- `The screencast is a demo of how the product runs. It includes a demo of both the Front End and the backend (Sqlite Database)`
  
- `The documentation consists of a series of planning files involving communication between me and my client.`

- `The product folder includes the complete project with front end and back end (DB Browser for Sqlite)

## Using the E-Dictionary

The first step you will need to do is to clone the repository using the following command:

`-git clone https://github.com/repositor224/E-Dictionary.git`

If you receive the error "Pip is not recognized" on CMD, go download Git!

After download, go to Product >> SyntaxDictionary.bat. Change SyntaxDictionary.bat into txt and input the following text into the system:

`JavaRunningEnvironment\bin\java.exe -jar SyntaxDictionary.jar`

and convert the bat that you have done that.

You can complete the next step in one of the two ways:

`(1) Extract the Product folder (folder with name "product") into D-disk, or`

`(2) Find the file "Sqlite.java" and input your file directory in the code inside file`

After that, you open the SyntaxDictionary.bat and then it is all completed!

## Note for IB Student and/or Developer

(1) If you encounter the following error while running the product:

`SQL error: database is locked`

It usually means that you open the SQL database with the system. To solve this problem, close the database and re-run the system.

(2) ITGS is replaced by "Digital Society" in 2024. The rules of the IA for Digital Society may vary with the ITGS.


