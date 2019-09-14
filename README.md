# Investigate Imdb Movies Dataset
This project has been completed as part of the [Udacity's Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) requirements.

## Overview
The imdb movies dataset has been analyzed and an exploratory analysis has been performed.

- First, a data screening has been performed and research questions have been identified.

- Secondly, the data have been cleaned and relevant variables to answer the research questions have been selected.

- Then, an exploratory data analysis (EDA) has been performed to identify correlations between variables and revenues and profits.

- Finally, detailed visulizations present the findings, and conclusions and limitations are discussed.

Research questions that have been explored:

1. Are the popularity, budget and vote count being correlated with revenues (adjusted)?
2. Which genres have the highest revenues each year and decade?
3. Which genres have the highest profits each decade?
4. Which are the most popular genres each year?
5. Which directors have the highest revenues?
6. Which directors have the highest and lowest profits?
7. Which directors have the highest budgets?
8. How the top directors with highest revenues are assossiated with the number of movies?

## Technologies used

- Python
- Libraries: Pandas, NumPy, MatPlotlib, Seaborn
- Jupyter Notebook

## Snapshot from the analysis
The following Figure shows revenues, profits, budget, number of movies and average revenues for the top 10 directors, as well as losses of the worst 10 directors.

<p align="center">
  <img src="https://github.com/gepallas/DAND_Project2_Investigate_Imdb_Movies_Dataset/blob/master/images/image1.png?raw=true" alt="Snapshot from the analysis"/>
</p>

Some insights:
- Steven Spielberg is by far the director with the highest total revenues and profits followed by James Cameron.
- The two plots of total revenues and profits per director are quite similar with small changes.
- When we look at the total budget plot, Steven Spielbeg is again on the top of the list. Ridley Scott is second on total budget. However, Ridley Scott is not on the top 10 list by total revenues and profits. A more detailed analysis can be performed to identify which specific movies had high budgets without bringing back expected revenues.
- By far the most productive director is Woody Allen, with more than 45 movies produced. He does not appear though in the plots of top 10 revenues and profits. That implies that the movies haven't had high revenues. However, he also does not appear in the list of the highest budgets. That also implies that many of his movies were low budget compared to other directors.
- If we look at the average revenues of top directors with more or equal than 10 movies (excluding those that might had a very big success with a few movies only resulting in high average), James Cameron is on the top of the list followed by Steven Spielberg.

### *Additional metrics*

The metric profit was not in the initial dataset. I developed this metric to show the assossiation between revenues and budgets.
Additional metrics or scores would be nice to be explored. For instance, if we divide the revenues with the budget it might also be a useful metric to quantify the success of a movie. We can then further analyze the success of each movie per director or develop an overall score for each director.

Additional metrics, as well as analyzing more variables in the dataset can provide new insights that can be used to predict the success of future movies.

