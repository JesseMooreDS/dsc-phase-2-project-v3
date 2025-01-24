# Movie Profits Analysis Project

# Overview

Our clients are looking to enter the movie industry and aim to maximize their profits. This project analyzes historical data to uncover key insights that can guide their investment and production decisions.

# Business Understanding

# Problem Statement

Our clients seek to make informed decisions when entering the movie industry by understanding the critical factors that influence a movie's financial success. Identifying these factors will help them allocate resources effectively and optimize their strategies for profitability.

# Business Objective

The goal of this analysis is to examine relevant datasets to identify key patterns and characteristics—such as genre, production budget, release timing, and cast—that have the greatest impact on movie profitability. These insights will empower our clients to make data-driven decisions and maximize their return on investment.

# Stakeholder Questions

* Which movie genres yield the highest profits?

* What are the most profitable months for releasing a movie?

* How significant is the production budget in determining return on investment?

# Data Understanding and Analysis

# Data Sources

The datasets used in this analysis were sourced from reputable industry platforms, including:

* Box Office Mojo

* IMDb

* Rotten Tomatoes

* TheMovieDB

* The Numbers

# Data Description

The collected data includes information on thousands of movies, covering key aspects such as production budgets, global and domestic revenues (USA), genres, and release dates. This comprehensive dataset allows for in-depth analysis of profitability trends across different movie attributes.

# Data Analysis

# Genre Analysis

The data was aggregated and analyzed to determine which movie genres provide the highest average profits. Our findings indicate that the science fiction genre consistently generates the most profits. Further trend analysis suggests that the profitability of science fiction movies continues to rise.
![Movie Profits by Genre](https://github.com/JesseMooreDS/dsc-phase-2-project-v3/blob/main/Mean_Total_Profit_By_Year.png?raw=true)

# Budget vs. Profit Analysis

An in-depth analysis was conducted to evaluate the impact of production budgets on profitability. The results confirm a strong linear relationship between production budget and profits. This relationship is illustrated through a linear regression plot comparing average production budgets to average profits for science fiction movies, alongside a scatter plot depicting actual production budgets versus realized profits.

![Total_Profit_for_Production_Budget](https://github.com/JesseMooreDS/dsc-phase-2-project-v3/blob/main/Total_Profit_for_Production_Budget.png?raw=true)



# Seasonal Release Analysis

To determine the most profitable time to release a movie, the data was grouped by month. Although the differences are marginal, June emerged as the most profitable month, narrowly outperforming November in terms of average profits.

![Average_Total_Profit_by_Movie_Release_Month](https://github.com/JesseMooreDS/dsc-phase-2-project-v3/blob/main/Average_Total_Profit_by_Movie_Release_Month.png?raw=true)



# Conclusion

Based on our analysis, we have drawn the following key insights:

* Best Release Months: June and November are the most profitable months for movie releases.

* Top-Grossing Genre: Science fiction movies yield the highest average profits.

* Budget Impact: There is a strong linear relationship between production budgets and profits.

For further details, please refer to the following linked project notebook and presentation:
[project notebook](https://github.com/JesseMooreDS/dsc-phase-2-project-v3/blob/main/notebook.ipynb)
[presentation](https://github.com/JesseMooreDS/dsc-phase-2-project-v3/blob/main/presentation.pdf)
