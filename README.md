# Is Passion the Only Factor That Influences Job Satisfaction for Developers?
## Data Driven Approach Using Survey Data

This repository contains the results of a study conducted to better understand the job satisfaction of full-time developers aged 15 to 60. Please see the linked [Medium](https://medium.com/@dindisn/is-passion-the-only-factor-that-influences-job-satisfaction-for-developers-28927944841e) article for more information on the findings.

## Data
The data used is the [Annual Developer Survey](https://insights.stackoverflow.com/survey) collected by Stackoverflow for the year 2020 . It contains responses of nearly 65K participants from over 150 countries. According to Stack overflow, the survey was conducted in February 2020, before COVID-19 was declared a pandemic by the World Health Organisation.
The data was filtered for the below at the analysis.
- Full-time personnel who are Developers by profession
- Aged between 15 and 60 years
- Who has responded to the survey question about whether or not they are content with their employment.
 

## Pre-requisites
The project was developed using python 3.7.6 with the following packages.
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Counter from collections

## Files
- EDA- Stack overflow 2020 Developers survey.ipynb : Jupyter Notebook with all the exploratory analysis and findings
- requirements.txt : pre-requisite libraries

## Key Questions analysed
1. Is it true that persons who code as a hobby have higher levels of job satisfaction than those who do not?
2. Is the percentage of satisfied and unsatisfied respondents similar across countries?
3. Does your age or gender have an effect on the distribution of job satisfaction rates?
4. Is there a link between working hours and job satisfaction?
5. What are the key factors which people look for in a job?


## Summary
The analysis is a basic EDA to understand what the dataset portrays. In order to get conclusions, statistical analysis should be carried out, and algorithmic approaches could be employed to portray higher level interactions between variables.

## Acknowledgments

[Stack Overflow](https://stackoverflow.com), for collecting and providing the data.
