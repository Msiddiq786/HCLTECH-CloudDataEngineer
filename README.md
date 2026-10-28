# Cloud Data Engineering Portfolio

**SQL • Python • PySpark • Linux • AWS • Azure**

A hands-on Cloud Data Engineering portfolio documenting database design, data processing, analytics, cloud security, workflow orchestration, monitoring, and troubleshooting.

This repository organizes my Cloud Data Engineer assessment work into six sections, with source code, scripts, configuration examples, implementation notes, and screenshots where available.

---

## Overview

Modern data engineering involves collecting, validating, transforming, securing, and analyzing data across multiple systems. This portfolio demonstrates my learning and practical work across SQL, Linux, PySpark, Amazon Web Services (AWS), AWS Step Functions, and Microsoft Azure.

The repository follows a structured, question-by-question approach, making the work easy to navigate, review, and reproduce.

## Technology Stack

| Category | Technologies and Concepts |
|---|---|
| Database and Analytics | SQL, MySQL, joins, subqueries, window functions, indexing |
| Programming | Python, PySpark |
| Operating Systems | Linux, Bash scripting, file permissions, log analysis |
| Data Processing | DataFrames, CSV processing, data cleaning, aggregation, joins |
| AWS Storage and Security | Amazon S3, IAM, bucket policies, encryption |
| AWS Compute and Monitoring | EC2, AWS Lambda, Amazon CloudWatch |
| AWS Orchestration | AWS Step Functions, Amazon SNS, event-driven processing |
| Microsoft Azure | Azure Data Lake Storage Gen2, Microsoft Entra ID, Azure RBAC |
| Azure Integration and Networking | Azure Data Factory, Virtual Machines, Network Security Groups, routing |
| Development and Version Control | Git, GitHub, Visual Studio Code |

## Repository Structure

```text
HCLCloudDataEngineer/
│
├── README.md
├── .gitignore
│
├── Documents/
│   └── Assessment documentation
│
├── Section-A/
│   └── SQL database design and analytics
│
├── Section-B/
│   └── Linux commands and Bash scripts
│
├── Section-C/
│   └── PySpark data engineering programs
│
├── Section-D/
│   └── AWS cloud services and security
│
├── Section-E/
│   └── AWS Step Functions workflows
│
└── Section-F/
    └── Microsoft Azure solutions
```

The structure above describes the logical organization. Refer to the actual folders for the files currently available in the repository.

## Section A — Advanced SQL

**Questions 1–3 | Database Design, Analytics, and Query Optimization**

This section covers relational database design and business-oriented SQL analysis.

Topics include:
- Creating databases and tables with primary keys, foreign keys, and constraints.
- Inserting and querying employee and department records.
- Joining employees, departments, and reporting managers.
- Finding employees earning above their department's average salary.
- Calculating the second-highest distinct salary.
- Ranking employees within departments using window functions.
- Calculating product revenue and monthly revenue trends.
- Optimizing date filters for potential index usage.
- Understanding execution plans, composite indexes, and duplicate detection.

**Key skills:** SQL programming, relational modeling, analytical queries, and query performance concepts.

## Section B — Linux and Bash Scripting

**Questions 4–6 | Log Analysis, Permissions, and Automation**

This section focuses on common Linux administration and troubleshooting tasks.

Topics include:
- Searching, filtering, and counting application log errors.
- Extracting errors by date and analyzing hourly error patterns.
- Creating Linux groups and setting file ownership and permissions.
- Investigating CPU, memory, and disk utilization.
- Finding files larger than a specified size.
- Building a timestamped backup script with argument validation and error handling.

**Key skills:** Linux command-line operations, file security, system troubleshooting, and Bash automation.

## Section C — PySpark Data Engineering

**Questions 7–9 | DataFrames, Data Cleaning, and Joins**

This section explores distributed data processing using PySpark.

Topics include:
- Creating employee DataFrames with appropriate schemas.
- Filtering, selecting, and deriving columns.
- Calculating annual salaries and department-level statistics.
- Reading CSV files with explicit schemas.
- Identifying duplicate transactions and handling missing values.
- Converting date fields and handling invalid dates.
- Calculating revenue and aggregating results by product.
- Joining customer and order datasets.
- Identifying customers without orders and calculating order value by city.
- Understanding broadcast joins, transformations, and actions.

**Key skills:** PySpark, data quality, transformation logic, aggregations, and data integration.

## Section D — AWS Cloud Services

**Questions 10–12 | Storage Security, Monitoring, and Event-Driven Processing**

This section documents AWS services used to design secure and reliable cloud solutions.

Topics include:
- Creating Amazon S3 buckets with Block Public Access enabled.
- Designing least-privilege IAM policies for object access.
- Verifying access restrictions and understanding encryption at rest.
- Troubleshooting EC2 instance health and application connectivity.
- Understanding security groups, route tables, and network access.
- Configuring CloudWatch alarms for high CPU utilization.
- Investigating resource utilization and application failures.
- Triggering Lambda processing when files are uploaded to S3.
- Defining input/output permissions, logs, and duplicate-processing safeguards.

**Key skills:** Cloud storage, IAM security, monitoring, server troubleshooting, and event-driven architecture.

## Section E — AWS Step Functions

**Questions 13–14 | State Machine Design and Implementation**

This section covers workflow orchestration for data processing.

Topics include:
- Designing sequential validation, transformation, calculation, and storage steps.
- Routing valid and invalid inputs with Choice states.
- Handling transient failures with Retry policies.
- Handling permanent failures with Catch transitions.
- Invoking Lambda functions and supported AWS services.
- Passing JSON input and output between states.
- Recording failures and sending notifications.
- Testing successful and failed executions.
- Reviewing execution history to troubleshoot workflows.

**Key skills:** Workflow design, Amazon States Language (ASL), error handling, retries, and cloud automation.

## Section F — Microsoft Azure

**Questions 15–17 | Data Lake Security, VM Troubleshooting, and Data Integration**

This section covers Azure storage, networking, and data ingestion concepts.

Topics include:
- Configuring Azure Data Lake Storage Gen2 with hierarchical namespace enabled.
- Organizing datasets in containers and date-based directories.
- Managing data access using Microsoft Entra ID, Azure RBAC, and access control lists.
- Verifying that unauthorized users cannot access data.
- Troubleshooting Azure Virtual Machine connectivity.
- Reviewing VM states, Network Security Group rules, subnet configuration, and routes.
- Using secure administrative access methods such as Azure Bastion.
- Designing data pipelines with Azure Data Factory.
- Copying CSV data into Data Lake Storage Gen2.
- Handling malformed records and missing values.
- Monitoring pipeline execution and validating data completeness.

**Key skills:** Azure storage, identity and access management, network troubleshooting, and cloud data integration.

---

## Learning Outcomes

Through this assessment and portfolio, I aim to demonstrate the ability to:

- Design relational databases and write analytical SQL queries.
- Process, clean, transform, and aggregate structured datasets.
- Automate operational tasks using Linux and Bash.
- Apply least-privilege access and cloud data protection principles.
- Monitor infrastructure and investigate operational failures.
- Design event-driven processing and orchestrated data workflows.
- Integrate data into cloud-based storage and analytics environments.
- Document implementations and communicate technical decisions clearly.

## How to Explore This Repository

1. Open the section relevant to the topic you want to review.
2. Read the associated code, configuration, or implementation notes.
3. Review the provided screenshots and outputs, where available.
4. Follow the execution instructions included with individual files.
5. Use sample datasets and your own authorized cloud environment when testing.

### Tools and Environment

Requirements vary by section:

- **SQL:** A compatible database system, such as MySQL.
- **Linux and Bash:** A Linux environment or compatible shell.
- **PySpark:** Python, Java, and PySpark configured appropriately.
- **AWS:** An AWS account with appropriately scoped permissions.
- **Azure:** An Azure subscription with appropriately scoped permissions.

Cloud services may incur charges. Review pricing and clean up temporary resources after testing.

## Security and Responsible Usage

- Never commit cloud access keys, passwords, tokens, private keys, or database credentials.
- Use synthetic datasets or data that you are authorized to publish.
- Apply least-privilege access to cloud resources.
- Keep account identifiers and personal information out of public screenshots where possible.
- Treat architecture examples and configuration templates as starting points that require environment-specific validation.

## Implementation and Testing Status

This repository is maintained progressively, section by section.

The presence of code or documentation does not automatically imply that every solution has been executed or deployed. Testing status, sample outputs, and screenshots should reflect actual verification. Proposed designs are identified as such where applicable.

## Author

**Mohammad Siddiq**

Cloud Data Engineering | SQL | PySpark | Linux | AWS | Microsoft Azure

---

*This portfolio documents my technical learning, assessment solutions, and development of practical cloud data engineering skills.*
