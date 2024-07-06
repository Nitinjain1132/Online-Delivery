# Online-Delivery

Restaurant Data Analysis
This project is a Tkinter-based application for analyzing restaurant data from a CSV file. It provides insights into the most common cuisines, the city with the highest number of restaurants, the city with the highest average rating, the distribution of price ranges among restaurants, and online delivery analysis. The results are displayed both in text format and through graphical visualizations using Matplotlib and Seaborn.

Features
Top Cuisines: Displays the top three most common cuisines along with the percentage of restaurants that serve each cuisine.
City with Most Restaurants: Identifies the city with the highest number of restaurants.
City with Highest Average Rating: Identifies the city with the highest average rating for restaurants.
Distribution of Price Ranges: Displays the percentage of restaurants in each price range category.
Online Delivery Analysis: Shows the percentage of restaurants that offer online delivery and compares the average ratings of restaurants with and without online delivery.
Graphical Visualizations: Provides bar charts for the top cuisines and their percentages, average ratings for the top 10 cities by number of restaurants, distribution of price ranges among restaurants, and online delivery analysis.
Prerequisites
Python 3.x
pandas
tkinter
matplotlib
seaborn
Installation
Clone the repository:
bash
cd restaurant-data-analysis
Install the required libraries:
bash
Copy code
pip install pandas tkinter matplotlib seaborn
Usage
Make sure your dataset CSV file is properly formatted and placed in the correct directory. Update the file path in the script if necessary.
Run the script:
bash
Copy code
python main.py
Code Overview
Data Loading
The dataset is loaded using pandas.read_csv and processed to extract relevant information such as the top cuisines, the city with the most restaurants, average ratings by city, the distribution of price ranges, and online delivery analysis.

Tkinter Interface
A Tkinter window is created to display the results. The interface includes buttons to open separate windows for each type of analysis.

Matplotlib and Seaborn Visualizations
Four bar charts are generated using Matplotlib and Seaborn:

One for the top three cuisines and their percentages.
Another for the average ratings of the top 10 cities by the number of restaurants.
Another for the distribution of price ranges among restaurants.
Another for the average ratings of restaurants with and without online delivery.
Dataset
Ensure that your dataset CSV file contains at least the following columns:

Cuisines: A string of cuisines separated by commas.
City: The city where the restaurant is located.
Aggregate rating: The average rating of the restaurant.
Price range: The price range category of the restaurant.
