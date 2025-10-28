NYC SAT Score Analysis 📊

This project examines the SAT performance of public high schools in New York City using Python’s pandas. Inspired by a dataset published by the NYC Department of Education, the analysis focuses on three key questions:

Which schools achieve the best math scores?
We define “best” as at least 80 % of the maximum possible math score of 800. The results are stored in a DataFrame named best_math_schools, listing school names and their average math scores, sorted from highest to lowest.

Which schools rank at the top when considering all three SAT sections combined?
The script calculates a new column total_SAT (sum of average math, reading, and writing) and selects the top 10 performing schools. These are stored in a DataFrame top_10_schools with columns school_name and total_SAT, sorted descending.

Which borough shows the greatest variability in combined SAT performance?
Grouping by borough, we compute the standard deviation of total_SAT and identify the single borough with the highest variation. The result is captured in a DataFrame largest_std_dev containing four fields: borough, num_schools, average_SAT, and std_SAT, with numeric values rounded to two decimals.
