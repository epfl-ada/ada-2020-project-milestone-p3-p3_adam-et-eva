# ada-2020-project-milestone-p3-p3_adam-et-eva
ada-2020-project-milestone-p3-p3_adam-et-eva created by GitHub Classroom

# Title: Happiness and housing conditions in London

## Data story:

https://vaperrin98.github.io 

## Abstract:
Cattaneo and al., in their paper Housing, Health and Happiness, discuss the influence of housing on health and welfare by studying the impact of a large-scale household Mexican government program, Piso Firme. In particular, they found that housing upgrades significantly improve adult welfare, as measured by increased satisfaction with their housing and quality of life, as well as lower depression and perceived stress.This raises an interesting point: how does their findings generalize to other cities? Is it possible to establish links between housing and life satisfaction in a big European city? We decided to extend their work by looking at data sets on housing in London. We aim at establishing the influence of numerous housing variables, such as prices, neighbourhoods (and conditions) on life satisfaction and happiness. We will further extend our research by examining whether political opinion is defined by housing and neighbourhood conditions.

## Research Questions: 
#### Q1: 
Does location define life satisfaction or is it defined by standard of living (job, house price)?
#### Q2: 
Can we group neighborhoods by looking at well being, security and economic stability? 
#### Q3: 
Do differences in political control translates in well-being and housing conditions? 

#### Dataset:
“london-borough-profiles-2016_Data_Set.csv”
- https://www.kaggle.com/marshald/london-boroughs 
- 85 variables

#### Access the data and description:
To get the dataset, we just downloaded the .csv file from the link above as .csv files reading is very adapted to python and its libraries.
Our dataset gives us valuable information on the London Boroughs and their demographics including crime statistics, life satisfaction, political aspects, and happiness score for example. The data was collected in 2016, with variables ranging from 2011 to 2015.
The dataset is relatively clean, with simple value definitions.

#### Data exploration, cleaning and processing:
Data exploratory analysis was used to find any irregularities or missing values, investigate the proportion of missing values, and of the mean/median of the variables would help us decide how to treat missing values. Some data processing was thus done based on the data exploration results. Missing values in area code in the data set required some processing, as well as missing values in any other features. Furthermore, careful considerations about the variable types were necessary.

The dataset offers a very large overview of many variables on London neighbourhoods, allowing to obtain a rather complete set of information to evaluate the influence of housing conditions on life satisfaction.  We are able to consider multiple housing conditions (boroughs, house prices, population density, greenspace, number of jobs, ...) to discuss satisfaction indices (life satisfaction, anxiety, happiness, …)

## Methods:
#### Q1: 
Perform regressions and see which variables give us more significant results: enter as independent/control variables location, life satisfaction, etc., and check for the level of significance for the different variables.

#### Q2: 
Use clustering methods guided by a calculation of neighborhood’s life satisfaction means. We look at the difference in means of mean salary, life satisfaction and housing prices and crime rates, to then guide PCA and clustering (using k-means).

#### Q3: 
Perform statistical t-tests to look for significant differences between labour-controlled and conservative-controlled boroughs. The statistical tests are preceded by mean difference calculations and some distribution plotting.

## Timeline:
We made one milestone per week (every Friday). Each milestone was updated based on the previous ones, and each week was concluded by a zoom meeting with all team members.
The individual part of P4 (Part B) is managed individually by each group member and is thus not included in the intermediate milestones.

#### P4a
- Week 1: Question 1 + Question 2 + Data visualisation
- Friday, Dec. 4th - P4a: Code for questions 1 & 2 & Data Visualization done

#### P4b
- Week 2: Redaction of Question 1 and 2 + Question 3
- Friday, Dec. 11th - P4b: Code for question 3 done + Questions 1 & 2 & Data Visualization part written in the report (+ code comments in notebook)

#### P4c
- Week 3: Report + Write and Film Pitch + Redaction Question 3
- Friday, Dec. 18th - P4c: Redaction in the report & code comments in notebook for Question 3 + Abstract, introduction, data collection & conclusion parts of the report done + Pitch text done

## Organization plan within the team:
### Week 1
- Valentine Perrin: Question 2 and Question 3
- Elodie Raes: Data Visualisation
- Ariane de Marcillac: Question 1

### Week 2
- Valentine Perrin: Redaction of report for Questions 2 and 3 
- Ariane de Marcillac: Redaction of report Question 1 + Data visualisation

### Week 3
- Valentine Perrin: Finalisation + Data visualisation + Creation of Jekyll support for the data Story
- Elodie Raes: Data visualisation
- Ariane de Marcillac: Finalisation + Pitch redaction + Pitch filming + Conclusion

Note: Redaction Q* means: Writing the ‘methods’ part used in the question, write the results
