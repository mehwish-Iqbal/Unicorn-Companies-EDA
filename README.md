# 🦄 Unicorn Companies Exploratory Data Analysis (EDA)
## Introduction

In this project, I explore a dataset of unicorn companies to identify trends, patterns, and insights that can help investment firms make informed investment decisions. Through exploratory data analysis (EDA), I examine company valuations, founding years, industries, geographic distribution, and the time required for companies to achieve unicorn status. The goal is to uncover factors associated with high-growth companies and provide data-driven insights for potential investment opportunities.
## Project Overview
This project analyzes a dataset of 1,074 unicorn companies using Python, Pandas, Matplotlib, and Seaborn. The analysis includes data cleaning, exploratory data analysis, and visualization to identify trends in valuation, industries, and company growth.
## Objectives

1. Visualize the time it took companies to reach unicorn status.
2. Visualize the maximum unicorn company valuation per industry.
3. Sort the dataset to gain insights into the latest unicorn companies.
4. Determine the number of companies founded each year.
5. Count unicorn companies by month.
6. Observe trends over time by identifying the quarter in which the most companies became unicorns in 2021.
7. Compare valuation trends across quarters for the years 2020 and 2021.
8. Visualize the time it took companies to become unicorns.
---
## Dataset Information

The dataset contains information on 1,074 unicorn companies from various countries and industries around the world. It includes details related to company valuation, founding year, funding, industry classification, geographic location, and the date each company achieved unicorn status.
## Dataset

Source: [Unicorn Companies Dataset](https://drive.google.com/file/d/1QJf93hPKyHRaUe-CuA4wJsK7JcThxuX9/view?usp=drive_link)

### Features

* **Company** – Name of the unicorn company
* **Valuation** – Company's estimated valuation
* **Date Joined** – Date when the company achieved unicorn status
* **Industry** – Industry category of the company
* **City** – City where the company is based
* **Country/Region** – Country or region where the company operates
* **Continent** – Continent of the company's location
* **Year Founded** – Year the company was established
* **Funding** – Total funding received by the company
* **Select Investors** – Key investors associated with the company
---
## Data Cleaning

The following data cleaning and preparation steps were performed:

1. Inspected the dataset structure and data types using `.info()`.
2. Checked for missing values across all columns
3. Converted the `Date Joined` column to datetime format.
4. Created additional date-related features (month, quarter, and year) for analysis.
5. Standardized and prepared the data for exploratory data analysis and visualization.

---
## Exploratory Data Analysis (EDA)

The following analyses were conducted to explore trends and patterns in the unicorn companies dataset:

1. Determined the number of companies founded each year.
2. Counted unicorn companies by month.
3. Analyzed the distribution of companies that achieved unicorn status in each quarter of 2021.
4. Examined the time required for companies to become unicorns.
5. Compared company valuations across quarters for the years 2020 and 2021.
6. Identified the maximum unicorn company valuation by industry.
7. Explored trends among the most recently founded unicorn companies.
8. Investigated the relationship between founding time and the time taken to achieve unicorn status.

---
