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
**1. Results **:  
  Using the Linear Regressiom model, the features that have the strongest impact on the market are Age, Position, Goals and Assists. I had the following results:
  
  ![image3](https://github.com/YoussefAithaddou/Predicting-football-Players-Value-with-Regression/blob/main/regression_results.PNG).
  ![image4](https://github.com/YoussefAithaddou/Predicting-football-Players-Value-with-Regression/blob/main/y_predicted%20vs%20y_test.png).
  
**2. Discussion:**  
The model coefficient are excepcted due to the fact that goal scorers and playmaker are sought after by small and big teams, and yong and prospective players are highly valuable due to the expectations they hold. However, R^2 score and Mean Squarred error do not reflect a prefect predcition of players' market value. 
This model can be improved to produce better results by taking into consideration more variables that affects the valuation of footballers such as the nationality, league, injuries, presence in marketing and social media (number of followers, interviews and shirts sold) and the most importantly the previous market value of the players and their current contract.

