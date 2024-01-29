# Doordash-EDA
Exploratory Data Analysis for Doordash Data 

Exploratory Data Analysis (EDA) is a crucial step in understanding your dataset before diving into any machine learning or data modeling. It helps in uncovering the underlying patterns, spotting anomalies, understanding the relationship between variables, and summarizing the main characteristics of the dataset. Given your dataset columns, here are several possibilities for conducting EDA:

1. Descriptive Statistics
Summary Statistics: Obtain summary statistics (mean, median, mode, min, max, range, quartiles, variance, standard deviation) for numerical columns like distance, delivery_fee_raw, delivery_fee, service_fee_raw, service_fee, review_count, and review_rating.
Frequency Counts: For categorical data like searched_state, searched_city, searched_metro, city_slug, cuisines, get the count of observations for each category to understand the distribution of data.

3. Data Quality Assessment
Missing Values: Check for missing values in all columns to identify if any column requires imputation or special handling.
Unique Values: Assess the number of unique values in columns such as searched_zipcode, searched_address, loc_name, loc_number to understand the diversity in the data.
Anomalies/Outliers: Identify outliers in numerical columns using box plots or statistical techniques.

5. Correlation Analysis
Examine the correlation between numerical variables to understand any linear relationship between them. For example, you might want to see if there's a relationship between distance and delivery_fee or review_rating and review_count.

7. Geospatial Analysis
Given the presence of latitude and longitude data (searched_lat, searched_lng, latitude, longitude), perform geospatial analysis to visualize the locations on a map. This could help in identifying spatial patterns or clusters.
Calculate distances between searched_lat, searched_lng and latitude, longitude to validate the distance column or uncover new insights.

11. Visualization
Histograms/Boxplots: For numerical data to understand the distribution and spot outliers.
Bar Charts: For categorical data to visualize the frequency of each category.
Scatter Plots: To visualize relationships between two numerical variables.
Heatmaps: For correlation analysis or to visualize geospatial density if applicable.
