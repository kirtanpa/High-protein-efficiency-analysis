Title: Branded Food Protein Analysis
Course: CS 210: Data Management for Data Science
Collaborators: Kirtan Patel
The "How-To" (Technical Instructions)
Requirements:

Python 3.9.6

Libraries: pandas, numpy, matplotlib, seaborn

Setup:

Download the ‘Branded’ USDA CSV file from ‘Latest Downloads’ via. https://fdc.nal.usda.gov/download-datasets 

Place the USDA CSV files in the project root directory.

Run python main.py.

Key Findings
-Top Protein Sources: After filtering, the most efficient sources were peanut butter, eggs, and pasta, which averaged a protein-to-calorie ratio of about 7-6g protein per kcal.

-Predictive Accuracy: The linear regression model showed a weak relationship between calories and protein. With the model being off by 8.71g, the model demonstrated that caloric density alone is not a reliable predictor of protein content across branded foods.

-Category Variance: "Other" and "Snack" categories showed the highest variance in protein efficiency, suggesting that processed branded foods are much less consistent in nutritional density than whole-food categories like Meat or Dairy.

