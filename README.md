# Bootcamp_Learning
# Data Technician Portfolio  
**Munro Hocking**

# Week 1 Workbook - Introduction to Data and Excel
## Overview
This repository documents my practical work and learning outcomes from the **JustIT Data Technician course (November 2025)**.  
It demonstrates my understanding of **data protection legislation**, **Excel-based data analysis**, **pivot tables**, **functions**, **data visualisation**, and **business communication**.

The portfolio reflects hands-on experience with real-world datasets, analytical techniques, and professional data handling practices.

---

## Skills Demonstrated
- Data protection & regulatory compliance (UK)
- Microsoft Excel (Tables, Functions, Pivot Tables)
- Data analysis & summarisation
- Data categorisation using logical functions
- Data visualisation & reporting
- Business communication & presentation skills
- Stakeholder-focused insight delivery

---

## Data Protection & Legal Frameworks
Understanding and complying with data legislation is critical when working with customer and organisational data.

### Data Protection Act
- Ensures secure and lawful handling of personal data
- Protects individuals from identity theft and fraud
- Requires transparency on data collection and usage

**Impact:**  
Strict controls on storage, access, and usage of data.

**Risk of Breach:**  
Large fines, reputational damage, and potential business closure.

---

### GDPR
- Governs how organisations collect, store, and process personal data
- Applies to all organisations handling personal data in the UK

**Example:**  
Retailers providing privacy notices when collecting customer data.

**Risk of Breach:**  
Legal action, financial penalties, and operational shutdown.

---

### Freedom of Information Act
- Grants public access to information held by public authorities

**Impact:**  
Requires accurate documentation and transparency in public-sector data handling.

---

### Computer Misuse Act
- Criminalises unauthorised access or modification of computer systems

**Impact:**  
Strict access control and authorisation requirements when working with data.

---

## Excel Data Analysis Tasks

### Day 2 – Retail Sales Dataset
**Techniques Used:**
- Converted raw data into structured Excel tables
- Sorted data by age (largest to smallest)
- Calculated:
  - Total commission using `SUM`
  - Average commission using `AVERAGE`
- Applied:
  - `MAX`
  - `SUMIF`
  - Pivot Tables for revenue analysis

**Outcome:**  
Improved ability to summarise large datasets and extract business-relevant metrics.

---

## Pivot Tables & Advanced Functions

### Bike Sales Analysis
- Built pivot tables to analyse sales by:
  - Country
  - Market
  - Age group
  - Gender

**Key Findings:**
- Most profitable country: **Australia**
- Most profitable age group: **Young Adults**
- Most profitable gender: **Female**

---

### County & Product Sales Analysis
**Dataset:**  
Sales performance across English counties.

**Techniques Used:**
- Pivot Tables (County × Product)
- `SWITCH` function to categorise sales volume:
  - High (>600)
  - Medium (300–600)
  - Low (<300)

```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
```

# Data Technician Portfolio – Week 2  
**Data Visualisation & Business Intelligence**  
**Author:** Munro Hocking  

---

## Overview
This repository documents my **Week 2 coursework** from the JustIT Data Technician programme.  
The focus of this week was on **data visualisation tools**, **dashboard design**, **trend analysis**, and **business intelligence reporting** using **Tableau** and **Power BI**.

---

## Tools & Technologies
- Tableau (Public, Desktop, Creator, Explorer, Viewer)
- Power BI Desktop
- Excel / CSV datasets
- Data visualisation best practices
- Business insight communication

---

## Tableau Platform Comparison

### Tableau Versions Overview
| Version | Purpose | Key Features | Limitations |
|------|-------|------------|------------|
| **Tableau Public** | Free public data visualisation | Static Excel/CSV files, public dashboards | No private saving, public-only, 15M row limit |
| **Tableau Desktop** | Professional analytics | Full data source support, private workbooks | Paid license |
| **Tableau Creator** | Enterprise analytics | Desktop + Prep, data cleaning, collaboration | Paid license |
| **Tableau Explorer** | Data exploration | Edit published dashboards | No raw data access |
| **Tableau Viewer** | Dashboard consumption | View and interact with dashboards | No editing |

### Tableau Public – Limited Functionality
- All dashboards are **public**
- No live database connections
- No custom extensions
- Cannot save work privately
- Intended for learning and portfolio sharing

---

## Dashboard Creation – EMSI Job Change (UK)
**Objective:**  
Create a Tableau dashboard using the EMSI Job Change UK dataset.

**Visuals Included:**
- Bar chart showing **percentage change**
- UK map highlighting **key impacted cities**

**Outcome:**  
Demonstrated geographic and comparative data visualisation for workforce analysis.

---

## Spotify Dataset Analysis

### Objective
Identify trends and insights that could support organisational decision-making using Spotify data.

### Key Findings
- Average song duration by genre
- Average danceability per genre
- Top 50 artists visualised using a **bubble chart**
- Top 20 songs based on live performance metrics
- Genre popularity displayed using a colour-coded table

**Business Value:**  
Supports music industry decisions around content production, marketing, and audience targeting.

---

## Health Dataset Analysis (NHS Context)

### Objective
Analyse health data to uncover trends that could support NHS decision-making.

### Key Insight
- Liver cancer rates are increasing **more significantly in men than women**

### Reflection
- Potential correlation with alcohol consumption guidelines
- Data can inform:
  - Preventative healthcare campaigns
  - Policy review
  - Targeted health interventions

---

## Power BI Labs

### Lab 1 – Get Data in Power BI Desktop
- Imported datasets
- Established data model
- Validated data structure

---

### Lab 2 – Load Transformed Data
- Applied data transformations
- Cleaned and shaped data using Power Query
- Prepared datasets for reporting

---

### Lab 8 – Design a Power BI Report
- Built structured report layouts
- Applied visuals for clarity and insight
- Focused on readability and business relevance

---

## Key Learnings
- Comparative understanding of Tableau products
- Practical dashboard design principles
- Insight extraction from large datasets
- Translating visual analysis into business-focused narratives
- Awareness of tooling and platform constraints

---

## Professional Relevance
This work demonstrates:
- Data visualisation literacy
- Analytical thinking
- Tool evaluation and selection
- Stakeholder-focused reporting
- Honest documentation of technical blockers

---

## Next Steps
- Expand Power BI work using Power BI Service
- Publish Tableau dashboards publicly
- Integrate SQL-based datasets
- Align insights with marketing and business analytics use cases

---

*This repository represents applied coursework completed during Week 2 of the JustIT Data Technician programme.*


# Data Technician Portfolio – Week 3  
**Databases & SQL Fundamentals**  
**Author:** Munro Hocking  

---

## Overview
This repository documents my **Week 3 coursework** from the JustIT Data Technician programme.  
The focus of this week was on **database theory**, **relational design**, and **SQL querying**, including joins, filtering, aggregation, and practical database analysis.

The work demonstrates both **conceptual understanding** and **applied SQL skills**.

---

## Core Skills Demonstrated
- Database design principles
- Primary, foreign, and secondary keys
- Relational vs non-relational databases
- Entity relationships (1:1, 1:M, M:M)
- SQL querying (SELECT, WHERE, JOIN, GROUP BY)
- Aggregate functions
- Real-world database design
- Analytical problem solving using SQL

---

## Database Fundamentals

### Keys & Relationships

**Primary Key**  
A unique identifier for each record in a table. Prevents duplicate and NULL values, ensuring data integrity.

**Secondary Key**  
An alternate key used to optimise queries and searches but not designated as the primary identifier.

**Foreign Key**  
A field that references the primary key of another table, creating a relationship between tables.

---

### Relationship Examples
- **One-to-One:** Husband ↔ Wife  
- **One-to-Many:** Mother → Children / School → Pupils  
- **Many-to-Many:** Actor ↔ Film / Recipe ↔ Ingredients  

---

## Relational vs Non-Relational Databases

### Relational Databases
- Structured tables (rows and columns)
- Fixed schema
- Strong relationships via keys
- Ideal for consistent, structured data

**Examples:** MySQL, PostgreSQL, SQL Server

---

### Non-Relational (NoSQL) Databases
- Flexible data structures
- Schema-less or semi-structured
- Highly scalable
- Suited to fast-changing or unstructured data

**Best Used For:**
- Social media posts
- User profiles
- Logs and sensor data
- Product catalogues

---

## SQL Querying & Filtering
The following SQL concepts were practiced using real datasets:

- Logical operators: `AND`, `OR`
- Filtering: `WHERE`, `IN`, `NOT`
- Aggregates:
  - `SUM`
  - `AVG`
  - `MAX`
  - `MIN`
  - `COUNT`

---

## SQL JOIN Types

### INNER JOIN
Returns only rows with matching values in both tables.

**Use Case:**  
Employees who have assigned managers.

---

### LEFT JOIN
Returns all rows from the left table and matching rows from the right.

**Use Case:**  
All employees, including those without managers.

---

### RIGHT JOIN
Returns all rows from the right table and matching rows from the left.

**Use Case:**  
All managers, even if they have no assigned employees.

---

### FULL JOIN
Returns all rows from both tables, filling unmatched rows with NULLs.

**Use Case:**  
Complete relationship mapping between two datasets.

---

### SELF JOIN
Joins a table to itself.

**Use Case:**  
Employee-manager hierarchies within a single table.

---

### CROSS JOIN
Returns all possible combinations of rows between tables.

**Use Case:**  
Generating all possible pairings or combinations.

---

## Database Design Case Study – Retail Shop

### Business Scenario
A small corner shop selling groceries and household items requires a database to manage:
- Inventory
- Sales
- Customers
- Loyalty programme

---

### Schema Design
**Core Tables:**
- `Products`
- `Customers`
- `Sales`
- `Suppliers`

**Key Relationships:**
- Products → Sales (One-to-Many)
- Customers → Sales (One-to-Many)

---

### Example SQL – Database & Tables
```sql
CREATE DATABASE CornerShop;

CREATE TABLE Products (
  ProductID INT PRIMARY KEY,
  ProductName VARCHAR(100),
  Category VARCHAR(50),
  Price DECIMAL(10,2),
  Inventory INT,
  SupplierID INT,
  FOREIGN KEY (SupplierID) REFERENCES Supplier(SupplierID)
);
```

# Data Technician Portfolio – Week 5

## Overview
This repository documents my learning and practical work completed during **Week 5 of the Data Technician programme**.  
The focus of this week was **cloud computing fundamentals, data legislation, Microsoft Azure services, and data analytics concepts**, culminating in a real-world business case proposal.

---

## Key Skills Demonstrated
- Cloud computing fundamentals (IaaS, PaaS, SaaS)
- Public, private, hybrid, and community cloud models
- UK data protection and cyber legislation
- Azure data storage and analytics services
- Relational and non-relational data concepts
- Data modelling and warehouse design
- Data security, compliance, and governance
- Business-focused data solution design

---

## Cloud Computing Fundamentals

### What Cloud Computing Enables
- On-demand access to computing resources
- Scalable storage and processing power
- Reduced infrastructure costs
- Secure, remote access to data and applications

### Business Benefits
- Pay-as-you-go pricing
- Improved reliability and availability
- Faster deployment and scalability
- Enhanced collaboration and disaster recovery

### Major Cloud Providers
| Provider | Analytics | Database Storage | Global Network |
|--------|-----------|------------------|---------------|
| AWS    | Yes       | Yes              | Yes           |
| Azure  | Yes       | Yes              | Yes           |
| GCP    | Yes       | Yes              | Yes           |

---

## Cloud Service Models

### Infrastructure as a Service (IaaS)
- Virtual machines, storage, and networks
- Full control over OS and applications  
**Use Case:** Migrating on-prem servers to the cloud

### Platform as a Service (PaaS)
- Managed runtime and development environments  
**Use Case:** Building and deploying web applications

### Software as a Service (SaaS)
- Fully managed applications accessed via browser  
**Use Case:** Microsoft 365, Google Workspace, Salesforce

---

## Cloud Deployment Models

- **Public Cloud:** Cost-effective, scalable, shared infrastructure  
- **Private Cloud:** Dedicated environment for sensitive data  
- **Hybrid Cloud:** Mix of on-prem and public cloud resources  
- **Community Cloud:** Shared infrastructure for regulated sectors

---

## UK Data Laws & Cyber Legislation

### Key Legislation Covered
- Computer Misuse Act 1990
- Police and Justice Act 2006
- Data Protection Act 2018
- GDPR
- Copyright, Designs and Patents Act 1988
- Consumer Rights Act 2015

### Core Topics
- Unauthorised access and system modification
- Copyright infringement and software piracy
- Employee and customer data handling
- Legal responsibilities of organisations

---

## Azure Practical Labs

### Completed Labs
- Explore relational data in Azure
- Explore non-relational data in Azure
- Explore data analytics in Azure

> Note: Some lab tasks were partially completed due to persistent virtual machine errors despite multiple resets and troubleshooting attempts.

---

## Business Case Study  
### *Paws & Whiskers – Azure Data Transformation Proposal*

### Business Problem
A growing pet shop relying on manual spreadsheets for:
- Sales data
- Customer information
- Inventory tracking

### Proposed Azure Solution
#### Data Storage
- **Azure Blob Storage** – raw and historical data
- **Azure SQL Database** – structured transactional data

#### Data Analytics
- **Azure Synapse Analytics** – sales and inventory trends
- **Azure Machine Learning** – customer behaviour analysis

#### Data Integration
- **Azure Data Factory** – automated ETL pipelines

---

## Data Modelling Approach

### Data Types
- Customer demographics
- Transaction records
- Inventory and product data
- Product categorisation

### Modelling Strategy
- Relational model with primary and foreign keys
- Star schema for analytical workloads
- Fact tables for sales data
- Dimension tables for customers, products, and time

---

## Data Security & Compliance

- GDPR and DPA 2018 compliance
- Role-Based Access Control (RBAC)
- Encryption at rest and in transit
- Azure Active Directory integration
- PCI DSS considerations for payment data

---

## Additional Considerations

### Backup & Disaster Recovery
- Azure Backup
- Azure Site Recovery
- Multi-region redundancy

### Data Visualisation
- Power BI dashboards for real-time insights
- Secure, role-based reporting access

### Scalability
- Azure’s elastic, pay-as-you-go architecture
- Designed to support long-term business growth

---

## Conclusion
This project demonstrates my ability to:
- Apply cloud and data concepts to real-world business scenarios
- Design compliant, scalable Azure data solutions
- Understand legal, technical, and business requirements
- Translate raw data into actionable insights

---

## Technologies & Tools
- Microsoft Azure
- Azure SQL Database
- Azure Blob Storage
- Azure Synapse Analytics
- Azure Data Factory
- Azure Machine Learning
- Power BI

# Data Technician Portfolio – Week 6  
## Python Programming & Data Analysis with Pandas

## Overview
This repository documents my **Week 6 Data Technician coursework**, focusing on **Python programming, data manipulation with Pandas, and exploratory data analysis**.  
The work demonstrates core programming logic, data transformation techniques, aggregation, and preparation of datasets for analysis and reporting.

---

## Skills Demonstrated
- Python fundamentals
- Control flow and logic (FizzBuzz)
- Pandas DataFrame operations
- Data cleaning and manipulation
- Indexing and slicing
- Aggregation and grouping
- Pivot tables and advanced transformations
- Data export and basic visualisation
- Exploratory data analysis (EDA)

---

## Python Programming Fundamentals

### FizzBuzz Exercise
Implemented the classic **FizzBuzz** logic in Python:

- Iterates through numbers 1–100
- Prints:
  - `"fizz"` for multiples of 3
  - `"buzz"` for multiples of 5
  - `"fizzbuzz"` for multiples of both
  - The number otherwise

**Skills demonstrated:**
- Loops
- Conditional statements
- Modulus operator
- Clean, readable Python syntax

---

## Data Analysis with Pandas

### Dataset: `student.csv`

### Exercise 1 – Loading & Exploring Data
- Loaded CSV data into a Pandas DataFrame
- Displayed the first five rows
- Retrieved DataFrame structure and metadata
- Generated summary statistics

**Key concepts:**
- `read_csv()`
- `head()`
- `info()`
- `describe()`

---

### Exercise 2 – Indexing & Slicing
- Selected individual and multiple columns
- Filtered rows using conditions
- Extracted subsets of data

**Key concepts:**
- Column selection
- Boolean indexing
- Row slicing

---

### Exercise 3 – Data Manipulation
- Added derived columns
- Renamed existing columns
- Removed unnecessary columns

**Key concepts:**
- Feature engineering
- Column renaming
- DataFrame mutation

---

### Exercise 4 – Aggregation & Grouping
- Calculated mean scores per class
- Counted students per group
- Analysed performance by gender

**Key concepts:**
- `groupby()`
- Aggregation functions
- Summarising datasets

---

### Exercise 5 – Advanced Operations
- Created pivot tables
- Applied conditional logic to create grades
- Sorted data by performance

**Key concepts:**
- `pivot_table()`
- Conditional column creation
- Sorting and ranking

---

### Exercise 6 – Exporting Data
- Exported transformed datasets to CSV format

**Key concepts:**
- Data persistence
- Reproducible data workflows

---

### Exercise 7 – Visualisation (Optional)
- Explored basic data visualisation techniques to identify trends and distributions

---

## Exploratory Data Analysis Project  
### Dataset: GDP (Nominal) per Capita

### Day 4 – Task 1
- Imported GDP per capita dataset into Pandas
- Inspected dataset structure
- Selected relevant columns for analysis

### Day 4 – Task 2
- Completed guided Jupyter Notebook activities
- Explored GDP trends by country and region
- Applied Python and Pandas skills creatively to additional datasets

---

## Tools & Technologies
- Python
- Pandas
- Jupyter Notebook
- CSV datasets

---

## Learning Outcomes
By completing this work, I demonstrated the ability to:
- Write clean and logical Python code
- Manipulate and analyse real-world datasets
- Transform raw data into structured, analysable formats
- Apply analytical thinking to explore trends and patterns
- Prepare datasets for reporting and visualisation

---

## Next Improvements
- Add matplotlib / seaborn visualisations
- Refactor notebooks into reusable Python scripts
- Apply statistical analysis to datasets
- Build a small end-to-end data project using multiple datasets

---

## Author
**Munro Hocking**  
Data Technician Trainee
