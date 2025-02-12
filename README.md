# Fetch Assessment

This project is designed to retrieve data from a specified JSON, organize, quality check, and email stakeholders

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vidyun-ai/Fetch_assessment.git
   cd Fetch_assessment
   ```

2. **Set Up the Environment**:
   - Ensure you have [Python 3.7.3](https://www.python.org/downloads/release/python-373/) installed.
   - Install the required packages:
     ```bash
     pip install -r requirements.txt
     ```

## Usage

1. The data folder contains the JSON files related to the project

2. Fetch_ERD_Proposed.png is the proposed ERD for the JSON files. Though the 3NF format can be more achieved, this proposed ERD will help to organize the data better

3. Fetch_Analysis.ipynb contains Python code to generate the tables and checks for quality issues and summary of each table and generate the report

4. Data_Analysis_Report.xlsx -This file contains each table and its data quality summary

5. fetch_queries.txt contains SQL queries

6. Email_stakeholder.txt contains the email that needs to be sent to stakeholder


