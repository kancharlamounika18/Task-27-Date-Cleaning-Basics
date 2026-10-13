# Task-27-Date-Cleaning-Basics

Day 27 of 45 — Data Analytics Internship

Organization: Veda Technology
Internship: Data Analytics Intern
GitHub Repository Name: Date-Cleaning-Basics

Objective

Standardize inconsistent date formats, identify invalid or missing dates, and create a reliable cleaned date column for analysis.

Tools Used

•
Python

•
pandas

•
Microsoft Excel

Project Files

•
retail_sales_dataset.csv — Original retail sales dataset containing inconsistent dates

•
cleaned_retail_sales.csv — Dataset with standardized dates and date-status information

•
date_cleaning.py — Reusable Python date-cleaning script

•
date_issue_log.csv — CSV log of invalid and missing dates

•
date_issue_log.xlsx — Excel issue log and summary workbook

Date Cleaning Operations

The project performs the following operations:

•
Reads retail sales records

•
Accepts multiple date formats

•
Converts valid dates to YYYY-MM-DD

•
Identifies missing date values

•
Identifies invalid dates such as impossible calendar dates

•
Adds a date-status field

•
Creates a separate issue log for review

Dataset Summary

•
Total records: 20

•
Valid dates: 16

•
Date issues identified: 4

•
Output date format: YYYY-MM-DD

Excel Workbook Sheets

The date_issue_log.xlsx workbook contains:

•
Issue_Log — Invalid and missing date records with recommended actions

•
Summary — Record counts, parser approach, and generated files

How to Run

1.
Download all project files into the same folder.

2.
Make sure Python and pandas are installed.

3.
Open a terminal in the project folder.

4.
Run:

Bash


python date_cleaning.py



1.
The script reads retail_sales_dataset.csv.

2.
It creates or updates cleaned_retail_sales.csv and date_issue_log.csv.

3.
Open date_issue_log.xlsx to review the issue summary.

Date Quality Notes

The input dataset intentionally includes different date formats, a missing date, and invalid dates such as September 31 and April 31. These records are not silently changed; they are marked as issues so they can be reviewed and corrected from the original source.

Internship

Completed as part of the Veda Technology Data Analytics Internship.

