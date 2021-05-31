# PersonalBudgetPlanning-task-2
### ============TABLE OF CONTENTS===============

1. Overview
2. Features of the project.
3. Development dependencies.
4.Technology + software required
5. Implementation of feedback from task 1
6. Running of the project.
7. Contributors and sources

### ============================================


### ===================OVERVIEW=================

This particular project is a personal budget planning application that is used to solve the problem of not being able to fully calculate and plan out your budget. This application provides an easier seamless way of calculating all of the important aspects of creating a budget, by asking the user to input their expenses, monthly income, tax deductions and also whether they are renting and paying a monthly rental or they are buying and paying a monthly repayment.The application will then ask the user if they want to purchase a car. The application uses the users input and calculates how much is available at the end of the month along with how much they actually pay on either their monthly rental or monthly repayment.

The motivation behind the project for me was to be able to create a user friendly application that won't confuse the user along with the coder who wrote this program. From a personal experience alot of people do struggle with being able to plan out their finances and create a budget because it is so time consuming. With this project I just wanted to create something that will be less time consuming for the user and accurate as possible.



### ==================FEATURES OF THE PROJECT=================

This project includes the following:

1. Welcome message.
2. Message to request the user to enter their monthly income before deductions and tax deducted.
3. Message to request the user to enter their monthly expenses.
4. Ability to calculate the users monthly money available if they choose to rent and their monthly home loan repayment if they choose to buy property.
5. Ability to calculate loan repayments of a vehicle if the users chooses to purchase a vehicle.
6. Regular notices of whether your expenses are over your monthly income.


### ===================DEVELOPMENT DEPENDENCIES======================

1. Microsoft.NETCore.App
2. Visual studio 2019.



### ==============TECHNOLOGY + SOFTWARE REQUIRED=================
1. A laptop that supports windows10 and microsoft.
2. Not supported on linux.
3. Microsoft visual studio 2019.
4. Microsoft.NET framework.



### =================IMPLEMENTATION OF THE FEEDBACK FROM TASK 1================

Hi Reneilwe,

Below is your feedback:

•	There were issues with your input validation process. You did not validate for negative values, zeros, and chars.
•	Around the decision ( rent or buy), you did not implement that correctly.
•	Some of your lines (in the code) were very long.
•	The coding standard in general must be improved.
Good luck for task 2.
### ===================================================================

One of the main problems my code had in task 1 was that I had no validation procedures in place that would validate the users input. In task 2 I had made sure that the users input would be validated because a user for instance may enter a string instead of a double and the system would expect a double so in order to validate and prevent such problems from occurring i used a try-catch block, that will pick up any exceptions found and inform the user what they did wrong and ask them to re-enter what they need to enter. 

The second issue I did not implement correctly was the decision for the user to choose between renting or buying. In order to fix this I had to look at the mistake I made in task 1 which was the if-statement, I had implemented an if statement which its condition and if the user chose to buy then the else statement would execute, this is essentially wrong, so in task 2 I had rectified that by creating 2 if-statements one with the condition that will validate what would happen if the user enters 1 to rent the property. Then the other if statement will also have a condition that will validate what would happen if the user enter 2 to buy the property. Being made aware of this problem helped me to be able to prevent this mistake from happening again.

The third issue was the fact that my code is too long. In task 1 was not at all aware of this until I recieved that feedback back. This was mainly due to the fact that I had not implemented my abstract class correctly so in task 2 I fixed this mistake by correctly implementing my abstract class and calling that method into the main, this shortened my lines of code in the main. I did also realize that I was repeating certain lines of code over and over and this made it seem as if my code is extremely wrong, so in task 2 I removed all of the unnecessary redundancy in code.

The fourth issue was just improving the coding standard in general. I did this by making sure that I understood the concepts I was dealing with in task 2 thoroughly such as how methods, object and classes work this helped improve my overall coding standard and by making sure that my code is not unnecissarily long.


### ==================RUNNING OF THE PROJECT======================

1. Open visual studio 2019.
2. Creat a new console application called PersonalBudgetPlanning2 (This console application needs to strictly be for C#).
3. Copy the program cs code (This is the parent class).
4. Delete everything on the page >> at this point you should just have a blank page. 
5. Paste the program cs into visual studio 2019.
6. On the solution explorer right click on the PersonalBudgetPlanning2 and scroll to "Add" and add a new class library.
7. Copy the class cs code.
8. Delete everything on the page >> at this point you should just have a blank page. 
9. Paste the class cs into the class library created (This is the child class).
10. Go back to the program cs and click the green button on the visual studio toolbar to run the program.
11. The programme will ask you to input data, all of this needs to be in the form of a decimal number.


### ===================CONTRIBUTORS + SOURCES========================

1. Reneilwe-Kutlwano Motlhabi.
2. https://www.geeksforgeeks.org/.
3. Troelsen, A. and Japikse, P. 2017. Pro C# 7 with .NET and .NET Core. 8th ed. Minnesota and Ohio: Andrew and Philip.
