Ant Count Analysis:

This repository contains Python scripts for analyzing ant count data related to different sandwich configurations, specifically focusing on the influence of bread type, topping, and butter presence. The project aims to descriptively visualize and potentially infer relationships between these variables and the number of ants attracted.


Project Description:

This project processes a dataset (sandwich.csv) containing records of ant counts observed under various experimental conditions involving different types of bread, toppings, and the presence or absence of butter. The core objective is to understand how these factors individually, and potentially in combination, affect ant attraction. The scripts generate bar graphs visualizing the mean ant count for each category, providing a clear descriptive overview of the data.



Features
Data Loading  Reads data from sandwich.csv and handles non-numeric antCount values by converting them to numeric and filling missing values with zero.
Mean Calculation: Computes the mean ant count for each distinct bread type, topping type, and butter presence.
Descriptive Visualizations: Generates bar plots using matplotlib and seaborn to visually represent Mean Ant Count by Bread TypeMean Ant Count by Topping TypeMean Ant Count by ButterPresenceData 




cd TU-Dortmund-Assignment
Dependencies:Install the required Python libraries using pip:pip install pandas matplotlib seaborn
python main.ipynb

