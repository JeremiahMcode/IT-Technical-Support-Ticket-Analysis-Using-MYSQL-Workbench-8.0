IT Technical Support Ticket Analysis

This projects demonstrate my proficiency in SQL and my ability to analyze operational data to generate meaningful business insights. They highlight skills in data cleaning, investigation, KPI analysis, and performance evaluation.

IT Help Desk Ticket Analysis

Technical Support Dataset.csv

Support ticket SQL code.txt

Project Description

This project involved analyzing IT help desk support ticket data to evaluate operational efficiency, service quality, and agent performance. The dataset contains detailed information on ticket creation and resolution times, issue topics, products, assigned agents, agent groups, and customer satisfaction feedback.

I used SQL to explore the data, answer business-driven questions, and uncover insights related to resolution efficiency, SLA compliance, backlog risk, and customer experience. The goal of the analysis was to simulate real-world IT service desk analytics used by IT operations and support leadership.

Tasks Performed

Performed initial data exploration and validation checks on the IT support ticket dataset

Cleaned and standardized timestamp fields by converting blank values to NULL and applying datetime formats

Calculated overall and topic-level average ticket resolution times

Analyzed unresolved ticket rates to assess backlog and operational risk

Identified product and topic combinations contributing most to unresolved tickets

Evaluated SLA compliance by measuring tickets resolved within 24 hours

Ranked agents within each agent group based on average customer feedback

Identified agents with the highest proportion of SLA exceptions

Compared individual agent performance against group averages

Analyzed the relationship between resolution speed and customer satisfaction

Used SQL techniques such as GROUP BY, HAVING, CASE statements, CTEs, and window functions

Summarized findings in a written analysis for business and leadership consumption

Key Insights

Most tickets are resolved within acceptable timeframes, though SLA exceptions are concentrated in specific issue categories

A small number of products and topics drive a disproportionate share of unresolved tickets

Agent performance varies significantly across groups, indicating opportunities to standardize best practices

Faster ticket resolution is generally associated with higher customer satisfaction scores

Files in This Repository
File Name	Description
Technical Support Dataset.csv	Raw IT help desk ticket data
Support ticket SQL code.txt	SQL queries used for all analyses
IT Support Ticket Analysis Document.docx	Written report summarizing findings, insights, and recommendations
About SQL

SQL (Structured Query Language) is used to interact with relational databases and perform data analysis tasks such as:

Filtering and aggregating data

Analyzing trends and performance metrics

Ranking and comparing entities using window functions

Identifying patterns and operational inefficiencies

This project was completed using MySQL / MySQL Workbench 8.0.

Usage

Install MySQL or MySQL Workbench

Import the Technical Support Dataset.csv file into a database table

Run the queries from Support ticket SQL code.txt

Modify queries as needed for further analysis or exploration
