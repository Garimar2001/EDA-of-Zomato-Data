EDA of Zomato Data

Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a Zomato restaurant dataset. The dataset contains information about various restaurants, including their location, cuisines, ratings, reviews, and other characteristics. The goal of the analysis is to extract meaningful insights, understand trends, and visualize key data points to better understand the restaurant industry and consumer preferences.

Steps Taken
1. Data Cleaning and Preprocessing
Checked for missing values and handled them appropriately.
Converted data types for relevant columns (e.g., ratings, prices).
Handled outliers and inconsistencies in the data.
Renamed columns for better readability.
2. Exploratory Data Analysis (EDA)
Country-level analysis: Identified countries with the most restaurants, top-rated countries, and regions with the highest number of votes.
City-level analysis: Analyzed the distribution of ratings and the influence of cuisine type on ratings.
Rating and Price Analysis: Explored the relationship between price range and ratings.
Online Delivery: Investigated whether the availability of online delivery impacts restaurant ratings.
Top Cuisines: Found the most popular cuisines across countries and cities.
3. Visualization
Histograms and Bar charts for distribution of ratings, prices, and votes.
Pie charts for the proportion of online delivery availability.
Heatmaps for correlation between different factors.
Box plots for rating distribution across different price ranges.
4. Insights and Conclusion
Restaurants offering online delivery tend to have a higher average rating.
Higher price range correlates with better ratings in certain regions.
Popular cities like New Delhi and Mumbai have a high concentration of top-rated restaurants.
The aggregate rating distribution reveals a slightly skewed rating trend across different countries.
Requirements
The following libraries are used in this analysis:

Pandas: For data manipulation and analysis.
Numpy: For numerical calculations.
Matplotlib: For visualizations.
Seaborn: For statistical data visualization.
Openpyxl: For writing to Excel files (if required).
The ratings of restaurants vary significantly across countries. Some countries like India have a higher proportion of 5-star rated restaurants, while other countries show a more evenly distributed rating pattern.
Cuisine Types
Popular cuisines like Indian, Chinese, and Italian dominate the dataset. By analyzing the average ratings per cuisine, we can see how ratings vary across different types of food.
Online Delivery
Restaurants with online delivery have slightly higher ratings compared to those without, especially in urban areas.
Attaching few screenshots of code-
![image](https://github.com/user-attachments/assets/0aa466e3-79fd-4bd3-ba04-cfde8367b170)
![image](https://github.com/user-attachments/assets/f37b0b0a-d954-4b39-8e59-b6048cbef3a4)
![image](https://github.com/user-attachments/assets/da6bcf0b-b2f8-4efd-91da-562d567dce8b)
![image](https://github.com/user-attachments/assets/5b30d9c5-50e0-4205-895c-b372732c4080)
![image](https://github.com/user-attachments/assets/70850646-b306-4ea2-bdd0-bd0907c76fb3)
![image](https://github.com/user-attachments/assets/4fe425f2-2517-4fae-a9ca-0dbd1d7de000)





