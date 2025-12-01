# Claims Analysis Project 
### Project Overview
This project simulates the daily analysis performed by healthcare data analysts, medical billing specialists, and health informaticians. Using a sample of prospective claims data from Stony Brook University Hospital, the goal is to explore provider billing patterns, common diagnoses and procedures, and payer relationships to support operational and compliance decision-making. This assignment helps develop practical skills in Python and pandas within a real-life scenario. 

### Data source 
All 3 of the CSV files were provided (STONYBRK_20240531_HEADER.csv, STONYBRK_20240531_LINE.csv, and STONYBRK_20240531_CODE.csv) as part of the project module. The Header file contains high-level claim information. The Line file contains important procedure/service information. And the Code file contains ICD-10 codes for the claims billed.

### Running the Notebook
A folder was created on my local machine, which would then be published to GitHub. Within this folder/repository, a data folder and a readme.md file, requirements.txt file, and Python notebook were all added. The three CSV files previously mentioned were uploaded to the data folder. From there, a virtual environment was created, and the required packages were installed. From here on, the script can be made and run in the claims_analysis.ipynb

### Key Findings
After analyzing the results Medicare was consistently one of the largest payers by both claim volume and total charges. This aligns with the understanding that the elderly population is one of the fastest-growing groups in the United States, which is reflected in the claims data from this period. Medicare’s position as the highest-billing payer also corresponds with the large number of claims originating from doctors’ offices and inpatient settings. As people age, they generally require more frequent medical care, ongoing monitoring, and increased hospital utilization, all of which contribute to higher claim counts and total charges. Another key finding in this analysis is that the most commonly billed ICD-10 diagnosis code was J96.01, which represents acute respiratory failure with hypoxia. This condition can be noted in older individuals and chronically ill patients. However, it is also important to note that the claim period started in September of 2023, which is the beginning of the COVID-19, Flu, and RSV season. The large amount of billing for this code can not only be associated with the elderly population, but may potentially be connected with the seasonal viral load. 

### Required Libraries
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0

located in the requirements.txt file 