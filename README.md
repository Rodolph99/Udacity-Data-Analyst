# [Udacity Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)

> Discover insights from data via Python and SQL.

## Skills Acquired (Summary)


### Prerequisites

You'll need to install:

* [Python (3.x or higher)](https://www.python.org/downloads/)
* [Jupyter Notebook](https://jupyter.org/)
* [Numpy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)

And additional libraries defined in each project.

Recommended:

* [Anaconda](https://www.anaconda.com/distribution/#download-section)

## Project Overview

### P1: Investigate a dataset

This analysis looks at data from two sources. The first is the [FBI's National Instant Criminal Background Check System (NICS)](https://www.fbi.gov/file-repository/nics_firearm_checks_-_month_year_by_state_type.pdf/view). Whenever an individual wants to undergo a transaction involving firearms or explosives, Federal Firearms Licensees (FFLs) have to input a background check into the system in order to make sure that the individual is eligible to complete the transaction. The data not only includes gun sales, but also other transactions such as concealed carry permits, rentals, private sales, and so on.

The other data comes from the US census and provides statistics by state for a variety of metrics. Most of this data is from the time period between 2010 and 2016.

In this analysis, I combine these two data sources to look at the relationship between gun background checks and demographic data. First, I plot the overall trend of background checks and gun sales over the time period represented by the data. Additionally, I zoom in specifically on handgun, long gun, and multiple-gun sales to see if the frequency of these particular transactions have changed over time. Next, I show which states have the most total background checks, as well as which states are growing the fastest in this area. Finally, I examine the general demographic profile of states with higher background checks. In particular, I focus on race, veteran status, immigrant status, education, income, and population density.

Here are the questions I answer in this analysis:
- What is the overall trend of background checks and gun sales?
- What is the overall trend of background checks split by gun category?
- Which states have had the largest overall and largest growth in background checks per capita?
- What demographic data correlates with background checks per capita by state?

Project 2 - Data Wrangling

The data wrangling stage of the data analysis process was thoroughly covered in this chapter. We gained knowledge of terms like "messy data" and "dirty data," as well as the assessment, definition, cleaning, and testing processes. Additionally, we covered a wide range of file types and data collection techniques.
In this project, we had to deal with the messy and soiled data reality (again). We gathered information from various sources (such as the Twitter API) and noted problems with the dataset's organization and quality. We then had to work out these issues while meticulously documenting each step. The examination of the data was then the project's final goal.

![Mean of retweets](https://github.com/DataLind/Udacity-Data-Analyst-Nanodegree/blob/master/mean_of_retweets_per_month-year_combination.png)

Project 3 - ProsperLoan Data Exploration

The 113,937 loans in this data set have an average of 81 variables, such as loan amount, borrower rate (or interest rate), current loan status, borrower income, and many more. The variables in the data set are described in this data dictionary. All of the dataset's variables are not anticipated to be explored as part of the project goal! However, narrow your attention to exploring only 10 to 15 of them.
