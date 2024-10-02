## ECE 2112 | EXPERIMENT 4 - Data Wrangling and Data Visualization
**I. Intended Learning Outcomes:**
1. To identify the codes and functions needed in cleaning and visualizing data
2. To be able to apply and use the different codes and functions in creating a Python program that will
be used in data wrangling and data visualization

**II. ECE BOARD EXAM PROBLEM:** Using data wrangling and data visualization technique with
storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given.
1. Create the following data frames based on the format provided:
- Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas
- Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as
Instrumentation and hometown Luzon
- Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is
constant as Mindanao and gender Female
- In addressing this problem, data wrangling was initially performed by structuring the data using the Pandas library. Following the provided instructions and parameters, the required data was extracted utilizing Pandas syntax, specifically through array extraction and indexing techniques.

2. Create a visualization that shows how the different features contributes to average grade. Does
chosen track in college, gender, or hometown contributes to a higher average score?
- In this problem, I used seaborn to graph Bar Plots of the Average by each parameter (a. Track, b. Gender, c. Hometown)
