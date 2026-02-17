# DAY-4-Challenge-Emergency-Resource-Dispatch-
Project Description

This project analyzes emergency resource requests reported during a disaster drill. The program classifies each request into different demand levels and applies a personalized filtering rule based on the length of the student’s full name.

The implementation strictly follows the given constraints. It uses lists, for loops, and conditional statements only. No advanced Python functions like list comprehension, dictionaries, sets, max, min, sum, or sorting functions are used.

Personalization Details

Full Name: jagadish reddy
Length excluding spaces L: 13
PLI Value: 1
Applied Rule: Rule B
Rule B removes all High Demand requests from the final dispatch report.

Classification Rules

If request is less than 0 it is marked as Invalid Request
If request is 0 it is considered No Demand
If request is between 1 and 20 it is Low Demand
If request is between 21 and 50 it is Moderate Demand
If request is greater than 50 it is High Demand

Program Features

The program:
Accepts a list of integer resource requests
Processes each value using a for loop
Classifies values into different demand lists
Counts total valid requests
Counts how many requests are removed due to PLI rule
Displays final filtered dispatch report
