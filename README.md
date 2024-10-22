# Top 5 League footballers price prediction

This project involves scraping footballer performance metrics from fbref.com and market value data from transfermarkt.com. The goal is to preprocess the data, visualize key trends, and build a machine learning model to predict player market values with improved accuracy using hyperparameter tuning and regularization.

## About The Project

In this project, I scraped data from two sources:
- **fbref.com**: Performance metrics for footballers.
- **transfermarkt.com**: Market value information.

The objective is to clean and preprocess the scraped data, visualize performance metrics, and develop a machine learning model to predict the market value of players based on their performance.

### Main Steps Involved:

- **Data Scraping**: Scraped footballer performance data from fbref.com and market value data from transfermarkt.com.
- **Data Preprocessing**: Cleaned and merged raw datasets using Pandas and handled missing or inconsistent values.
- **Data Visualization**: Used visualization techniques to explore relationships between performance metrics and market value.
- **Modeling**: Developed machine learning models with hyperparameter tuning and regularization techniques to improve predictive accuracy.
- **Evaluation**: Evaluated model performance using RMSE score.


## Data Visualization

Visualizations play an important role in understanding the relationship between footballer performance and their market value. Some key visualizations include:

- **Scatter Plots**: Used to explore relationships between key metrics (e.g., goals, assists, xG, nPxG) and market value.
- **Correlation Heatmaps**: To analyze the correlations between different performance metrics and their effect on market value.
- **Box Plots**: Used to understand the distribution of market value across different performance categories.
- **Histograms**: Used to visualize the distribution of market value across different leagues, showing how player market values differ between leagues.



### Future Improvements

- **Expanding Data**: Scraping data from additional seasons, leagues, and player positions.
- **Feature Engineering**: Incorporating new features, such as injuries, potential, mentality attribute.
- **Implementing Advanced Models**: Using models like XGBoost or neural networks for better accuracy.
