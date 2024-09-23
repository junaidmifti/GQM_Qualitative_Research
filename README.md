# Impact of Physical Health and Daily Habits on Developer Productivity

This repository contains the research and analysis on how daily habits and physical health affect the productivity of software developers, conducted as part of SE 611: Software Metrics. The study explores correlations between various daily habits, physical health attributes, and developer productivity using the Goal-Question-Metric (GQM) paradigm.

## Table of Contents
- [Introduction](#introduction)
- [GQM Paradigm](#gqm-paradigm)
- [Data Collection](#data-collection)
- [Metric Implementation](#metric-implementation)
- [Results and Analysis](#results-and-analysis)
- [Conclusion](#conclusion)
- [Resources](#resources)

## Introduction

This research aims to assess the impact of developers' daily routines and physical health on their productivity. Data was collected from Bangladeshi software professionals using a survey, and the analysis was performed using the GQM framework. Various productivity metrics such as decision-making contribution, task satisfaction, and interaction willingness were analyzed in relation to health metrics like sleep duration, BMI, and meal timing.

## GQM Paradigm

The Goal-Question-Metric (GQM) approach was used to define the research framework:

- **Goal**: Analyze developer productivity in relation to daily habits and physical health.
- **Questions**:
    - What is the developer's productivity level?
    - What are the health factors affecting productivity?
- **Metrics**:
    - **Productivity**: Task satisfaction, decision contribution, interaction willingness.
    - **Health**: Average sleep duration, exercise frequency, meal timings.

## Data Collection

A survey was prepared to gather information from software developers, focusing on their work habits, health, and daily routines. The survey used a Likert scale for most responses, and data was collected from 48 respondents.

## Metric Implementation

The data was pre-processed, encoded, and analyzed using the following libraries:

- **pandas, numpy**: For data manipulation and cleaning.
- **matplotlib, seaborn**: For data visualization.

We applied correlation analysis (Spearman correlation) to identify statistically significant relationships between productivity factors and health metrics.

## Results and Analysis

The analysis revealed several key correlations:

- **Positive Impact**: Meal timings, particularly breakfast and lunch, showed a positive correlation with task satisfaction and productivity.
- **Negative Impact**: Inconsistent sleep patterns negatively affected external interactions and deadlines.
- **Neutral Impact**: Factors like BMI and smoking habits showed little to no impact on productivity.

### Visualization
- [Heatmap Analysis](https://github.com/bsse1006/ImpactOfPhysicalFitnessOnDeveloperProductivity/blob/main/heatmap.ipynb)
- [Bar Chart Analysis](https://github.com/bsse1006/ImpactOfPhysicalFitnessOnDeveloperProductivity/blob/main/barCharts.ipynb)

## Conclusion

The study concluded that while certain health habits like meal timing positively impact developer productivity, other factors like BMI and sleep duration show varied results. Overall, health factors have both positive and neutral impacts on different aspects of productivity.

## Resources
- [Survey Questionnaire](https://forms.gle/W4MxK2iwoQ1rgqQ19)
- [Project Source Code](https://github.com/bsse1006/ImpactOfPhysicalFitnessOnDeveloperProductivity)
