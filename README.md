# NIPS Papers Data Analysis and Visualization

For the NIPS dataset, you can download it from [Kaggle](https://www.kaggle.com/datasets/yerbaaaa/nips-19872020).

## Table of Contents

- [Introduction](#introduction)
- [Data Import and Cleaning](#data-import-and-cleaning)
- [Exploratory Data Visualization](#exploratory-data-visualization)
- [LDA Analysis](#lda-analysis)
- [Conclusion](#conclusion)

## Introduction

In this project, we conducted an extensive analysis and visualization of the NIPS (Neural Information Processing Systems) papers dataset from 1987 to 2022. Our primary objective was to gain insights into trends, topics, authors, and institutions within the dataset, shedding light on the landscape of neural information processing systems research.

## Data Import and Cleaning

We began by importing necessary libraries and loading the provided CSV files: `papers.csv`, `institutions.csv`, and `authors.csv`. Data cleaning was carried out to eliminate irrelevant columns, and institution information was merged with authors' data to provide context for the analysis.

## Exploratory Data Visualization

We utilized various visualizations to provide an overview of the dataset:

- **Distribution of Articles Over the Years:** A countplot to visualize the distribution of articles published over the years.
- **Top Authors and Institutions:** Bar graphs highlighting the top authors and institutions based on article count.
- **Top Countries:** A bar graph displaying the top countries contributing to the articles.

- **Word Clouds for Titles and Abstracts:** Word clouds capturing the most common words in processed titles and abstracts.

- **Top 10 Most Common Words in Processed Titles:** A bar plot revealing the top 10 most common words in processed titles.

- **Top 10 Most Common Words in Processed Abstracts:** Another bar plot showcasing the top 10 most common words in processed abstracts.

## LDA Analysis

We applied Latent Dirichlet Allocation (LDA) to uncover the underlying topics within titles and abstracts:

- **LDA Analysis on Processed Titles:** Applying LDA to processed titles revealed hidden topics, offering insights into overarching themes.
- **LDA Analysis on Processed Abstracts:** LDA analysis on processed abstracts helped unveil significant topics present in the abstracts.

## Conclusion

This project's comprehensive analysis and visualizations provided valuable insights into the NIPS papers dataset. We explored temporal trends, identified influential authors and institutions, visualized geographical distribution, and extracted key topics using LDA. The project contributes to understanding the evolving landscape of neural information processing systems research and serves as a foundation for future investigations.

Please refer to the provided code snippets for each analysis and visualization step.