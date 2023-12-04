# Project Presentation: Hotel Data Analysis and Rating Prediction

## Overview

This project involves the comprehensive analysis of hotel data collected from booking.com, spanning various cities worldwide. The project is divided into four key parts: data crawling, data cleaning and formatting, exploratory data analysis (EDA) visualization, and machine learning (ML) model implementation.

## Part 1 - Data Crawling from Booking

We utilized BeautifulSoup to scrape hotel information from booking.com, extracting details such as hotel name, location, rating, and price. Data was collected from 10 different cities globally, and the results were stored in CSV files.

## Part 2 - Cleaning and Formatting the Data

This stage involved essential data cleaning tasks, including handling duplicates, managing missing values, converting data types, and standardizing units. Additional features, such as price per night and distance from the city center, were created. The cleaned data sets serve as the foundation for subsequent analysis.

## Part 3 - EDA Visualization

Exploratory Data Analysis (EDA) was conducted to gain insights into the collected data. Visualization techniques such as histograms, boxplots, scatterplots, and heatmaps were employed. The analysis focused on the distribution of hotel ratings and prices across different cities and regions. Relationships between hotel features and customer satisfaction were also explored.

## Part 4 - ML Machine Learning Model

Two machine learning models, DecisionTreeClassifier and KNN, were applied to predict hotel ratings based on various features. Performance evaluation was conducted using accuracy metrics. Cross-validation and hyperparameter tuning were implemented to optimize the models.

## Requirements
- Python 3.x
- Jupyter Notebooks
- Libraries: BeautifulSoup, pandas, matplotlib, seaborn, scikit-learn

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/omertzroya/Data-science-CrawlingBooking-Python-Project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd //Your current path
   ```

3. Run the Jupyter notebooks in the `/notebooks` directory in sequential order.


## Technology Used
<div>
<img src='https://img.shields.io/badge/Python-3.9.7-blue?style=for-the-badge&logo=python&logoColor=white' alt='Python'/>
<img src='https://img.shields.io/badge/BeautifulSoup-4.9.0-green?style=for-the-badge&logo=beautifulsoup&logoColor=white' alt='BeautifulSoup'/>
<img src='https://img.shields.io/badge/pandas-1.3.3-blue?style=for-the-badge&logo=pandas&logoColor=white' alt='Pandas'/>
<img src='https://img.shields.io/badge/Matplotlib-3.4.3-red?style=for-the-badge&logo=matplotlib&logoColor=white' alt='Matplotlib'/>
<img src='https://img.shields.io/badge/Seaborn-0.11.2-orange?style=for-the-badge&logo=seaborn&logoColor=white' alt='Seaborn'/>
<img src='https://img.shields.io/badge/scikit--learn-0.24.2-yellow?style=for-the-badge&logo=scikit-learn&logoColor=white' alt='scikit-learn'/>
</div>

## Contributing

Feel free to contribute to the project by opening issues or creating pull requests. 

## License

![GitHub](https://img.shields.io/github/license/ItsAlexanderPopov/Simon-game)
