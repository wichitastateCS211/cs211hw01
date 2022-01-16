# Homework 1 - Counting Change
## Background
The program will prompt you to enter the quantities of coins and tell you how much money you have.

## Assignment Requirements
- Name your file \<WSUID\>_hw01.cpp
  - Substitute your WSUID in place of \<WSUID\>
- The program is only required to work if the numbers entered are 0 or positive integers.
  - If a negative number is entered, the user must be presented with an error message, and that
    input will be treated as a zero.
  - Error messages will be printed to the error stream using `std::cerr`.

## Sample Runs
```
Please enter the number of
        Quarters: 2
        Dimes: 2
        Nickels: 2
        Pennies: 2
You have 82 cents.

Please enter the number of
        Quarters: 2
Dimes: -3
Negative dimes treated like 0.
Nickels: 2
        Pennies: -1
Negative pennies treated like 0.
You have 60 cents.

Please enter the number of
        Quarters: 1
        Dimes: 0
        Nickels: 0
        Pennies: 0
You have 25 cents.
```

## Hints
- Because automated inputs and outputs are used, you must match the text and spacing exactly.
  - A tab is placed before the name of each coin.
- **General hint:** Keep your homework assignments; revisiting them after learning new principles
can reveal other ways to complete the homework.

## Reminders
- Be sure to include a comment block at the top of every submission with the required information.
  - Refer to the Coding Guidelines handout.
- Provide meaningful comments
  - If you think a comment is redundant, it probably is.
  - If you think a comment is helpful, it probably is.
  - Remember that you are writing comments for other programmers, not people who know nothing (Jon
    Snow) about coding.
  - Comments are more helpful when they explain why, not what or how.

## Preparing and Submitting
- Clone your homework repo to your local machine and complete the assignment.
- Commit your changes and push them to your remote.
- Initiate a pull request.
- Submit only a single \*.cpp file.
- Be sure to verify the results of the GitHub Action.
- You are responsible for testing your code.
- "But it runs on my machine!" will **not** earn you points.
