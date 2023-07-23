# Tech-Jobs-Analysis
This repository contains Python code used to analyze salary data from levels.fyi.  I wrote the code during my completion of the CareerFoundry Data Analytics course.
## Background Information
As an aspiring data analyst who will soon be looking for a job, I decided to do some research on the job market for data and tech fields.  The primary focus of my analysis centered around salary and how it is affected by experience in the field, an employee's time at their current company, education level, and job location.  The analysis was done in Python and includes machine learning techniques (regression and k-means clustering) as part of an exploratory analysis.  I created a Tableau storyboard to summarize my findings.  
## Data 
* Source: I accessed this data on Kaggle.  It was scraped from [levels.fyi](levels.fyi) by Jack Ogozaly using the technique outlined in [this article](https://towardsdatascience.com/a-beginners-guide-to-grabbing-and-analyzing-salary-data-in-python-e8c60eab186e).  These data were scraped in 2021.
* Data Collection: The data collection here is similar to that of the Analyst Salaries dataset.  levels.fyi is a job posting and searching platform that allows users to anonymously submit information about their salary, experience level, job title, etc.  The data is not directly available for download, and thus, was scraped from the website.
* Data Contents: This dataset contains information about the salaries of individuals who work in tech and data fields.  These data were collected between 2017 and 2021.  There are over 62,000 rows, each representing an individual.  The columns include information on salary, company, experience level, years at company, job location, education, gender, and race.  For more information, see the data profile in this document.
* Shape files: For the geospatial component of this analysis, I sourced JSON files from datahub.io, [here](https://datahub.io/core/geo-countries)
## Tools
This project required the use of Python and Tableau.  The following libraries were used in Python:
* pandas
* numpy
* seaborn
* matplotlib
* scipy
* quandl
* statsmodels.api
* sklearn
* pylab
I used Jupyter to write my python code.  You may access the Jupyter notebooks in the [Scripts]() folder.
## Deliverables
For a summary of the final results of my analysis, see this [Tableau storyboard](https://public.tableau.com/views/TechJobs/TechJobsAnexploratoryanalysisofthesalariesofvariousjobsindataandtechnology?:language=en-US&:display_count=n&:origin=viz_share_link)
