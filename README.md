# Harnessing Big Data to Identify Financially Material DEI Metrics

## Description
The pipeline demo code is available in .ipynb notebook format. Download the notebook to try with the provided 'demo_example_input.csv.' Note that the output from the pipeline will have a different name than the provided example output CSV. 

The folder also includes two CSVs that list the practice, outcome, and DEI terms that our pipeline is built to identify and categorize the terms by topic and/or theme. The keywords used to identify each term and practice and outcome terms' patterns and context windows are also listed. These two CSVs must also be downloaded and added to the working directory housing the demo notebook for a demo run.
This repository is composed of three folders of resources: 
1) Dataset_Results: An Excel file of simplified pipeline results for each dataset used in our analysis 
2) Pipeline_Demo: A Python notebook copy of our pipeline code with a sample input file, sample output file, and other supporting files.
3) Term_Dictionaries: CSV files that list our term dictionaries

## About Dataset_Results
We have shared the public version of our data analysis results in these files. If you are interested in access to our full data results for collaboration, please reach out to **[]**. 

The columns of each file are color-coded according to this code:
- Blue: Data from the original dataset (input columns).
- Green: Descriptive summary columns (output columns). These columns list the terms found in each text based on category. The category and identified term pattern are listed with each term.
- Yellow: Summary indicator columns (output columns). These columns indicate if a type of term or term-co-occurrence has appeared, and thus can be toggled to filter for texts that have/do not have them by filtering for 1 or 0, respectively. The first yellow column to the left 'ANY_PRACTICE_OR_OUTCOME' is the indicator for texts flagged for at least one practice-outcome term co-occurrence--1 is a positively flagged text and 0 means no co-occurrence was found. (Given the size of the proxy statements dataset, the uploaded file only includes the texts positively flagged for a term co-occurrence ('ANY_PRACTICE_OR_OUTCOME' == 1)
- Gray: Individual indicator columns (output columns). These columns indicate if a specific term or keyword has appeared in a text and can be toggled in the same manner as the yellow summary indicator columns.

## About Pipeline_Demo
The pipeline demo code is available in .ipynb notebook format. Download the notebook to try with the provided 'demo_example_input.csv.' Note that the output from the pipeline will have a different name than the provided example output CSV. 

The folder also includes two CSV files that list the practice, outcome, and DEI terms that our pipeline is built to identify and categorize the terms by topic and/or theme. The keywords used to identify each term and practice and outcome terms' patterns and context windows are also listed. These two CSVs must also be downloaded and added to the working directory housing the demo notebook for a demo run.

## About Term_Dictionaries
Each file lists the terms (practice, outcome, DEI, and context) that our pipeline is built to identify and categorizes them by topic and/or theme. The keywords used to identify each term and practice and outcome terms' patterns and context windows are also listed.
