[Back to Portfolio](./)

Tennis Simulator
===============

-   **Class:** CSCI 325 Object-Oriented Programming
-   **Grade:** B
-   **Language(s):** Java
-   **Source Code Repository:** (Please [email me](mailto:weddingzack@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

I worked with a partner on this project. We came up with the idea to simulate a tennis match. When the program starts, the first player must choose heads or tails to see who is serving first. After the server is decided, they get to decide how hard the serve it (between a difficulty of 1 and 3). The harder they serve it, the more likely they are to mess up the serve. However, if they do not mess up the serve, it is then harder for the other player to return. After the intial serves, the players return the ball in a very similar fashion until someone messes up. The simulator goes by farily basic tennis rules (first to 60 wins the set, best of three sets).

## How to compile and run the program

```bash
cd ./project
javac TennisGame.java
java TennisGame.java
```

## UI Design

The program includes five different class (AwardPoint, Return, ScoreBoard, StartOfGame, and TennisGame). The AwardPoint class decides which player to award a point to based on which player hit the ball out of bounds. The Return class deals with returning the serve and returning other returns. After the difficulty of the return is decided, it is determined whether this return will be in bounds or picking a random number. The harder the difficulty of the serve, the smaller chance the return has of being successful. The difficulty of the previous return also factors into whether the current return will be successful or not. The harder the previous return, the more difficult it will be for the current return to be successful. The ScoreBoard class displays the scoreboard and determines when a set or match is over by the point values and who won the match or set. The StartOfGame class does the initial coin flip to see who serves first as well as the initial serve. Lastly, the TennisGame class ties all of these other classes together to make the program function.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
