 # **Project 1**                       

**Project Objective:**

•Study trends and patterns in issued building permits in the property development sector.

**Focus Areas:**

•Identify key drivers affecting building permit issuance.

•Analyze the impact of government policies on property development.

**Approach:**

•Examine historical permit data and relevant regulations.

•Assess the effects of market conditions on development trends.

**Goal:**

•Provide insights for developers and policymakers to improve project planning.

•Propose strategies for navigating regulatory environments efficiently.


### Project 1 :Analysis of Issued Building Permits in Property Development  
                                                                                
**1**. **Exploratory Data Analysis**

**Project Description**: The project involves analyzing building permit data from Vancouver to identify trends, patterns, and structures in permit processing times.

**Project Title:** Exploratory Analysis of Building Permit Processing Times in Vancouver

**Objective:** To explore and understand the distribution and trends in permit processing times across different categories.

**Dataset:** The dataset includes building permit records from Vancouver’s Open Data Portal, with 296 records for 2023 and 191 records for 2024.

**Methodology**:

•	**Data Discovery**: Filtering of the dataset to focus on relevant records, resulting in a manageable number of entries for each year.

![123](https://github.com/user-attachments/assets/cc8c3eb1-d3f5-4d6f-89cd-498b734855f3)

![qqq](https://github.com/user-attachments/assets/9dc9c12e-5b00-44f2-8e1e-cb76c47b7967)

•	**Data Analysis:** Execution of SQL queries in AWS Athena to explore data and identify trends in permit elapsed days.

![mmm](https://github.com/user-attachments/assets/865753bf-719c-40e0-bdd2-f36089519d36)

**Tools and Technologies:**

•	AWS Athena: For running SQL queries to explore the data.

•	Vancouver Open Data Portal: Source of the permit data.

**Deliverables:**

•	Data Insights: Identification of trends and patterns in permit processing times.

•	Exploratory Results: SQL query outputs that reveal data trends.

**Timeline (2 days):**


**Day 1**:

- Set up data storage (landing, raw, and curated folders) for building permit records.
  
- Filter the dataset to focus on relevant records for 2023 and 2024.
  
- Conduct an initial review of the dataset to assess completeness and scope.

**Day 2**:

- Execute SQL queries in AWS Athena to explore building permit data.
  
- Identify trends and patterns in permit processing times.
  
- Extract SQL query results for further analysis.






**2**. **Descriptive Analysis**

**Project Description:** This analysis summarizes key features of the building permit data to provide a clear overview of permit processing times.

**Project Title:** Descriptive Summary of Building Permit Processing Times

**Objective**: To provide a summary and visual representation of permit processing times across different categories.

**Dataset:** The dataset includes records of building permits for 2023 and 2024, detailing elapsed days for each permit category.


**Methodology:**

•	**Sum of Permit Elapsed Days**: Calculation of total elapsed days for each permit category.

•	**Data Visualization**: Creation of pie charts in Excel to illustrate the distribution of elapsed days.

<img width="242" alt="ooo" src="https://github.com/user-attachments/assets/12a3fd26-abd0-4a19-ad76-52192eedb110">

•       **Publishing in General Server** -The data visualization was made available on a general server for internal users, providing restricted access to the organization via Windows Remote Desktop.

![ooo](https://github.com/user-attachments/assets/19a83f5b-f136-4925-a57e-e27774331ef7)


![000-2](https://github.com/user-attachments/assets/28e3e965-583f-4545-8888-f327255d8deb)



 •      **Publishing in web Server** -The visualization was eventually made publicly accessible through a web server hosted on AWS EC2

 ![000-2](https://github.com/user-attachments/assets/a2ed39d9-9465-4c03-a10a-2a14687a9554)
 

**Tools and Technologies:**


•	**Excel:** For creating pie charts and visualizing data.

•	**AWS Athena:** For querying and summarizing data.

<img width="142" alt="000-2" src="https://github.com/user-attachments/assets/f219952c-b3e3-47b1-8389-9c820c9346d6">


**Deliverables:**


•	**Summarized Data:** Total elapsed days per permit category.

•	**Visualizations:** Pie charts showing the distribution of elapsed days.


**Timeline (2 days):**

**Day 3**:
 - Calculate the sum of permit elapsed days for each category using AWS Athena.
   
 - Generate summarized data tables for permit processing times across 2023 and 2024.

**Day 4**:

- Use Excel to create pie charts and visual representations of the summarized data.
  
- Analyze the pie charts to identify key insights into permit processing distributions.
  
- Finalize and document the descriptive analysis results.







**3**. **Diagnostic Analysis**

**Project Description**: The project focuses on understanding the reasons behind observed trends and anomalies in permit processing times.

**Project Title**: Diagnostic Analysis of Building Permit Processing Issues

**Objective**: To diagnose potential issues or inconsistencies in the permit processing data.

**Dataset**: Building permit records from 2023 and 2024, including details on elapsed days and permit categories.

**Methodology**:

•	**Data Cleaning**: Addressing missing values and removing unnecessary columns.

•	**Data Wrangling**: Transforming data by renaming columns and restructuring the dataset.

![ooo](https://github.com/user-attachments/assets/eb9db76f-033e-4227-b5a9-fabbdd4f8228)


![ooo](https://github.com/user-attachments/assets/2c0ec387-ab64-4a47-9e4b-8767b6f36c19)



**Tools and Technologies**:

•	**AWS Data Brew**: For cleaning data and handling missing values.

•	**AWS Glue**: For data transformation and pipeline management.

<img width="251" alt="image" src="https://github.com/user-attachments/assets/cebd0ba2-c2f7-4629-b0e4-d55b97fd6833">



**Deliverables**:

•	**Cleaned Data**: Data with missing values handled and irrelevant columns removed.

•	**Structured Data**: Transformed dataset with renamed columns and refined formats.

**Timeline (1day)**:

**Day 5**:

- Clean the dataset by handling missing values and removing irrelevant columns using AWS Data Brew.
  
- Perform data wrangling tasks like renaming columns and restructuring the dataset.
  
- Diagnose potential issues or inconsistencies in permit processing times by comparing cleaned data trends with initial findings from Projects 1 and 2.



**4**. **Data Wrangling**

**Project Description**: The focus is on transforming raw data into a structured and clean format suitable for analysis.

**Project Title**: Data Wrangling for Building Permit Analysis

**Objective**: To prepare raw building permit data for analysis by cleaning and structuring it.

**Background**:This project aims to improve the quality and usability of building permit data from the Vancouver Open Data Portal, covering records for 2023 and 2024. The goal is to enable effective analysis by cleaning, structuring, and securing the data.

**Dataset**: Data from the Vancouver Open Data Portal, including building permit records for 2023 and 2024.

**Methodology**:

•	**Data Storage Design**: Organization of data into landing, raw, and curated folders.

![ooo](https://github.com/user-attachments/assets/93cfc673-69b8-47ea-a280-85b74c91a16e)

•	**Dataset Preparation**: Cleaning and processing of datasets, handling missing values and irrelevant columns.

•	**Data Pipeline Design and Implementation**: Creation of ETL pipelines using AWS Glue to process and transform the data.

![ooo](https://github.com/user-attachments/assets/d0bbbced-624f-483d-9e93-b7f492539236)

			
•	**Data Monitoring**:

 - 	AWS CloudWatch for resource tracking, performance, and costs.

   ![ooo](https://github.com/user-attachments/assets/b518345e-9900-4759-a745-efdcd6fbd4f2)

 -  AWS CloudTrail for auditing and logging.

   ![ooo](https://github.com/user-attachments/assets/1722e050-9b21-4546-be08-d01fe40c9364)
   
 -  Alarms in CloudWatch for cost management and notifications.

   ![ooo](https://github.com/user-attachments/assets/960451b8-6e6c-4d9a-a99e-e83d3e04bc17)

			
**Tools and Technologies**:

•	**AWS Glue**: For ETL pipeline design and implementation.

•	**AWS Data Brew**: For initial data cleaning and structuring.

•	**AWS CloudWatch**: For monitoring metrics and managing costs.

•	**AWS CloudTrail**: For auditing and tracking user activities.

**Deliverables**:

•	**Processed Data**: Cleaned and structured datasets.

•	**ETL Pipelines**: Implemented pipelines for data transformation and loading.

•	**Monitoring Setup**: Dashboards and alarms for cost and activity monitoring.

**Timeline (2 days)**:

**Day 6**:

- Continue data preparation, focusing on cleaning and structuring datasets.
  
- Design and implement ETL pipelines using AWS Glue for data transformation.

- Set up replication rules for automatic backup of the building permit data.

**Day 7**:

- Set up AWS CloudWatch for performance tracking and cost management, and AWS CloudTrail for auditing and logging activities.

- Finalize the project by reviewing processed data, validating the data quality, and preparing a final report for stakeholders.



**5**. **Quality Control**

**Project Description**: Quality control involves ensuring the accuracy and reliability of the recruitment and selection data by implementing validation checks and addressing any data quality issues.

**Project Title**: Quality Control for for Building Permit Analysis

**Objective**: To ensure the integrity and accuracy of the Building Permit data through validation and error-checking processes.

**Dataset**: Data from the Vancouver Open Data Portal, including building permit records for 2023 and 2024.

**Methodology**:

•	**Data Protection**:

 - Data encrypted using AWS Key Management Service (KMS).

 - Encryption key: development-buildingandlicensing-key-sharanya used for S3 bucket data.

   ![ooo](https://github.com/user-attachments/assets/d28e4c58-4718-42a0-9ed3-2905c415b48d)

 - Encryption applied to S3 bucket folders and backup buckets.

  ![ooo](https://github.com/user-attachments/assets/8df14bc2-2ec3-47a1-964e-3132e47700e2)
   
 - 	Replication rule set for automatic data backup.
   
•	**Data Governance**:

 - 	Data managed using AWS Glue with trusted zones and quality checks.

	![ooo](https://github.com/user-attachments/assets/84328714-f9ec-40f9-8c42-4110987fca76)

 -  Checks for sensitive data and data completeness.

   ![ooo](https://github.com/user-attachments/assets/c3a36c35-8e61-40b7-8c0f-3d048a53e4a9)

**Tools and Technologies**:

•	**AWS Key Management Service (KMS)**: For data encryption.

•	**AWS Glue**: For ETL pipeline design and implementation.


<img width="227" alt="image" src="https://github.com/user-attachments/assets/0692a309-2363-4a88-b024-926eb391f5f7">



# Project 2 

**Project Objective:**

•Assess the efficiency of the university’s recruitment and selection process.

**Focus Areas:**

•Evaluate time spent on interviews across departments.

•Identify resource wastage and inefficiencies in the hiring process.

**Approach:**

•Analyze the hours dedicated to interviews in 2024.

•Investigate recruitment bottlenecks and challenges.

**Goal:**

•Propose strategies to streamline the recruitment process.

•Optimize resource usage and reduce time-to-hire.


### Project 2 :University Recruitment and Selection Process Optimization 

**1**. **Exploratory Data Analysis**
Project Description: The project analyzed the efficiency of the recruitment and selection process at UCW for the year 2024. The objective was to determine the percentage of work hours spent per interview by each department relative to the total work hours across all departments.

**Objective**: To assess how much time each department spends on interviews compared to the total time spent by all departments, helping to understand workload distribution and efficiency.

**Dataset**:

•**Source**: CSV file containing work hours and interview counts by department

•**Content**: Number of interviews and work hours spent per interview for each department

**Methodology**:

•**Formulate the Analytical Question**: What percentage of total work hours is spent on interviews by each department?

•**Data Discovery**: Data was generated in CSV format, converted to Excel, and analyzed by separating datasets for interviews and work hours.

<img width="908" alt="image" src="https://github.com/user-attachments/assets/2d99b6ea-a0b9-4822-81f9-fe76f101c421">


<img width="674" alt="image" src="https://github.com/user-attachments/assets/92edcc91-0e3d-4184-8113-ca1c1f587be2">




•**Upload and Organize Data**: Stored the cleaned data in Amazon S3 Raw folder.

![ooo](https://github.com/user-attachments/assets/34da382f-27ff-4aaf-a8b0-c822e9d151d0)

•**Run Queries**: Use AWS Athena to execute SQL queries for extracting and aggregating data.

![ooo](https://github.com/user-attachments/assets/ddff287a-1b01-49ed-bb1e-f0af1bb13fff)
   
   
**Tools and Technologie**s:

•	**Data Storage**: Amazon S3

•	**Data Analysis**: AWS Athena

**Deliverables**:

•	**Analysis Report**: Percentage of work hours spent per interview by each department

•	**Visualizations**: Bar graphs illustrating the data

**Timeline**:

**Day 1**:

- Convert CSV to Excel, upload data to Amazon S3, and create the raw folder.
  
- Organize datasets for interviews and work hours.

**Day 2**:

- Query Execution in AWS Athena
  
- Run SQL queries to extract and aggregate data based on interview hours by department.
  
- Calculate the percentage of total work hours for each department.






**2**. **Descriptive Analysis**

**Project Description**:This project involved summarizing the recruitment and selection process data, specifically analyzing the work hours spent per interview to measure efficiency across departments.

**Objective**:To summarize key metrics, such as work hours per interview, and provide a detailed overview of departmental performance in the recruitment process.

**Dataset**

**Source**: CSV file containing work hours and interview data for each department.

**Methodology**:

•**Data Summary**: Used AWS Athena to generate summaries like total work hours and average time per interview for each department.

•**Visualize Data**: Created bar graphs in Excel to visually represent the percentage of total work hours spent on interviews by each department.

<img width="375" alt="ooo" src="https://github.com/user-attachments/assets/717e75df-c7bf-4ef4-9a7f-81047f2ea3df">

**Tools and Technologies**:

•**AWS Athena**: For summarizing data.

•**AWS Glue**: For organizing and structuring the dataset.

**Deliverables**:

**Descriptive Summary Report**: Insights into work hours per interview by department.


**Timeline**:

**Day 3**:

- Generate summaries such as total work hours and average time per interview.
  
- Extract insights for each department.
  
- Create bar graphs showing the percentage of total work hours spent on interviews for each department.

**Day 4**:

- Finalize data summaries in AWS Athena.

- Review and validate the aggregated data.



**3**. **Data Wrangling** 

**Project Description**:Data wrangling involves transforming and preparing the recruitment and selection data for analysis by addressing issues such as missing values, inconsistent formats, and unnecessary columns.

**Project Title**:Data Wrangling for Recruitment and Selection Data at UCW

**Objective**:To prepare the recruitment and selection dataset for analysis by cleaning, structuring, and securing the data to ensure accuracy, consistency, and confidentiality.

**Background**:The dataset includes work hours and interview counts across different departments for 2024. Proper data wrangling is essential to ensure the dataset is reliable and ready for in-depth analysis.

**Dataset**:The dataset consists of work hours and interview data collected from various departments, provided in CSV format.

**Methodology**:
•	**Data Collection**: Data was extracted from CSV files and initially uploaded to a landing folder.

•	**Data Cleaning**: Missing values and inconsistencies were addressed by removing extraneous columns and correcting inaccuracies.

![ooo](https://github.com/user-attachments/assets/c5ac91c6-1f93-408c-bc40-eb5855b0c5b3)

•	**Data Transformation**: Standardized formats and structures, including converting date formats and renaming columns for clarity.

•	**Data Structuring**: Aggregated data by department and summarized key metrics to prepare it for analysis.

•	**Data Storage**: Cleaned and transformed data was moved to curated and trusted folders in Amazon S3.

![ooo](https://github.com/user-attachments/assets/f7187ebe-c951-42ab-a93a-32ade60b6889)


•       **Data Pipeline Design and Implementation**: Creation of ETL pipelines using AWS Glue to process and transform the data

![ooo](https://github.com/user-attachments/assets/40fc1019-c236-4096-9801-552e6fed3128)


**Tools and Technologies**:

•	**AWS Glue**: For ETL processes, including cleaning and transforming data.

•	**Amazon S3**: For storing and managing encrypted data.

**Deliverables**:

•	**Cleaned Data**: Dataset with missing values addressed, formats standardized, and unnecessary columns removed.

•	**Structured Data**: Well-organized dataset ready for analysis.



**Timeline**:

**Day 5**:

- Address missing values and inconsistencies.
  
- Standardize formats, remove unnecessary columns, and rename columns for clarity.
  
- Organize data by department and summarize key metrics for analysis.

**Day 6**:

- ETL Pipeline Design
  
- Set up ETL pipelines using AWS Glue for data transformation.
  



**4**.. **Quality Control**

**Project Description**: Quality control involves ensuring the accuracy and reliability of the recruitment and selection data by implementing validation checks and addressing any data quality issues.

**Project Title**: Quality Control for Recruitment and Selection Data at UCW

**Objective**: To ensure the integrity and accuracy of the recruitment and selection data through validation and error-checking processes.

**Dataset**: The dataset includes work hours and interview counts for different departments for the year 2024.

**Methodology**:

•	**Data Validation**: Conducted validation checks to ensure data accuracy, including cross-referencing with source data and checking for discrepancies.

•	**Error Detection**: Identified and corrected errors in the dataset, such as outliers, inconsistencies, and data entry mistakes.

•	**Data Quality Metrics**: Established metrics for data quality, including completeness, accuracy, and consistency, and applied these metrics to the dataset.

•	**Data Protection**: Data encryption was applied using AWS Key Management Service (KMS) to secure data both in primary and backup storage locations.

![ooo](https://github.com/user-attachments/assets/84e01dc8-6712-4e9a-9857-b177e2d193ce)


![ooo](https://github.com/user-attachments/assets/f2d7f281-11c5-4545-ad6f-61f88982b478)


•       **Data Governance**: Applied data quality checks using AWS Glue, including detecting and masking sensitive information and evaluating data quality with completeness rules.

![ooo](https://github.com/user-attachments/assets/de880380-5511-4c01-bf7f-2ee31dc6b05a)


•	**Ongoing Monitoring**: Implemented processes for ongoing data quality monitoring to ensure continued accuracy and reliability.

<img width="959" alt="qwee" src="https://github.com/user-attachments/assets/e0dc47f2-65c3-45b8-a8cc-11de69197013">


**Tools and Technologies**:

•	**AWS Glue**: For data validation and quality checks during ETL processes.

•	**AWS Key Management Service (KMS)**: For managing encryption keys.

•	**AWS Athena**: For running queries to detect anomalies and ensure data integrity.

**Deliverables**:

•	**Validated Data**: Data that has undergone validation checks and error corrections.

•	**Quality Reports**: Reports detailing data quality metrics and any issues addressed.

•	**Encrypted Data**: Data protected by encryption keys throughout its lifecycle.

•	**Backup and Replication**: Consistent data protection across primary and backup storage.

•	**Governance Compliance**: Data meets quality standards and governance guidelines.

**Timeline**:

**Day 7**:

- Validate the dataset by cross-referencing with the source data.
  
- Detect and correct any errors or inconsistencies using AWS Glue and AWS Athena.
  
- Implement monitoring tools like AWS CloudWatch for continuous data quality control.
  
- Apply encryption using AWS KMS for data protection and back up the data in Amazon S3.
  
- Prepare a quality control report summarizing the validation checks and any errors addressed.
