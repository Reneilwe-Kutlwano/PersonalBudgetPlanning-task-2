# PersonalBudgetPlanning-task-2

# ================Implementation of what I changed based on the feedback I recieved=====================

Hi Reneilwe,

Below is your feedback:

•	There were issues with your input validation process. You did not validate for negative values, zeros, and chars.
•	Around the decision ( rent or buy), you did not implement that correctly.
•	Some of your lines (in the code) were very long.
•	The coding standard in general must be improved.
Good luck for task 2.


One of the main problems my code had in task 1 was that I had no validation procedures in place that would validate the users input. In task 2 I had made sure that the users input would be validated because a user for instance may enter a string instead of a double and the system would expect a double so in order to validate and prevent such problems from occurring i used a try-catch block, that will pick up any exceptions found and inform the user what they did wrong and ask them to re-enter what they need to enter. 

The second issue I did not implement correctly was the decision for the user to choose between renting or buying. In order to fix this I had to look at the mistake I made in task 1 which was the if-statement, I had implemented an if statement which its condition and if the user chose to buy then the else statement would execute, this is essentially wrong, so in task 2 I had rectified that by creating 2 if-statements one with the condition that will validate what would happen if the user enters 1 to rent the property. Then the other if statement will also have a condition that will validate what would happen if the user enter 2 to buy the property. Being made aware of this problem helped me to be able to prevent this mistake from happening again.

The third issue was the fact that my code is too long. In task 1 was not at all aware of this until I recieved that feedback back. This was mainly due to the fact that I had not implemented my abstract class correctly so in task 2 I fixed this mistake by correctly implementing my abstract class and calling that method into the main, this shortened my lines of code in the main. I did also realize that I was repeating certain lines of code over and over and this made it seem as if my code is extremely wrong, so in task 2 I removed all of the unnecessary redundancy in code.

The fourth issue was just improving the coding standard in general. I did this by making sure that I understood the concepts I was dealing with in task 2 thoroughly such as how methods, object and classes work this helped improve my overall coding standard and by making sure that my code is not unnecissarily long.
