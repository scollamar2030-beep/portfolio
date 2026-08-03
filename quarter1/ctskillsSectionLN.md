Annex A
Computational Thinking Exercise: "Smart School Canteen Queue"


Section: Barium                                                        Score:____________
C# / Name: Shannon Collamar                                Date: August 2, 2026

Scenario
The PSHS school canteen is small and often gets crowded during lunch break. Students line up to buy food, but the process is slow because:
Some students take too long to decide what to order.
The cashier has to manually calculate totals and give change.
There is no system to track which food items are running out.
Your group’s task is to decompose this problem into smaller, manageable parts that could be solved with computational thinking (CT) Skills.
Step 1: Identify the Big Problem
Main Problem: The PSHS school canteen becomes crowded during lunch because ordering and payment takes too much time, and there is no system to monitor food availability. This causes long waiting lines, delays, and inconvenience for students and staff.
Step 2: Identify three to four Sub-Problems
Please list possible sub-problems:
1. Students spend too much time deciding what food to order which slows down the queue because the students behind them have to wait.
2. The cashier manually computes the total cost and change which may result in mistakes.
3. There is no inventory system to monitor the food availability. Students may order items that are already sold out.
4. Students may cut in line or become confused whose turn it is because there is no organized queue management system.


Step 3: Define Computational Thinking Approaches
For each sub-problem, apply CT skills:
Sub-Problem
CT Skill
Example Solution
Students take too long to decide what to order.
Abstraction
Display a digital menu composed of prices, pictures, and available items to make students decide beforehand.
The cashier manually calculates totals and changes.
Algorithm Design
Create a system that automatically adds item prices, accepts payment, computes the change, and displays the amount due.
No inventory tracking.
Pattern Recognition
Track the number of food items sold every day to predict which foods usually run out first and automatically update stock levels.
No organized queue system.
Decomposition
Divide the queue into ticket assignment, waiting, serving, and exit, so each step is handled professionally.

 




Step 4: Draw a flowchart or write a pseudocode for the identified sub-problem


START

Set Total = 0

Choose food
Add its price to Total

Show Total
Enter Payment

If Payment is enough
    Compute Change
    Show Change
Else
    Show "Not enough payment"
End if

END


