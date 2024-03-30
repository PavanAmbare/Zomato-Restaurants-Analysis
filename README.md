# Zomato-Restaurants-Analysis

# About Dataset
This dataset is a collection of restaurants that are registered on Zomato in Bengaluru City. In this dataset, we have more than 50000 rows and 17 columns, a fairly large dataset. 

1. **Importing the dataset:** The dataset is read into a Pandas DataFrame.

2. **Basic analysis:** The head and tail of the DataFrame are displayed to get a quick look at the data. Information about the dataset (e.g., data types, non-null counts) is printed, as well as a summary of the dataset's statistics.

3. **Data cleaning:** Redundant columns are dropped, and remaining columns are renamed for clarity. The 'rating' column is cleaned by extracting numeric values, converting them to float, and filling missing values with 0. The 'name_of_restro' column is standardized to lowercase and stripped of additional information. The 'location' column is cleaned by extracting the city name. The 'dish_liked' column is dropped, and missing values in 'restro_type' and 'approx_cost_for_two_people' are filled with the mode and mean, respectively.

4. **Data export:** The cleaned dataset is exported to a CSV file for further analysis and visualization in Tableau.

LINK : https://public.tableau.com/app/profile/pavan.ambare7481/viz/zomatoDataset/ZomatoRestaurantsAnalysis?publish=yes

![Image Alt text](/images/img.jpg

![Image Alt text](/images/img.jpg "Optional title"))
