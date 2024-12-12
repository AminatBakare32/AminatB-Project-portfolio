# Project portfolio  
Overview of three projects
# **Remote Work Analysis and Optimization Framework** -1

## **Overview**
This project is designed to analyze and optimize remote work practices by leveraging AWS cloud infrastructure and data engineering methodologies. It focuses on three critical aspects:
1. **Employee Eligibility**: Who qualifies for remote work?
2. **Performance Tracking**: How does remote work impact productivity?
3. **Resource Allocation**: Is equipment distribution aligned with employee needs?
Performed the descriptive, exploratory, and diagnostic analysis of this project.

The framework ensures data-driven decision-making to improve productivity, resource allocation, and policy compliance.

---

## **Architecture**
### **Key Components**
- **Data Sources**:
  - **General Virtual Servers**: Employee eligibility and performance clickstream logs.
  - **Web Virtual Servers**: Resource allocation and security compliance data.
- **AWS Infrastructure**:
  - **S3 Buckets**: Stores raw, cleaned, and transformed datasets.
  - **AWS Glue**: Manages ETL workflows for data processing.
  - **CloudWatch**: Provides observability for monitoring pipeline health and logs.
  - **EFS**: Shared storage for HR resources and logs.
- **Security**:
  - **IAM Roles**: Role-based access control.
  - **Data Encryption**: Ensures data safety at rest and in transit.

For detailed architecture, refer to the following diagram:
- **Project View**:
  👉 **[AMINAT PROJECT 2.Drawio](./AMINAT%20PROJECT%202.Drawio)**
  ![image](https://github.com/user-attachments/assets/0f84024b-b5b9-4578-a58d-b32812813b68)


## **Objectives**
1. **Understand Remote Work Trends**:
   - Analyze eligibility distribution across departments and roles.
2. **Enhance Productivity**:
   - Identify productivity drivers linked to remote work practices.
3. **Optimize Resource Allocation**:
   - Assess the efficiency of equipment usage and compliance.

---

## **Datasets**
1. **Employee Eligibility Data**:
   - Fields: Employee IDs, eligibility status, departments, and roles.
2. **Performance Tracking Data**:
   - Fields: Work hours, productivity scores, login frequency, and feedback ratings.
3. **Resource Allocation Data**:
   - Fields: Equipment provided, reimbursable expenses, and security compliance metrics.

---

## **Methodology**
1. **Data Ingestion**:
   - Collect raw data from virtual servers and store it in Amazon S3 buckets.
2. **Data Cleaning**:
   - Standardize data using AWS Glue DataBrew (e.g., column naming, null value handling).
3. **ETL**:
   - Transform datasets into enriched outputs with AWS Glue pipelines.
4. **Governance, protection, and observability**:
   - Enforce role-based access control, encryption, Privacy & Quality Check, and observability.
5. **Analysis**:
   - Generate insights on eligibility, productivity, and resource allocation.

---

## **Tools and Technologies**
- **Cloud Services**:
  - AWS Glue, VPC, S3, CloudWatch, IAM, KMS and EFS.
- **Programming**:
  - SQL, JSON

---

## **Deliverables**
1. **Insights**:
   - Analysis of remote work trends and resource efficiency.
2. **Visualizations**:
   - Dashboards for eligibility, performance, and resource allocation.
3. **Scripts**:
   - Automated workflows for ingestion, ETL, and observability.
4. **Governance Reports**:
   - Understanding of remote work Policies for data governance and security compliance by Employees.
  
---
## PROJECT 2- PREDICTIVE ANALYSIS
  
  # **Credit Level Prediction: A Machine Learning Approach** 

## **Overview**
This project develops a machine learning model to classify customers into three credit levels: **Low**, **Medium**, and **High**. It supports financial institutions in improving credit approvals, optimizing credit limits, and setting interest rates, enhancing financial risk management.

---

## **Problem Statement**
The goal is to accurately classify customers into credit levels based on their demographic, financial, and transactional features. Correct classification helps institutions manage credit risk effectively and make informed financial decisions.

---

## **Dataset**
- **Records**: 10,167 customer profiles.
- **Features**: 20 attributes, including age, income, credit limit, and transaction details.
- **Categories**:
  - **Demographic**: Age, gender, education level.
  - **Financial**: Income category, credit limit.
  - **Transactional**: Total transaction amount, transaction count, and more.

---

## **Methodology**
1. **Data Preprocessing**:
   - Handled missing values (median/mode imputation).
   - Addressed outliers using trimming and capping.
   - Scaled and one-hot encoded features for consistency.
2. **Feature Engineering**:
   - Created interaction terms (e.g., utilization ratio).
   - Derived new features (e.g., average transaction amount).
3. **Modeling**:
   - Used Random Forest Classifier for its robustness and accuracy.
   - Applied k-fold cross-validation and hyperparameter tuning via Grid Search.
4. **Evaluation**:
   - Achieved **86% accuracy** with strong performance metrics (Precision: 84%-90%, Recall: 79%-92%).

---

## **Key Insights**
- Top predictors: Credit Limit, Total Revolving Balance, and Avg Utilization Ratio.
- Demographics like Age and Income Category also influenced credit risk classification.

---

## **Recommendations**
- Integrate real-time data for dynamic model updates.
- Explore advanced models (e.g., deep learning) for enhanced accuracy.
- Incorporate unstructured data (e.g., customer logs, social media) for deeper insights.

---

## **Tools and Technologies**
- **Programming**: Python (Pandas, NumPy, scikit-learn).
- **Visualization**: Matplotlib, Seaborn, Jupyter Notebooks.
- **Modeling**: Random Forest Classifier.

  
---
## PROJECT 3- # Data Wrangling for Enhanced Customer Analytics at SUPERSTORE SALES COMPANY

## Project Title
Data Wrangling for Enhanced Customer Analytics at Superstore Sales Company

## Objective
The primary goal of this project is to perform comprehensive data wrangling to prepare a robust dataset for customer analytics at the Superstore Company. By cleaning, transforming, and consolidating data from various sources, the project aims to enhance the accuracy and usability of customer data for subsequent analysis and reporting.

## Background
Superstore Company has accumulated customer data from multiple channels, including sales transactions, customer service interactions, and marketing campaigns. However, this data is often inconsistent, incomplete, or fragmented, making it challenging to derive meaningful insights. Effective data wrangling will facilitate better decision-making and more targeted marketing strategies.

## Dataset
The data wrangling process involves:
1. Sales Data: Transaction records including customer IDs, purchase amounts, product details, and timestamps.
2. Customer Information: Demographic details such as age, gender, location, and account creation date.
3. Customer Service Records: Logs of customer inquiries, complaints, and resolutions.
4. Marketing Interaction Data: Email and campaign response data, including open rates and click-through rates.

## Methodology
1. **Data Collection**:
   - Gather datasets from various sources, including internal databases and marketing platforms.
2. **Data Assessment**:
   - Identify missing values, duplicates, and inconsistencies.
3. **Data Cleaning**:
   - Remove duplicates, handle missing values, and standardize formats.
4. **Data Transformation**:
   - Derive new features and aggregate data.
5. **Data Consolidation**:
   - Merge datasets into a unified database using unique identifiers.
6. **Validation and Documentation**:
   - Conduct exploratory data analysis (EDA) and document the process.

## Tools and Technologies
- **Python** (Pandas, NumPy) for data manipulation and cleaning.
- **SQL** for data extraction and initial assessment of relational databases.
- **AWS Services**: S3, Glue, Athena, and QuickSight.
- **Visualization Tools**: Matplotlib, Seaborn, and Amazon QuickSight.
- output/sales_distribution_by_product_line

![image](https://github.com/user-attachments/assets/de30e7a1-1cdf-45d4-a043-980a1265d3ff)


The "Total Sales Distribution by Product Line" visualization highlights top-performing product lines, enabling businesses to prioritize inventory and marketing efforts effectively. High-revenue categories warrant focused strategies to sustain growth, while underperforming lines offer opportunities for targeted promotions or reevaluation. By aligning resources with revenue potential, businesses can optimize their product portfolio, improve profitability, and enhance competitiveness in the market through data-driven decision-making.

## Deliverables
1. A cleaned and transformed customer dataset ready for analysis, available in CSV format.
2. A comprehensive report documenting the data wrangling process.
3. Visualizations illustrating key data insights and validations.

## Timeline
The project will be completed within six weeks:
1. Data Collection and Assessment: Week 1-2
2. Data Cleaning and Transformation: Week 3-4
3. Consolidation, Validation, and Documentation: Week 5
4. Reporting and Visualization: Week 6
