# Job Market Analytics for Resume & LinkedIn Optimization

## Project Overview

This project analyzes job postings collected during the project to identify job-market requirements, in-demand skills, software/tools, experience requirements, salary availability, and role-related trends.

The project was developed for Quantric Intelligence to support data-driven Resume Writing and LinkedIn Optimization services.

The complete internal working datasets are not included in this public repository. Selected sanitized/sample data and project outputs are provided for portfolio and demonstration purposes.

## Objectives

* Analyze job-market requirements across collected job postings
* Identify frequently occurring skills and tools
* Analyze experience and salary availability
* Identify job-role and hiring trends
* Apply regression analysis to Python-related job demand
* Develop Power BI reporting for business intelligence
* Generate data-driven inputs for resume and LinkedIn optimization

## Data Collection

Job data was collected through:

* Manual collection from LinkedIn and Naukri
* Python-based API collection maintained as a separate raw dataset

The raw datasets were maintained separately during the project for data collection and preparation.

The Power BI dashboard was developed using the manually collected job dataset after data preparation and processing.

## Data Processing

The project includes:

* Data validation
* Duplicate checking
* Missing-value handling
* Text standardization
* Date formatting
* Experience categorization
* Salary availability classification
* Skills extraction and normalization
* Tools/software extraction and normalization

## Dataset

The project included a final cleaned dataset containing:

* **300 job postings**
* **16 analytical columns**
* **185 Fresher / Entry Level postings**
* **115 Experienced postings**

The normalized Skills Table contains:

* **2,013 skill records**
* **287 unique skills**

The normalized Tools Table contains:

* **1,202 tool records**
* **406 unique tools**

Only selected sanitized/sample data is included in this public repository.

## Analysis

The project covers:

* Job role analysis
* Industry analysis
* Company analysis
* Location analysis
* Experience analysis
* Salary availability analysis
* Skills analysis
* Tools/software analysis
* Job source analysis

## Machine Learning

Linear Regression was applied to forecast weekly Python-related job demand.

### Model Evaluation

* **MAE:** 3.51
* **MSE:** 19.84
* **R² Score:** 0.41

### Forecast

* **Week 8:** 14.7
* **Week 9:** 16.6

## Power BI

A Power BI dashboard was developed using the manually collected and prepared job dataset to present job-market information through interactive business intelligence reporting.

The dashboard covers areas such as:

* KPIs
* Skills
* Tools
* Companies
* Industries
* Locations
* Experience
* Salary
* Job sources

Dashboard screenshots are included in the repository for demonstration.

## Business Application

The findings support data-driven inputs for Quantric Intelligence's services, including:

* ATS Resume Optimization
* LinkedIn Headline Optimization
* Skills Recommendations
* Project Recommendations
* Job-Role Matching

## Tools Used

* Python
* Pandas
* Microsoft Excel
* Power BI
* Linear Regression

## Project Context

This project was developed as part of the Summer Internship Project at Quantric Intelligence.

**Project Title:** Job Market Analytics for Resume & LinkedIn Optimization - A Data-Driven Approach

## Data Privacy

The complete internal working datasets used during the project are not publicly shared in this repository.

Publicly available files are sanitized/sample materials provided for project demonstration and portfolio purposes.
