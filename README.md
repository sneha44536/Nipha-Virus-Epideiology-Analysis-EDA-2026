# Nipha-Virus-Epideiology-Analysis-EDA-2026
"A comprehensive Python-based analysis of Nipah Virus (NiV) outbreak data. This project investigates demographic trends, transmission sources (like raw date palm sap), and patient outcomes through data visualization and preprocessing."


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
[![Matplotlib](https://img.shields.io/badge/matplotlib-%23E06E7F.svg?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)

# Nipah Virus (NiV): Historical Trends & Case Study Analysis 🦠

## Project Overview
This repository contains a comprehensive data analysis of the Nipah Virus, a zoonotic pathogen with high mortality rates. The project is divided into two main parts: where the analysis is done on the two diffrent levels.
1. *Global Historical Analysis (1998 - 2026):* Visualizing death counts, mortality rates, and transmission sources across different countries.
2. *Local Case Study (Rajshahi, 2026):* A detailed look at patient demographics, symptom distribution, and recovery status from the latest outbreak data.

##  Part 1: Global Epidemiology (1998-2026)
In this section, I analyzed historical data to identify long-term patterns:
* *Mortality Rate Analysis:* Visualized how the fatality rate fluctuates by year and region.
* *Country Comparison:* A bar plot comparing case counts in Bangladesh, India, Malaysia, and Singapore.
* *Symptom Distribution:* A horizontal bar chart identifying the most common clinical signs (Fever, Headache, Seizures, etc.).

##  Part 2: Rajshahi Outbreak Case Study
Using the  original nipah_bangladesh_2026.csv dataset from kaggle, I performed specific data cleaning and visualization:
* *Data Mapping:* Standardized 'Gender' values to 'M' and 'F' for better plot aesthetics.
* *Case vs. Contact:* Analyzed the ratio of primary cases to secondary contacts to understand transmission depth.
* *Status Visualization:* Used custom color-coding (Green/Red/Orange) to track 'Cleared' vs 'Symptomatic' patients.

##  Technical Stack.
* *Language:* Python 3.x
* *Data Manipulation:* Pandas, NumPy
* *Data Visualization:* Matplotlib (using dark_background style for modern UI),Bar plot,Horizontal Bar plot.
* *Environment:* Jupyter Notebook

##  Featured Visualizations
> [!TIP]
> Use the dark-themed plots from my jyupter notebook here! They look incredibly professional and classy too. 


##  Key Findings
* *Demographics:* Identifying specific age groups (e.g., 20-40) that are more frequently symptomatic.
* *Transmission:* Confirming the role of "Raw Date Palm Sap" as a primary transmission source in the 2026 data.
* *Clinical Insights:* Highlighting the prevalence of "Fever" and "Death Symptoms" in positive cases.

## 🚀 How to Use
1. Clone the repository.
2. Ensure you have the datasets csv_dataset.csv and nipah_bangladesh_2026.csv in the root folder.
3. Run the Jupyter Notebook to reproduce the plots.
