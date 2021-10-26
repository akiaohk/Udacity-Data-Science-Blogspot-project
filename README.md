
# Data Science Blogpost project
You can read my Medium Blog Post in [Udacity Data Science Project](https://medium.com/@akikhoa/udacity-data-science-project-860d1741ec01).

## Libraries
To be able to run this notebook, you need to install these libraries:
* numpy
* pandas
* matplotlib
* seaborn

## Business Understanding
With the emerging technology in Germany such as AI and Data Science, many programming languages that were poorly spoken and used are now experiencing a rise in popularity.

In this article, we are going to analyze real data to verify if these programming languages are really being used in Germany or if they are just rumors.

**The motivation behind the project** is to get a better understanding of Top programming Languages in Germany, as well as study them as a total.
1.	 *What are most used programming language in Germany?*
2.	 *What are most wanted programming language in in Germany?*
3.	 *Which occupations were most popular in each year?*

## Data Understanding
For this, we are going to use data from Stackoverflow’s 2017 and 2018 Annual Developer Survey [(by Stackoverflow)](https://insights.stackoverflow.com/survey).

The rows are the different respondants to the survey, and the columns are the answer to the survey questions. It contains data that comes as numerical, categorical and text. It has missing values and outliers as well.

## Prepare Data

For the data preparation phase, we gathered the data, assessed it and then proceeded to clean it, focusing on our columns of interest, with python libraries of numpy and pandas.

## Data Modeling

We graphed different behaviours that were relevant to the 3 questions, with the python libraries matplotlib and seaborn.

## Evaluate the Results

After I did the analysis, these are the conclusion I found:
1. We can see that classic languages like: Java Script, SQL, Java are still in the top positions.
2. Javascript, Python, Java and SQL are in top list of wanted languages.
3. Web developer, Desktop applications developer, Mobile developer is the most popular occupation among participants in 2017.
   Back-end developer, Full-stack web developer, Front end developer is the most popular occupation among participants after 2018.

## Files in repository
* **DataScience_blogpost.ipynb**: 
Notebook containing the data analysis.
  * data/2017/survey_results_public.csv: Stackoverflow's 2017 Annual Developer Survey data.
  * data/2018/survey_results_public.csv: Stackoverflow's 2018 Annual Developer Survey data.
*	**README.md**: 
file for write-up

## Acknowledgements
1. Udacity
2. Stackoverflow
