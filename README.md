[ Practiced different approaches and systems in project02.ipynb ]

# Statistical Analysis on a Global Food Dataset

This project performs a comprehensive statistical analysis on a dataset of various food items from around the world. The primary goal is to uncover patterns, distributions, and relationships within the data through descriptive statistics, data visualization, and hypothesis testing.

## Dataset

The analysis is based on the `cleaned_food_data.csv` file. This dataset contains information about various food items, including the following key columns used in this notebook:

-   `Country/Region`
    
-   `Calories`
    
-   `Preparation Time`
    
-   `Category`
    
-   `Popularity Rank`
    

## Analysis Performed

The Jupyter Notebook (`Satistical_Analysis_on_Dataset.ipynb`) conducts the following analyses:

### 1. Descriptive Statistics

-   **Frequency Count:** Calculation of the number of unique food items from each country/region to understand the geographical distribution of the data.
    
-   **Grouped Analysis:** Calculation of the average calories and preparation time for food items, grouped by their country of origin.
    

### 2. Cross-Tabulation

-   A contingency table was created to analyze the distribution of different food categories (e.g., Dessert, Main Course, Snack) across various countries.
    

### 3. Data Visualization

Several plots were generated to visually represent the findings:

-   **Bar Chart:** Food item counts by country.
    
-   **Bar Charts:** Average calories and average preparation time by country.
    
-   **Stacked Bar Chart:** Distribution of food categories within each country.
    
-   **Scatter Plot:** Relationship between the number of calories and the popularity rank of food items, including a regression line to visualize the trend.
    
-   **Histogram:** Distribution of calories across all food items to observe its central tendency and spread.
    

### 4. Hypothesis Testing

-   A one-sample Z-test was conducted for each country's food items to test the null hypothesis (H_0) that the mean preparation time is 30 minutes.
    
    -   **Null Hypothesis (H_0):** mu=30 minutes.
        
    -   **Alternative Hypothesis (H_a):** muneq30 minutes.
        
    -   A significance level (alpha) of 0.05 was used.
        

## Key Findings

-   **Geographical Distribution:** India, Japan, and the United States are the most represented countries in the dataset.
    
-   **Nutritional Insights:** Foods from Singapore and the United Kingdom have the highest average calories.
    
-   **Preparation Time:** Foods from Morocco and Korea have notably long average preparation times compared to other countries.
    
-   **Hypothesis Test Result:** The Z-test showed that for most countries, there is not enough statistical evidence to reject the claim that the average preparation time is 30 minutes.
    
    -   A significant exception is **Korea**, where the null hypothesis was rejected. The average preparation time for Korean foods in the dataset (325 minutes) is statistically different from 30 minutes.
        

## Technologies Used

-   **Python**
    
-   **Pandas:** For data manipulation and analysis.
    
-   **NumPy:** For numerical operations.
    
-   **Matplotlib & Seaborn:** For data visualization.
    

Open the Satistical_Analysis_on_Dataset.ipynb file and run the cells sequentially to see the analysis and visualizations.
