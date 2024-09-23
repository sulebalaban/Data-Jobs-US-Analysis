# Data Jobs US Market Analysis

This repository contains a detailed analysis of data job postings in the United States, focusing on the top 3 job titles: Data Analyst, Data Scientist, and Data Engineer. 
## Project Overview

The goal of this project is to:
- Extract job data specific to the United States.
- Perform monthly trend analysis for the top 3 data-related job titles.
- Visualize the results to understand the fluctuations in job postings over the months.

## Dataset

The dataset is publicly available on Hugging Face: [lukebarousse/data_jobs](https://huggingface.co/datasets/lukebarousse/data_jobs). It includes various data job postings from around the world.

## Analysis Steps

1. Filtered the dataset for job postings in the United States.
2. Converted the `job_posted_date` column to datetime format.
3. Extracted the month from the posting date to identify trends.
4. Created pivot tables to visualize job posting trends by month.
5. Plotted the top 3 data job titles by the number of job postings.

## Key Libraries Used
- `pandas`
- `matplotlib`
# Visualizations

The final output is a line plot that shows the monthly trends for the top 3 job titles.


