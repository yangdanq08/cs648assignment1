# cs648assignment1
Solve these JavaScript conditional logic and looping problems. Download the beginning files Download Download the beginning files for this lab to help get you started.

Larger or Smaller? (5 points)

Create an application that accepts two integers within two separate prompts. Then, display only the larger of the two within the browser window. Don’t forget to handle the fact that the two could be equal.

The “Coin Flip” Game (10 points)

In this part of the assignment you will explore what you’ve learned so far about variables, prompts, conditionals, operators, math, and more to create a “coin flip game”. To complete the game follow the steps outlined below:

Begin your application by creating a variable called coinFlip and set it equal to a random number. You will have to use a Math method to get this number.
Prompt the user to select “Heads or Tails” and set the result to a new variable called choice.
Use a conditional to check the result of the coin flip. If it’s less than a certain number, it will be heads. If it’s greater than a certain number, it will be tails.
If the result is heads and the user selects heads, display the following message within an alert: 
The flip was heads and you chose heads...you win!
If the result is heads and the user selects tails, display the following message within an alert: 
The flip was heads but you chose tails...you lose!
If the result is tails and the user selects heads, display the following message within an alert: 
The flip was tails but you chose heads...you lose!
If the result is tails and the user selects tails, display the following message within an alert: 
The flip was tails and you chose tails...you win!
Use two Math methods to get a solid whole number on the coin flip. Modify the evaluation of the expression in your conditional so that it now checks for a Boolean result.
The “Coin Flip” Game Redux (10 points)

In this part of the assignment you will explore what you’ve learned so far about variables, for loops, conditionals, operators, math, and more to create a different version of the “coin flip game”. To complete the game follow the steps outlined below:

Begin your application by declaring a variable called coinFlip. Do not assign the variable a number just yet.
Create a for loop that loops 10 times.
Within the for loop assign a randomly generated number to You will have to use a Math method to get this number. Also, make sure to round that number off so that you get either a 0 or 1 as the result.
Use a conditional to check the result of the coin flip. If it’s 0, write out “Heads” into the console window. If it’s 1, write out “Tails” into the console window.
The “Coin Flip Streak” Game (5 points)

In this part of the assignment you will explore what you’ve learned so far about variables, do while loops, conditionals, operators, math, and more to create a “coin flip streak game”. The point of this simple game is to see what kind of streak you can get to (how many times “Heads” comes up in a row before “Tails” does to end the game). To complete the game follow the steps outlined below:

Begin your application by declaring a variable called coinFlip. Do not assign the variable a number just yet.
Create a do while loop.
Within the do while loop assign a randomly generated number to You will have to use a Math method to get this number. Also, make sure to round that number off so that you get either a 0 or 1 as the result.
Use a conditional to check the result of the coin flip. If it’s 0, write out “Heads” into the console window. If it’s 1, write out “Tails” into the console window.
Set the condition of the do while loop to end once the coinFlip becomes “Tails”.
Looping a Triangle (5 points)

Write a loop that displays the following triangle within a console window:

#
##
###
####
#####
######
#######

Odd or Even? (5 points)

Write a loop that will iterate from 0 to 15. For each iteration it will check if the current number is odd or even, and display a message in the console window.

Sample Output:
"0 is even" 
"1 is odd" 
"2 is even"

Marco! Polo! (5 points)

Create an application which iterates numbers from 1 to 100. For multiples of 3, print "Marco!" instead of the number and for multiples of 5, print "Polo!" instead of the number. For numbers which are multiples of both 3 and 5 print "Marco! Polo!". This is a VERY common JavaScript interview question and you should know how to do this. You will need to take advantage of the modulus operator to accomplish this task.

Countdown (5 points)

Write an application that counts down to 0 based on the number that a user passes into a prompt. If the number is 10, it should count down from 10 to 0. If the number is 100, it should count down from 100 to 0 and so on.
