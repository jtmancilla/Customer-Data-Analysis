# Project: Arvato Bertelsmann Customer Analysis


## Project Motivation

The goal of this project is to predict which individuals are most likely to convert into becoming customers for a mail-order sales company in Germany.

**Customer Segmentation Report** - This analyzed demographics data for customers of a mail-order sales company in Germany. This used unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. 


## Table of Contents:

1. [Installation](#installation)
2. [Data Files](#files)
3. [Instructions](#instructions)
4. [Results](#results)
5. [Acknowledgements](#acknowledgements)


## Installation: <a name="installation"></a>
Download and Install Anaconda distribution of Python. The code should run with no issues using Python versions 3.7.3.



## Data Files: <a name="files"></a>

There were four data files provided by Arvato for this project. The last file was created by the user. As part of the terms and conditions of Arvato, the files cannot be shared in this repository. However, they can be described below.

1. Udacity_AZDIAS_Subset.csv: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
2. Udacity_CUSTOMERS_Subset.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
3. Data_Dictionary.md: Detailed information file about the features in the provided datasets.
4. AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns


## Instructions: <a name="instructions"></a>

Since the data files are not available publicly, the Jupyter notebook is just for exploration. 


- Part 1 Customer Segmentation Report - Analysis of customers



## Results <a name="results"></a>

Cluster 4 is overrepresented in the customers data compared to general population data. Some characteristics of the group of population that are relative popular with the mail-order company:

in areas where the share of 6-10 family homes is lower (PLZ8_ANTG3=1.73)
in Prosperous or Comfortable households (WEALTH=2.75)
in life stage of Families With School Age Children or Older Families & Mature Couples (LIFE_STAGE=3.30)
Cluster 13 is underrepresented in the customers data. Some characteristics of the segment of the population that are relatively unpopular with the company:

in areas where the share of 6-10 family homes is higher (PLZ8_ANTG3=2.44)
in Less Affluent or Poorer households (WEALTH=4.4)
in life stage of Pre-Family Couples & Singles or Young Couples With Children (LIFE_STAGE=1.98)



## Acknowledgements <a name="acknowledgements"></a>

Must give credit to Arvato Financial Solutions and Udacity for the challenge and data.
