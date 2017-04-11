---
layout: page
title: Dremio v. Data Prep Products

---

### Overview
Analysts and data scientists are consumers of enterprise data. The use BI tools like Tableau, Qlik, and Power BI, as well as data science languages like Python and R, enable these teams to analyze data in powerful ways. All of these tools work best when the data has been collected from the different sources, prepared for analysis, and is stored in a high-performance database for access. 

Data Prep tools have emerged to help companies perform the work of sourcing and preparing their data for analysis. Companies use these tools as an integral part of their <a href="#">Data Pipelines.</a> In this article we compare Data Prep tools to Dremio, a new approach to data analytics that integrates several critical functional areas, including Data Prep.

### What is Data Prep?
Data Prep, also known as Data Wrangling, is a new class of software products designed to help companies improve the quality of their data for analytics. The idea of improving data quality isn’t new. What is new with Data Prep is allowing users to make decisions about how to improve data based on the data itself rather than relying on metadata. 

ETL tools are another class of products that perform a similar function. There are many more ETL tools, and they have been around much longer. ETL tools differ from Data Prep in that they tend to work from metadata definitions instead of data samples. They are also different in that they are exclusively designed for IT users, whereas Data Prep tools are designed for IT users as well as technical users within a business function. 

Data Prep is an important part of an end-to-end Data Pipeline. Data Pipelines typically cover multiple steps, and involve several technologies. In a Data Pipeline, data is:

- **Sourced.** Access the data from one or more systems.
- **Joined.** Combine the data from multiple sources.
- **Extracted.** Extract specific data elements embedded in other fields.
- **Standardized.** Make values consistent across all the data, such as colors, sizes, codes, units of measure, and more.
- **Corrected.** Correct mistakes, or detect corrupt data.
- **Loaded.** Load the cleansed data into a destination system
- **Automated.** Make the process run on a schedule or continuously.

Data Prep is especially important for Joining, Extracting, Standardizing, and Correcting data. These tools typically run on a centralized server where they are accessed through a browser, or on an individual’s desktop. Some BI tools include basic data prep capabilities, but these are usually only suitable for small datasets that fit on the desktop computer.

### What is Dremio?
Dremio is a new and unique approach to data analytics that let’s you do more with your data, with less effort, and at an end-to-end speed never before possible. Unlike Data Prep products, Dremio is a comprehensive solution that is designed for business users to conduct end-to-end analytics from any data source, at any scale, for use with any BI or data science tool. While Data Prep is focused on one step of the process, Dremio allows users to perform data preparation tasks as part of a larger comprehensive process that includes:

- **Self Service Data** The ability for business users to discover, curate, accelerate, and share enterprise data from an enterprise data catalog.
- **Distributed Query Execution.** The ability to process analytical queries on any data source, including relational and non-relational systems, as well as cloud sources.
- **Data Acceleration.** The ability to transparently optimize data and queries for interactive analysis across all BI and data science tools.
- **Data Lineage.** The ability to understand and analyze the full lineage of data as it is being queried, joined, transformed, and shared across different datasets, systems, and analytical tools.
					
Instead of cobbling together products from multiple vendors, Dremio lets you start seeing value in minutes, and for the first time makes all of your data easily accessible to IT as well as business users.

Analysts connect to Dremio with their favorite BI tool (Tableau, Power BI, Qlik Sense, etc.) or language (SQL, R, Python, etc.). To an analyst, all data appears as tables, no matter what system it came from, with the full power of SQL to join, aggregate, transform and sort data across one or more data sources. Dremio is entirely transparent to your users. And Dremio’s autonomous cache accelerates your data so that no matter the size or data source, your data feels small, approachable, and instantaneous. Unlike cubes that only work for a small set of pre-defined queries, Dremio makes all your SQL fast, including ad-hoc row-level queries.

### Terminology & Concepts

Data Source
: Data is created or captured in systems such as RDBMS, file systems, 3rd party apps, Hadoop, and NoSQL.

Join
: Combining data from multiple sources, including lookup values such as industry codes. All sources must include common keys that are explicitly defined in the data, or can be extracted or calculated from the data

Transformation
: Converting data from the way it is represented in its source to a different structure, including converting data types, extracting values from fields, combining multiple fields together, and filtering records based on Boolean, range, text search, regular expression, and other conditions.

Calculate
: Calculating new values based on explicit or implicit values in the data sources, such as standard deviation, k-means, or IRR.

Aggregate
: Summarizing data using measures such as MIN, MAX, AVG, COUNT based on one or more dimensions of the data.

Load
: Load the data into its final destination, usually an RDBMS, data warehouse, or Hadoop.

### Feature Comparison


{:.feature-table}
|---
|| Dremio | Data Prep
|:-:|:-:|:-:|
Read data from many sources (RDBMS, file system, Hadoop, NoSQL, etc) | **Yes** | **Yes**
Push optimized queries into data sources via native connectors, minimizing impact on data source operations | **Yes** | ~~No~~
Transform data using SQL, regular expressions, nested data operators, etc | **Yes** | **Yes**
Calculate new values from discrete fields or extracted values using a range of math operators | **Yes** | **Yes**
Aggregate data with many measures across many dimensions | **Yes** | **Yes**
Apply transformations, calculations, and aggregations in-memory as a dynamic operation expressed as a SQL query | **Yes** | ~~No~~
Load data into destination systems | ~~No~~, Dremio provides dynamic access to all data instead of loading into a new destination system, accelerating time to insight, and minimizing cost of ownership | **Yes**


### What Are Common Use Cases for Dremio?

Dremio lets you reimagine your end to end analytical processes, with a solution that makes your data engineers and your analysts more productive on day 1. Instead of using Data Prep, ETL, and custom scripts to move your data between different environments, Dremio connects to your data sources directly, and automatically creates a highly optimized cache that makes even your biggest data feel small, approachable, and interactive. Dremio supports all your favorite BI tools, and advanced languages like Python/Pandas, R, and Apache Spark.

{:.blue}
**Customers use Dremio in a wide range of applications. Here are some popular first projects:**

- **BI on Non-Relational Data.** Fast access to Elasticsearch, MongoDB, HDFS, S3, plus joins to relational data.
- **Autonomous Data Acceleration.** Make PB-scale queries fast, without cubes or aggregation tables.
- **Self-Service Data.** Empower IT and analysts to discover, curate, accelerate, and share data.
- **The Data Graph.** Lineage of data flows, data reshaping, sharing, and access patterns
- **BI on Non-Relational Data.** Fast access to Elasticsearch, MongoDB, HDFS, S3, plus joins to relational data.
- **Autonomous Data Acceleration.** Make PB-scale queries fast, without cubes or aggregation tables.
- **Self-Service Data.** Empower IT and analysts to discover, curate, accelerate, and share data.
- **The Data Graph.** Lineage of data flows, data reshaping, sharing, and access patterns

### Want to Learn More?
CTA - gate to access white paper or recorded webinar

- Bi/olap  on hadoop
- Data prep
- Data warehouse
- Etl 
- Data virtualization
- Sql on hadoop



