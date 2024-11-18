[Back to Portfolio](./)

Overlap Coverage
===============

-   **Class:** CSCI 315 Data Structures
-   **Grade:** C
-   **Language(s):** C++
-   **Source Code Repository:** (Please [email me](mailto:weddingzack@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

This project finds the minimum overlap of sets that cover all points. For example, if there were multiple group projects that needed to be presented at the end of the semester and the professor must grade everyone at least once, they would want to minimize the number of presentations that they see. They can do this by finding the minimum amount of overlap. Similarly, the project aims to find the minimum amount of overlap within a set of numbers.

## How to compile and run the program

```bash
cd ./project
g++ main.cpp MinimumOverlap.cpp -o
.\main.cpp small30.set
```

## UI Design

The program parses the dataset and is able to find the minimum overlap with the help of the minOverlap function. This function is a recursive function that optimizes overlap by examining different combinations of sets and always keeping track of the smallest solution. 

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
