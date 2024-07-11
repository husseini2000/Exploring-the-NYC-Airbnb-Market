# New York City Airbnb Analysis - Exploratory Data Analysis (EDA)

## Overview

This project provides a comprehensive exploratory data analysis (EDA) of Airbnb listings in New York City. Using datasets from Kaggle, we aim to uncover insights and trends in the Airbnb market across the five NYC boroughs: Manhattan, Brooklyn, Queens, Bronx, and Staten Island. 

## Key Questions

1. What is the average price per night for an Airbnb listing in NYC?
2. How do Airbnb listing prices compare across the five NYC boroughs?
3. What is the distribution of room types among the listings?
4. How do listings fall into different price ranges across the boroughs?

## Datasets

We utilized three datasets from Kaggle for this analysis:

1. **airbnb_last_review.csv**: Contains the last review date for each listing.
2. **airbnb_price.csv**: Contains price information for each listing.
3. **airbnb_room_type.xlsx**: Contains room type information for each listing.

## Steps and Methodology

### 1. Data Loading and Initial Inspection
- Imported the necessary libraries and loaded the datasets.
- Displayed the first few rows of each dataset side by side for a quick overview.

### 2. Data Cleaning and Preprocessing
- Handled missing values by dropping rows with essential missing data.
- Converted columns to appropriate data types (e.g., `last_review` to datetime).
- Merged datasets on common keys (`listing_id`) to create a unified dataset.

### 3. Exploratory Data Analysis (EDA)
- Visualized the distribution of Airbnb prices using histograms and KDE plots.
- Analyzed the count of different room types through bar plots.

### 4. Borough-Level Analysis
- Grouped data by boroughs to calculate average prices and other statistics.
- Visualized the average prices across boroughs using bar plots.

### 5. Price Range Analysis
- Categorized listings into price ranges: Budget, Average, Expensive, and Extravagant.
- Analyzed and visualized the distribution of these price ranges across boroughs.

## Key Findings

- **Average Price Insights**: The average price per night varies significantly across different boroughs, with Manhattan having the highest average prices.
- **Borough Comparison**: Brooklyn and Manhattan dominate in terms of the number and price of listings, while Queens, Bronx, and Staten Island offer more budget-friendly options.
- **Room Type Distribution**: Entire homes/apartments make up the majority of listings, followed by private rooms.
- **Price Range Distribution**: Manhattan boasts a higher concentration of high-priced listings, whereas other boroughs have a larger share of budget and average-priced listings.

## Conclusion

This analysis provides valuable insights into the NYC Airbnb market, highlighting significant differences in prices and types of listings across boroughs. Future work could explore seasonal trends and the impact of external factors on Airbnb pricing.

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/husseini2000/Exploring-the-NYC-Airbnb-Market.git
    ```

2. Navigate to the project directory:
    ```bash
    cd husseini2000/Exploring-the-NYC-Airbnb-Market.git
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter Notebook:
    ```bash
    jupyter notebook NYC_Airbnb_Analysis_EDA.ipynb
    ```

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- jupyter
- datetime

## Acknowledgments

This project utilizes datasets from Kaggle. Special thanks to Kaggle for providing the data.

## Contact

Feel free to reach out if you have any questions or suggestions!

- **LinkedIn**: [Al-Husseini Abdelaleem](https://www.linkedin.com/in/al-husseiniabdelaleem)
- **GitHub**: [husseini2000](https://github.com/husseini2000)

