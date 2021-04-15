Wedding Seating Problem
========================
By Zhijing Eu
zhijingeu@yahoo.com

Apr 2021

The Wedding Seating Problem is a combinatorial puzzle that often arises when planning for large
banquets or parties where guests need to be assigned to tables but certain people need to be kept 
seated together or seated apart

Description of Files: 
* Wedding_ Seating_Arrangement_Solver.xlsm - An Excel implementation of a Brute Force Search approach to solving the problem
* WSP_BruteForceMethod.ipynb - A Python Notebook that 'mimics' the Excel implementation with some extra bells & whistles
* WSP_SimAnnealingMethod.ipynb - A Python Notebook that uses a different approach called Simulated Annealing to solve the same problem
* CalculateNoOfPossibleCombinations.ipynb - A supplementary Py Notebook that has some code to calculate the no of possible combinations for table seating arrangement
* Example_Guests96pax_TableSize8pax.xls and Example_Guests30pax_TableSize8pax.xls - Example Upload files to transfer inputs from the Excel Tool to Python Notebooks
* Output_BruteForce_Example_Guests96pax_TableSize8pa.csv and Output_BruteForce_Example_Guests30pax_TableSize8pa.csv - Example output files from Python Notebooks that can be used to transfer results back to the Excel Tool

A Walk Thru video covering the details of this repo available here:
https://youtu.be/zKUuijcyZoc

This Github repo that is accompanied by a Medium article that also covers how the code works in detail as well as 
highlights other possible solving approaches and providing links to other code/resources on the topic:
https://zhijingeu.medium.com/building-a-wedding-seating-plan-using-probabilistic-methods-simulated-annealing-8f31d8987026

The code used for Simulated Annealing is heavily based on the code available on this other Github Repo :
http://linanqiu.github.io/2018/03/05/Wedding-Seat-Optimization
with some additional tweaks/additions that:

1.Provides the option to either generate 'dummy' data for testing or allow users to import guest lists/conditions from the earlier Excel tool 

2. Checks the logical consistency of the seating constraints 

3.View the results in a more user friendly way.  
