------------------
Overview


This program detects the number of times employees have coincided hours in the office. The schedule is a text file with the name of an employee and the schedule they worked.
The program reads the input file, stores, separates and compares the data and shows the coincidences. The result is displayed in the console.
------------------
Architecture
------------------

The program its developed in JavaScript and uses Node.js to read the input file. The input file is in the same directory as the program and its named "input.txt".

------------------
Approach and methodology
------------------

The input file is read line by line and each line is split into two parts: the name of the employee and the schedule. The name of the employee is used as the key for the schedule data in a object called schedule.

Next, the program loops through each pair of employees and calculates the number of times they have coincided in the office by looping through each day of the schedule of one of the employees and checking if the other employee also worked on that day. If they both worked on the same day, the count is incremented.

------------------
Running the program locally
------------------

1-Download and extract the folder.

2-Open a terminal and navigate to the directory where the program files (main.js & input.txt) are located.

3-Its running in NODEJS & npm (In case dont have NPM run "npm install" in terminal)if you don't have node you can donwload it from https://nodejs.org/ and install it.

4-Use the "input.txt" to manage and manipulate the input as you want.

5-Run the program by typing node index.js in the terminal and press enter.

6-The result will be displayed in the console.

Note: The program assumes that Node.js and npm are already installed on your system.


