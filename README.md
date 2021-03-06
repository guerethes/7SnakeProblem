# 7SnakeProblem

Project
======

To solve the problem, the technique was used Brute-force. Where a thread with random initial positions is initialized and which snake is found to have a smaller size (the size considered in this case is the sum of the elements). The algorithm only ends when no solution is found, in which case a "fail" message will be displayed to the user. If the algorithm finds some solution the solution will be shown in the console with the step by step taken by each snake until arriving at the solution found and also the value of the sum of the houses will be displayed.

Getting Started
======

Prerequisites
------
	To run the project it is necessary that the machine has Java 8 installed.

	It is that you have a grid, with the specifications determined by the challenge.

Execution
------
	To execute the project it is necessary to execute the following set of instructions:

1 - Enter the source code folder

2 - Execute the following command
    
    java Main "path"
    
	Example: java Main /Users/guerethes/Downloads/7SnakeProblem-master/example2.csv

Note¹ : where "path" will be the path of the grid that will serve as input to the program.

Note² : If a directory is not informed, the program returns the message: "File path not informed";

Note³ : If an invalid directory is informed system displays the message "File not exists."

### Output
Two lines, each representing a snake with the necessary steps to find the desired solution. 
At the end is shown the sum of the body of the snake.

e.g.:
```
Snake A
	Step 1 -> X:5 - Y:6
Sum -> 241

Snake B
	Step 1 -> X:8 - Y:10
Sum -> 241
```