[Back to Portfolio](./)

Data Parser
===============

-   **Class:** Programming for Investigators
-   **Grade:** A
-   **Language(s):** Python
-   **Source Code Repository:** (Please [email me](mailto:weddingzack@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

This project parses data from multiple HTML files and exports the data into a database for easy use. After exporting the data into a database, the user is prompted to enter a search term. If this term is found within the database, it prints out the row in which the term was found. In addition to this, the number of times that the search term was found in the database is printed.

## How to run the program

```bash
python .\Wedding_Final_Assignment.py
```

## UI Design

The programs first import the necessary libraries (re, sqlite3, and os). Next, the program connects to the database and drops the database if it already exists.

The program then uses regex to filter out a date, monkier, number of posts, and content from the current post in the forum from the HTML files. These reset after each post. Once all values are filled, they are exported into the database. After all posts have been accounted for, the database is closed.

Error checking has been put into place to ensure database entries and file openings have been done correctly.

![screenshot](images/CYBR-6150 Final1.png)  
Fig 1. Running the program and searching a term

![screenshot](images/CYBR-6150 Final2.png)  
Fig 2. Program outputs the number of times a term is in the database

![screenshot](images/CYBR-6150 Final4.png)  
Fig 3. Accessing the database

![screenshot](images/CYBR-6150 Final3.png)  
Fig 4. Error checking

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
