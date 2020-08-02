<a href="url"><img src="assets/logo.png" align="left" height="60" width="60" ></a>

# SABER PRO Data Analysis Repo 

This Repo stores data cleaning and preparation, AWS integration and data analysis notebooks of Team 25 for the *Analyzing and Predicting Performance on the SABER PRO* project created for DS4A. 

## Introduction

Each year, Colombian undergraduates take the Test for the Quality of Higher Education - Saber PRO, as a prerequisite for graduation. The test assesses math, reading, citizenship, writing and English skills of students at every higher education institution. The scores of this test become publicly available each year, with the idea that institutions and the Government identify vulnerable populations and adjust their education policies. 

The raw data consists on yearly files for each of the databases:

* Saber11
* Saber-Pro

As well as files for
* Basic Education Indicators
* State and city locations

The raw data was obtained from: https://www.datos.gov.co/

The code on this repo contains the notebooks that detail our process of data wrangling and cleaning which included joining different datasets from different years, handling missing values, correcting formats, data types, values and names, as well as performing string operations on variables.

The code also contains noteboooks that run different models, including Linear Regression, Random Forest, XG Boosting, and spatial models, that were created in order to predict performance on the Saber-Pro tests.

## File Description

### Folder Structure

Folder PATH listing:
│   
├───data_preparation
│   │   .gitignore
│   │   .Rhistory
│   │   .Rprofile
│   │   01_create_data.Rproj
│   │   README.md
│      
├───models
│   │   .gitignore
│   │   .Rhistory
│   │   .Rprofile
│   │   01_create_data.Rproj
│   │   README.md
├───assets
│   │   logo.png
│   │   file_relation.png
│   │


### File Relation




