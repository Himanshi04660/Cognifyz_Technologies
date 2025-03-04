# Cognifyz_Technologies
This project is part of the Data Analysis Internship, where we perform data manipulation on a restaurant dataset to uncover insights about cuisines, city-wise restaurant distributions, and online delivery trends.

The dataset includes information about:

Types of cuisines served:
1) Restaurant locations
2) Customer ratings
3) Online delivery availability
By analyzing this data, we aim to extract key patterns and trends that could be useful for business decision-making in the food industry.

Tasks Covered
The notebook Level1_tasks.ipynb contains multiple data analysis tasks categorized under Level 1 of the internship. 

The tasks are:

Task 1: Top Cuisines Analysis
Identified the most popular cuisines based on their frequency in the dataset.
Used data preprocessing to handle missing values in the "Cuisines" column.
Counted the occurrences of each cuisine and sorted them to determine the top cuisines.
This analysis helps in understanding food preferences and trends in different locations.

Task 2: City Analysis
Analyzed restaurant distribution across different cities.
Counted the number of restaurants in each city and visualized the data.
Provided insights into which cities have the most food establishments.
Helped in identifying high-density restaurant locations for potential business insights.

Task 3: Price Range Distribution 
Examined the distribution of restaurants across different price ranges.
Categorized restaurants based on their price levels.
Used visualizations like bar plots or histograms to showcase price variations.
Provided insights into affordability and the pricing structure of restaurants.

Task 4: Online Delivery Analysis
Investigated the availability of online food delivery services.
Analyzed the proportion of restaurants offering online delivery.
Helped in understanding market trends and the adoption of online food services.
Could be useful for businesses looking to expand their delivery operations

1️⃣ Top Cuisines Analysis
1) Objective:
Identify the top three most common cuisines in the dataset.
Calculate the percentage of restaurants serving each of these top cuisines.
2) Approach:
Load and explore the dataset.
Count the occurrences of each cuisine type.
Find the top three most frequent cuisines.
Calculate the percentage by dividing the number of restaurants serving each cuisine by the total number of restaurants.
3) Outcome:
A ranked list of the most popular cuisines in the dataset.
Insights into how dominant certain cuisines are in the restaurant industry.

2️⃣ City Analysis
1)Objective:
Determine the city with the highest number of restaurants in the dataset.
Calculate the average rating of restaurants in each city.
Identify the city with the highest average rating.
2) Approach:
Group the dataset by city and count the number of restaurants per city.
Compute the average rating for each city.
Identify the city with the highest restaurant count and highest average rating.
3) Outcome:
Understanding which cities have the highest restaurant density.
Identifying cities with better-rated restaurants.

3️⃣ Online Delivery Insights
1) Objective:
Determine the percentage of restaurants that offer online delivery.
Compare the average ratings of restaurants that offer online delivery vs. those that don’t.
2) Approach:
Filter the dataset to separate restaurants that provide online delivery from those that don’t.
Calculate the percentage of restaurants offering online delivery.
Compute the average ratings for both groups and compare them.
3) Outcome:
Insights into the prevalence of online delivery services.
Understanding whether restaurants offering online delivery have higher or lower ratings compared to those that don’t.
