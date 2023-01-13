# GlassDoor-Data-Analysis Overview

The dataset I used for this data analysis project contains data on the top jobs from GlassDoor from the years 2015 to 2021. 
This includes each job's average salary, overall satisfaction rating, number of job openings, and (numerical) rank for the given year.
I obtained this dataset from [Kaggle](https://www.kaggle.com/datasets).

My purpose for writing this software that does an analysis of each year's top ranking jobs in order to provide insights on what fields are growing based on various factors like salary, voted satisfaction, and competitiveness (job openings)- which may potentially help students choose a career path considering the analytics. 

{Provide a link to your YouTube demonstration.  It should be a 4-5 minute demo of the data set, the questions and answers, the code running and a walkthrough of the code.}

[Software Demo Video](http://youtube.link.goes.here)

# Data Analysis Results

What was the top job based on average salary for a given year?

    2015: Finance Manager with a average salary of $122865.

    2016: Software Development Manager with a average salary of $135000.

    2017: Physician with a average salary of $200000.

    2018: Strategy Manager with a average salary of $135000.

    2019: Software Engineering Manager with a average salary of $153000.

    2020: Strategy Manager with a average salary of $133067.

    2021: Technical Program Manager with a average salary of $142379.

What was the top job based on satisfaction ratings for a given year?

    2015: Audit Manager with a satisfactory rating of 3.9.

    2016:  Data Scientist with a satisfactory rating of 4.1.

    2017: Data Scientist with a satisfactory rating of 4.4.

    2018: Compliance Manager with a satisfactory rating of 4.3.

    2019: Product Designer with a satisfactory rating of 4.5.

    2020: Corporate Recruiter with a satisfactory rating of 4.4.

    2021: Realtor with a satisfactory rating of 4.4.

What was the top job based on the number of job openings for a given year?

    2015: Software Engineer with a total of 104828 openings.

    2016: Software Engineer with a total of 49270 openings.

    2017: Physical Therapist with a total of 24579 openings.

    2018: Software Engineer with a total of 29187 openings.

    2019: Software Engineer with a total of 49007 openings.

    2020: Software Engineer with a total of 50438 openings.

    2021: Software Engineer with a total of 40564 openings.

What is the correlation between each category of the dataset?

    Based on the Pearson Correlation chart, we can see conclude that ranking and salary have the highest correlation with a correlation coefficient of -0.33, while satisfaction rating and ranking are the least correlated with a correlation coefficient of -0.021. 

# Development Environment

- Visual Studio Code

- Python 3.10.6

    - [numpy](https://pypi.org/project/numpy/)
    - [pandas](https://pypi.org/project/pandas/) 
    - [matplotlib/matplotlib.pyplot](https://pypi.org/project/matplotlib/)
    - [seaborn](https://pypi.org/project/seaborn/)
    - [logging](https://docs.python.org/3/library/logging.html)

# Useful Websites

* [Bar Plot in Matplotlib by GeeksForGeeks](https://www.geeksforgeeks.org/bar-plot-in-matplotlib/)
* [Visualizing Distributions of Data by Seaborn](https://seaborn.pydata.org/tutorial/distributions.html)
* [Add Logging to a Python Script](https://www.geeksforgeeks.org/python-add-logging-to-a-python-script/?ref=rp)

# Future Work

* View analytics for particular jobs
* Check trends of categories (or jobs) over the years
* Make predictions for upcoming years