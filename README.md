# Predicting-football-Players-Value-with-Regression
* Scraped all players data from www.transfermarkt.com with the help of python and selenium.
* Cleaned data by replacing missing values and deleting unrelated columns.  
* Prepared features to be used in the sklearn's model.
* Performed Exploratory Data Analysis with Seaborn to gain more insight about the data.
* Applied Linear Regression to predict players' values based on the dataset of the website.
* Classified data and predicted the movie ratings based on the written reviews.

# Resources Used
* Python Version: 3.7
* Packages: selenium, pandas, numpy, sklearn, matplotlib, seaborn.
* ChromeDriver 95.0.4638.10 [download](https://chromedriver.chromium.org/downloads).
# Web Scraping
* Used selenium to extract 500 football (soccer) player infromation.
# Data cleaning and Preparation
* Replaced incomplete and NAN data into a value of '0'.
* Transformed data into integers to be used later.
* Encoded players positions (categorical data) into numerical data.
* Dropped specific category (goalkeepers) because they have a complete differnt role in the pitch.
# Data visualization
* Computed the correlation of columns and visualized it with a heatmap, which showed that goals and assists as well as the time spent on field have the highest correlation with the player's market value. Also, I plotted regression plots of goals and assits made by players besides the histogram of time played by footballers as well as a box plot of the the different market values.

![image 1](https://github.com/YoussefAithaddou/Predicting-football-Players-Value-with-Regression/blob/main/Heatmap.png)
![image 2](https://github.com/YoussefAithaddou/Predicting-football-Players-Value-with-Regression/blob/main/Goal-Assist-Time-Value.png)
* The data extraction process gives the following results:
  1. Reviews: written critic of users.
  2. Stars: from 1 to 5 where 5 is the maximum possible value.

# Linear Regression Model
* Results:
  Using the Linear Regressiom model, I had the following results:
  ![image](https://github.com/YoussefAithaddou/Predicting-football-Players-Value-with-Regression/blob/main/regression_results.PNG).

