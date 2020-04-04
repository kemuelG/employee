# Employee Attrition - DATA 1282 Project
> An basic analysis of employee attrition based on factors such as income, job role and education.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Directory Structure](#directory-structure)
* [Insights](#insights)
* [Status](#status)
* [Contact](#contact)
* [Readme Credits](#readme-credits)

## General info
The project is part of the requirement for DATA 1282 - Data Analysis Tools for Analytics. It involves loading data from storage, performing basic transformations on the data using SQL, processing the data using various aggregations in SQL then performing basic analysis in Microsoft Excel.

## Technologies
* HDInsight 4.0
* Hadoop 2.7.3
* Microsoft Excel 2013

## Setup
1. Download dataset using link from data directory
2. Load dataset into HD insight with Hadoop cluster
3. Use Ambari Views in HDInsight to perform transformations (documentation found in munge directory)
4. Use Ambari Views in HDInsight to perform data aggregations (documention found in src directory)
5. Download final aggregated data from (4) and create 2 visuals (dashboard and histogram as seen in xlsx file in reports directory)

## Directory structure
Directory: <br />
Employee (repo) <br /> 
&nbsp;&nbsp;&nbsp; * data (folder) <br />
&nbsp;&nbsp;&nbsp; * munge (folder) <br />
&nbsp;&nbsp;&nbsp; * src (folder) <br />
&nbsp;&nbsp;&nbsp; * reports (folder) <br /> 
README.md

## Insights
Summary of insights found from analysis
* Attrition can be found among 20% of salespeople from the HR data
* Similar monthly income distributions (right-skewed) for sales people with and without attrition. 
* Most salespeople in the company make about $5000 per month (21% of all salespeople)
* Non-attrition is higher for salespeople with a monthly income of $5000
* Salespeople with an income of $15,000 more more are less likely to leave the company

## Status
Project is: _finished_

## Contact
Created by [@kemuelG]

## Readme credits
ritaly  https://github.com/ritaly/README-cheatsheet
