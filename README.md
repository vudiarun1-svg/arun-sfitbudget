# arun-sfitbudget
grocery optimization tool for building affordable high-protein meal plans for college students


FitBudget is a Python grocery optimization tool designed to help college students build affordable, high-protein grocery plans while staying within calorie and nutrition goals.

Why I Built It

As a college student interested in fitness, I wanted a better way to balance grocery costs with nutrition goals.

FitBudget allows a user to enter their grocery budget, how many days they need groceries to last, their daily calorie target, and their minimum protein goal.

The program then searches through more than 100 food options and generates a cost-effective grocery plan that meets the user's constraints.

Features
Custom grocery budget
Custom number of days
Daily calorie target
Daily protein target
100+ food options
Estimated grocery package costs
Protein, carbohydrate, fat, and fiber tracking
Fruit and vegetable requirements
Healthy-fat and whole-grain requirements
Whole-package grocery purchasing
Estimated cost per day
Daily nutrition plan
Grocery cost visualization
Daily protein visualization
Daily calorie visualization
Technologies
Python
Pandas
PuLP
Matplotlib
How It Works

The user enters information such as:

Grocery Budget: $200
Plan Length: 14 days
Daily Calories: 1200
Minimum Protein: 120g

FitBudget creates a constrained optimization problem.

The program attempts to minimize grocery cost while satisfying requirements such as:

Total spending must remain within the user's budget
Daily calories must remain near the calorie target
Daily protein must meet or exceed the minimum
Dietary fat must remain within a target range
Minimum fiber intake must be reached
Fruits and vegetables must be included
Healthy-fat foods must be included
Whole-grain foods must be included
Food consumed cannot exceed the amount purchased
Example Output

FitBudget generates:

Recommended grocery items
Number of packages to purchase
Estimated grocery cost
Remaining budget
Cost per day
Daily calories
Daily protein
Daily carbohydrates
Daily fats
Daily fiber
What I Learned

While building FitBudget, I practiced:

Python programming
Loops and conditional statements
Working with structured data
Pandas DataFrames
Mathematical optimization
Decision variables
Optimization constraints
Integer variables
Data visualization
Turning a real-world problem into a mathematical model
Future Improvements

Future versions could include:

More accurate and regularly updated grocery prices
Multiple grocery stores
Breakfast, lunch, dinner, and snack scheduling
Food preference filters
Allergy restrictions
Vegetarian and vegan modes
Cutting, maintenance, and muscle-gain modes
A web-based user interface
Disclaimer

Grocery prices in the current version are estimates and may vary by store and location. Nutrition values should be verified for specific products before using the program for personal dietary planning.
