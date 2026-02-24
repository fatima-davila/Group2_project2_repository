# Files Contained in This Repository
This repository contains Group B's files for CIVE 202 Project #2. {EXPLAIN WHAT EACH FILE IN THE REPOSITORY IS}
readme file- explains the code 
project 2 code- the code that does complete what is asked of our group from the client

# Project Summary
The Nebraska Department of Transportation (NDOT) currently uses a Microsoft Excel sheet to perform calculations for concrete mix design. NDOT wishes to migrate this calculation work to a Python-based system, which is contained in this repository. By transferring its concrete mix design calculations from Excel to Python, NDOT intends to improve the reliability of its mix design process. Migrating to Python will ensure that the logic used in calculations is fixed, transparent, and repeatable. This will make the calculation logic more suitable for use in a future web-based tool.


# Project Objectives
- Translate NDOT Excel mix design formulas into Python
- Create reusable engineering calculation functions
- Implement sequential user input collection
- Generate a client-readable output summary
- Validate the model using four realistic concrete mix scenarios
- 
# Part 1 setup and constants
Each function replicates a specific Excel formula from the NDOT worksheet.

Water Weight Calculation
Q=(A+B+C+D)×E
Calculates total water weight based on the water–cementitious ratio.

Cementous Material Volumes
V=weight/(sg*62.4)

Air and Water volumes
Air volume = (%air/100)* 27
water volume = water weight/62.4

# User Guide
1. Open the Jupyter Notebook.

2. Run all function definition cells.

3. Execute the input cell.

4. Enter values when prompted.

5. Review the computed material breakdown.
