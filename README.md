DS202.3 – Data Programming with R: Clinical Data Analysis

This repository contains our group project for the DS202.3 module. We conducted an Exploratory Data Analysis (EDA) on the MSK-CHORD dataset, comprising 24,950 patient records, to explore survival outcomes using clinical and genomic features.

Analytical Goal
Our project addresses whether basic demographics (Age, Sex) and clinical markers (Tumor Stage, FGA) can be used to construct a predictive roadmap for patient survival outcomes.

Key Implementation Steps
Data Cleaning: Standardization of NLP-derived clinical fields and handling missing values using Median Imputation.

Feature Engineering: Creation of a binary Survival Response Proxy based on the median overall survival months.

Visualization: Utilizing ggplot2 for multivariate analysis, including Boxplots, Density plots, and Stacked bar charts.

Genomic Insights: Detailed analysis of the correlation between Fraction Genome Altered (FGA) and various Cancer Stages.

Technology Stack
Language: R

Environment: RStudio

Key Libraries: tidyverse, dplyr, ggplot2, readr

Repository Structure
Main Notebook: R Markdown file containing both code and the analytical report.

Dataset: The clinical data file used for all computations.

Outputs: Exported visualizations used for data interpretation.

Group Members
1.D. S. S. Nayakasena-36285
2.W.G.B.D.Gamage - 35273
