# ada-2020-project-milestone-p3-p3_adam-et-eva
ada-2020-project-milestone-p3-p3_adam-et-eva created by GitHub Classroom

# Title: Life satisfaction and housing conditions in London

## Abstract:
Cattaneo and al., in their paper Housing, Health and Happiness, discuss the influence of housing on health and welfare by studying the impact of a large-scale household Mexican government program, Piso Firme. In particular, they found that housing upgrades significantly improve adult welfare, as measured by increased satisfaction with their housing and quality of life, as well as lower depression and perceived stress.This raises an interesting point: how does their findings generalize to other cities? Is it possible to establish links between housing and life satisfaction in a big European city? We decided to extend their work by looking at data sets on housing in London. We aim at establishing the influence of numerous housing variables, such as prices, neighbourhoods (and conditions) on life satisfaction and happiness. We will further extend our research on whether political opinion is defined by housing and neighbourhood conditions.

## Research Questions: 
#### Q1: 
Does location define life satisfaction or is it defined by standard of living (job, house price)?
#### Q2: 
Can we group neighborhoods by looking at well being, security and economic stability? 
#### Q3: 
Can we predict political control based on life satisfaction and housing conditions ? 

## Proposed datasets:
- https://www.kaggle.com/justinas/housing-in-london?select=housing_in_london_monthly_variables.csv 
- https://www.kaggle.com/justinas/housing-in-london?select=housing_in_london_yearly_variables.csv
- https://www.kaggle.com/marshald/london-boroughs 

#### Names of the datasets:
- 1st dataset “housing_in_london_monthly_variables.csv”
- 2nd dataset “housing_in_london_yearly_variables.csv”
- 3rd dataset “london-borough-profiles-2016_Data_Set.csv”

#### Access the data and description:
To get all three datasets, we just have to download the .csv files from the three links above. csv files reading is very adapted to python and its libraries.
The first two datasets contain at least 20 years of data (1995-2020 and 1999-2019). This gives us a very wide range of information and allows us to reliably use any calculation on the data. 
The third dataset gives us additional information on the London Boroughs and their demographics including crime statistics, life satisfaction, political aspects, and happiness score for example. For the third dataset, the data was collected in 2016, with variables ranging from 2011 to 2015.
The datasets are relatively clean, with simple value definitions.

#### Number of variables per dataset:
- 1st dataset: 7 variables
- 2nd dataset: 12 variables
- 3rd dataset: 85 variables

#### Data exploration, cleaning and processing:
Data exploratory analysis would be used to find any irregularities or missing values, and investigation of the proportion of missing values, and of the mean/median of the variables would help us decide how to treat missing values. Some data processing would thus have to be done based on the data exploration results. For example, we will have to do some data processing for the dates in the first two datasets, to express them in timestamp format; missing values in area code in the third data set also require some processing, as well as missing values in any other features. Furthermore, potential merging of data from different datasets will require data selection based on existing boroughs and years in the different datasets.
These three datasets will mutually enrich each other, as they offer a very large overview of many variables on London neighbourhoods, allowing to obtain a rather complete set of information to evaluate the influence of housing conditions on life satisfaction.  We are able to consider multiple housing conditions (boroughs, house prices, population density, greenspace, number of jobs, ...) to discuss satisfaction indices (life satisfaction, anxiety, happiness, …)

## Methods:
#### Q1: 
Perform regressions and see which variables give us more significant results: enter as independent/control variables location, life satisfaction, etc., and check for the level of significance for the different variables.
#### Q2: 
Use clustering methods guided by a calculation of neighborhood’s life satisfaction means. We look at the difference in means of mean salary, life satisfaction and housing prices and crime rates, to then guide PCA and clustering (using k-means).
#### Q3: 
Done by looking at the third dataset, and performing a classification with logistic regression. The idea is to develop a model to predict the party in political control by neighbourhoods, depending on all the standard of living criteria (life satisfaction score, happiness score, anxiety score, worthwhileness score, percentage of area that is green space…); the significance levels of the control variables will be assessed to discuss whether political views are significantly affected by life conditions (housing, happiness).

## Proposed timeline:
We make one milestone per week (every Friday). Each milestone will be updated based on the previous ones, and each week will be concluded by a zoom meeting with all team members.
The individual part of P4 (Part B) is managed individually by each group member and is thus not included in the intermediate milestones.

#### P4a
- Week 1: Question 1 + Question 2 + Data visualisation
- Friday, Dec. 4th - P4a: Code for questions 1 & 2 & Data Visualization done

#### P4b
- Week 2: Redaction of Question 1 and 2 + Question 3
- Friday, Dec. 11th - P4b: Code for question 3 done + Questions 1 & 2 & Data Visualization part written in the report (+ code comments in notebook)

#### P4c
- Week 3: Report + Write Pitch (film later) + Redaction Question 3
- Friday, Dec. 18th - P4c: Redaction in the report & code comments in notebook for Question 3 + Abstract, introduction, data collection & conclusion parts of the report done + Pitch text done

## Organization within the team:
#### P4a
- Valentine Perrin: Question 2
- Elodie Raes: Data Visualisation
- Ariane de Marcillac: Question 1

#### P4b
- Valentine Perrin: Redaction Q2 + Report
- Elodie Raes: Question 3
- Ariane de Marcillac: Redaction Q1 + Report

#### P4c
- Valentine Perrin: Finalisation + Pitch redaction
- Elodie Raes: Redaction Q3
- Ariane de Marcillac: Finalisation + Pitch redaction

Note: Redaction Q* means: Writing the ‘methods’ part used in the question, write the results
