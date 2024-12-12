Used Cars Dataset Analysis
Overview
This project analyzes a dataset of vehicle listings from Craigslist to uncover insights about car manufacturers, pricing, conditions, fuel types, and other attributes. The dataset includes 426,880 rows and 26 columns with information such as price, year, condition, and location of vehicles.
The analysis aims to identify trends, anomalies, and business-critical insights using Python-based data cleaning, exploratory data analysis (EDA), and visualization techniques.
________________________________________
Features
1.	Data Cleaning:
o	Handling missing values through imputation or removal.
o	Standardizing text data (e.g., vehicle models).
o	Converting data types for consistency.
o	Dropping unnecessary columns such as URLs and descriptions.
2.	Exploratory Data Analysis (EDA):
o	Insights into the top car manufacturers, models, and conditions.
o	Distribution analysis across states and vehicle types.
o	Examination of average vehicle prices based on attributes such as condition, fuel type, transmission, and number of cylinders.
3.	Visualizations:
o	Bar charts, pie charts, and histograms to illustrate trends.
o	Comparative plots to analyze pricing across categories.
________________________________________
Technologies Used
•	Python
•	Pandas
•	Matplotlib
•	Seaborn
•	Jupyter Notebook
________________________________________
Dataset
The dataset contains information about car listings, including:
•	Categorical Attributes: Manufacturer, model, condition, fuel type, transmission, etc.
•	Numerical Attributes: Price, year, odometer readings, etc.
•	Location Attributes: State, latitude, and longitude.
________________________________________
Key Insights and Business Questions Answered
1.	What are the most common car manufacturers and models?
o	Analyzed the top 10 manufacturers and models based on the number of listings.
o	Visualization: Bar charts of manufacturers and models.
2.	What is the distribution of car conditions in the dataset?
o	Identified proportions of conditions like "Good," "Excellent," and "Fair."
o	Visualization: Pie chart of car conditions.
3.	How do car prices vary by condition?
o	Calculated and visualized average prices for each condition.
4.	What are the preferences for fuel types among the top 10 manufacturers?
o	Explored fuel type distribution across popular car manufacturers.
o	Visualization: Stacked bar chart.
5.	How does transmission type affect the average price of vehicles?
o	Analyzed pricing trends for automatic, manual, and other transmission types.
6.	What are the most common vehicle types and their price ranges?
o	Investigated listings and pricing by vehicle type.
o	Visualization: Separate bar charts for distribution and average price.
7.	How do fuel types influence pricing?
o	Explored the relationship between fuel types (e.g., gas, diesel, electric) and average prices.
8.	How does the number of cylinders correlate with vehicle prices?
o	Visualized average pricing for vehicles with varying cylinder configurations.
________________________________________
Installation and Usage
1.	Clone this repository: 
2.	git clone https://github.com/asaazamaan/vehicle-analysis.git
3.	Install the required Python libraries: 
4.	pip install pandas matplotlib seaborn
5.	Place the dataset (vehicles.csv) in the project directory.
6.	Run the Jupyter Notebook or Python script to reproduce the analysis.
________________________________________

Acknowledgments
•	Dataset sourced from Craigslist. You can find the dataset on: https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/data
•	inspired by Netflix EDA Project. You can find the project on: https://github.com/Mohamed2bdelaziz/Netflix_EDA/blob/main/Netflix__EDA.ipynb
•	This project was developed as part of the **MLSC Data Science & Machine Learning Course**.
