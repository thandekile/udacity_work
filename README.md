Adult Job Cencus Analysis

Overview

This project aims to answer important questions regarding different types of jobs, experience and the factors that influence the income that an individual gets. The kinds of features that are used are: age, work class, education, number of year in education, marital status, occupation, relationship, race, sex capital gain, capital loss, hours of work per week, native country and income.

Blog post link
https://medium.com/@thande.tm/a-story-on-jobs-826f4e8623d3

Installation

To run the code, you need the Anaconda distribution of Python. The code is compatible with Python 3.x versions and you should be able to run it. You would need to install the following libraries using pip install:

pip install -r requirements.txt
The requirements.txt file includes:

pandas
numpy
scikit-learn
matplotlib
seaborn
Usage
To use this project, follow these steps:

Clone the repository to your local machine.
Install the required libraries as mentioned in the Installation section.
Open the Jupyter Notebook JobCencus.ipynb to explore the data analysis and visualizations.
Use the survey_results_public.csv and survey_results_schema.csv files for further analysis.

Project Motivation

The intention of this project was to answer three business questions I had, that being:
- What determines whether an individual earns more than 50K annually?
- Does the level of education have an impact on an individual's levels of income and how?
- What is the relationship between occupation and income levels?

These were examined given the aforementioned features
examine factors that influence individuals' income given the features that were mentioned. 


Key Findings
- What determines whether an individual earns more than 50K annually?
Features that influenced whether an individual earns more than 50K are: age, relationship (family structure - children, married, no children, etc.), capital gains, hours per week (working hours per week) and education num (number of years in education).
- Does the level of education have an impact on an individual's levels of income and how?
one can say that higher levels of education do likely yield higher levels of income. Those holding Doctorates had 74% of them earning 50K. A majority of individuals holding Masters degrees (55,7%) earn more than 50K; and those with Bachelor's degrees had 42% of them earning 50K.
- What is the relationship between occupation and income levels?
The more technical and managerial/leadership roles have a higher proportion of individuals who earn more than 50K. An exec-managerial roles is seen to have about 48% of the respondents earning morning 50K. When looking at the prof-specialty role, we find that individuals who earn more than 50K make up 45% of the respondents.


File Descriptions

JobCensus.ipynb: The Jupyter Notebook has data analysis, visualisations in code form using Python (in pandas)
README.txt: The file has information pertaining to the synopsis of the project, files, how to navigate the components in the project and other relevant piece of useful information.
adult_cencus.csv: The file contains respondent data regarding their demographics, occupation, income and other related data. You are not able to infer anyone's personal identity from the file.

Licensing, Authors, Acknowledgements
The data was sourced from Kaggle (Adult Census Income). The data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics).
