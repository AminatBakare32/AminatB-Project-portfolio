# Project UCW-portfolio  
# **Remote Work Analysis and Optimization Framework**

## **Overview**
This project is designed to analyze and optimize remote work practices by leveraging AWS cloud infrastructure and data engineering methodologies. It focuses on three critical aspects:
1. **Employee Eligibility**: Who qualifies for remote work?
2. **Performance Tracking**: How does remote work impact productivity?
3. **Resource Allocation**: Is equipment distribution aligned with employee needs?

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

