# Tentative Research on the Causes of the Declining Birthrate
Authors: Jingjing Lin, Ruiwen Zhang, Yeqing Liu

Check the original work repository at [here](https://github.com/JJJJJingL/ANLY503) 
Changes in this version: 1. Fixed the mistakes in Gender equality data in python 
                         2. Updated the slides and tableau visualization  
                         
-------------                
      The descirpition is imported from the original work 
--------------

# Objectives
This research aims to discuss the causes of the declining birthrate phenomenon from the economic background (E), the rise of Gender Equality: feminism (F) and the healthcare (H) , then conduct 3 case studies of China, USA and India, to see how those factors influence the birthrate in the real world. 

# Requirements

- [x] All the development file(s)
- [x] Code
- [x] Data used for analysis (raw data and wrangled data)
- [x] Data visualization(s)
- [x] Clear screenshots of your visualization(s)
- [x] Your slides and any other presentation material

# Datasets 
### 3. Data used for analysis (raw data)
There are 7 datasets used in this project (Birth Rate data is the same datastes for each topic)
- For datasets in Economic:
  - inflation_data.csv, Inflation worldwide
  - gdp_data.csv, GDP worldwide
  - Econ_birthrate_data.csv, Birth Rate
- For datasets in Gender Equality:
  - SecondaryEnrol.xls, School enrollment, secondary, female (% gross)
  - birthrate.xls, Birth Rate
  - WageGenderGap.xls, Wage and salaried workers, female (% of female employment) (modeled ILO estimate)
- For datasets in Healthcare:
  - Healthcare_birthrate.csv, Birth Rate
  - health_MR.csv,Mortality Rate of Infant The lower mortality rate of infant, the better healthcare a country has 
  - health_CP.csv, Contraceptive Prevalence The high rate of contraception means that a country has a better healthcare
- For global:
  - global time series birth rate.xlsx
  - 2017 global birth rate.xlsx
  
# Code Instruction 
### 1. All the development file(s), 2. Code
There are three jupyter notebooks,including scripts for data preprocessing, analysis and visualizations in each field respectively.
- economy analysis.ipynb’ , for economy vs birth rate analysis
- healthcare analysis.ipynb‘ , for healthcare vs birth rate analysis
- GenderEqualityAnalysis.ipynb’, for gender equality vs birth rate analysis

# Output file 
### 3. Data used for analysis (wrangled datasets)

After preprocessing the datasets, there are some results are generated by the code and applied into Tableau:

- femaleData.xls, for gender equality analysis 
- combined.csv, for economy analysis 
- wrangled_health_CP.csv, contraceptive prevalence after dealing with missing values
- wrangled_health_MR.csv, mortality rate of infant after dealing with missing values
- Br_health.csv, merge birthrate data with healthcare data(contraceptive prevalence and mortality rate of infant)


# Screenshots file 
### 4.Clear screenshots of your visualization(s)
[Screenshots](https://github.com/JJJJJingL/DataVisualizationDemo/blob/master/Screenshot%20of%20plots.pdf)


# Visualizations 
### 5.Data visualization(s)
 Please see screeshots file and jupyter file
 some visualizations in Tableau you could find:  
   
1. [Female wage index](https://public.tableau.com/profile/jingjing.lin2982#!/vizhome/femaleTab/BirthRateVSFemaleWageIndex?publish=yes)   

2. [Compare birth rate and gdp](https://public.tableau.com/profile/yq6720#!/vizhome/503project/Sheet2?publish=yes)  

3. [2017 global birth rate(heat map)](https://public.tableau.com/profile/yq6720#!/vizhome/worldbirthrate2017/Sheet2?publish=yes)  

4. [Time series global birth rate](https://public.tableau.com/profile/yq6720#!/vizhome/globaltimeseriesbirthrate/Sheet1?publish=yes)   

# Slides 
### 6.Your slides and any other presentation material

[Group9-503 Final Project.pdf](https://github.com/JJJJJingL/DataVisualizationDemo/blob/master/Final%20Project.pdf)





