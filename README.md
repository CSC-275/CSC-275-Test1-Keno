# Keno Game Project

## Game Description
Keno is a lottery-like gambling game where 20 numbers are randomly selected out of numbers ranging from 1 to 80. 
Players wager on how many numbers they can match out of the numbers that are randomly generated.

The program will prompt the user for 10 numbers they will try to match in the range of 1-80. 
The program watches for numbers that the user enters that are out of range, invalid data type, 
or when duplicate numbers have been entered and allows the user to correct their mistake. 
Once the 10 numbers have been picked, the program will generate 20 random numbers in the range of 1-80 
without any duplicate numbers. The program will report the the winning Keno numbers generated, 
the player’s picks, and which numbers they matched. The program tells the player what they have won (<b>Use table below</b>). 
<ul>
  <h3>Prizes</h3>
  <li>10 of 20 wins $25,000</li>
  <li>9 of 20 wins $2,500</li>
  <li>8 of 20 wins $250</li>
  <li>7 of 20 wins $50</li>
  <li>6 of 20 wins $10</li>
  <li>5 of 20 wins $5</li>
  <li>less than 5 wins $0</li>
</ul>
The program allows the user to play repeatedly if they would like to continue playing.

## Game Interface Prototype Example
<pre><b> ********************
 * Let's Play Keno! *
 ********************

To play Keno, select 10 numbers in the range of 1-80.

Enter your pick #1: 22
Enter your pick #2: 50
Enter your pick #3: 5
Enter your pick #4: 87
87 is out of range! Try again. Enter your pick #4: 78
Enter your pick #5: 5
5 was already picked! Try again. Enter your pick #5: 36
Enter your pick #6: 48
Enter your pick #7: Bob
Invalid data input! Try again. Enter your pick #7: 64
Enter your pick #8: 65
Enter your pick #9: 60
Enter your pick #10: 43

----------------------------------Results----------------------------------
Keno Numbers: 5 22 24 31 34 36 39 43 44 48 49 50 52 58 64 65 68 69 72 78 
Player Picks: 5 22 36 43 48 50 60 64 65 78 
You matched: 5 22 36 43 48 50 64 65 78 
Matching 9 of 20 numbers wins $2,500

Play another round? (y/n): y

To play Keno, select 10 numbers in the range of 1-80.

Enter your pick #1: 55
Enter your pick #2: 64
Enter your pick #3: 36
Enter your pick #4: 60
Enter your pick #5: 58
Enter your pick #6: 39
Enter your pick #7: 72
Enter your pick #8: 78
Enter your pick #9: 45
Enter your pick #10: 2

----------------------------------Results----------------------------------
Keno Numbers: 5 22 24 31 34 36 39 43 44 48 49 50 52 58 64 65 68 69 72 78 
Player Picks: 2 36 39 45 55 58 60 64 72 78 
You matched: 36 39 58 64 72 78 
Matching 6 of 20 numbers wins $10

Play another round? (y/n): n


THANKS FOR PLAYING!!
</b></pre>

## Version 1
Create a working version of the game that matches the example prototype interface shown above. This version should be completed using only procedural coding learned in CSC 175.

## Version 2
Use an object oriented paradigm approach to refactor the version 1 code. The completed project must be a fully object oriented solution that consists of multiple classes.


