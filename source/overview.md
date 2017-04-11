---
layout: page
title: Overview
permalink: /overview/
---

### Overview

Since the 90s, data architecture teams have distinguished between operational and analytical workloads with the terms online transactional processing (OLTP) and online analytical processing (OLAP). While the data and technologies we use for applications has evolved over the years, these terms are still very relevant today.

OLTP workloads tend to be dominated by discrete operations that read, write, update, or delete a small number of records for each transaction. These applications tend to support many concurrent operations (thousands of queries per second), with low latency (<10ms) and high availability (99.999% uptime). When these systems are down or slow, they can significantly impact the business. A good example is an ecommerce system for a popular retail site.

In contrast, OLAP workloads are dominated by queries that read large numbers of records for each operation. These queries usually involve aggregations - SUM, MIN, MAX, AVG, etc. - across several dimensions of the data. OLAP queries tend to touch orders of magnitude more data than OLTP queries as they span most or all of the records for each operation. There tend to be fewer concurrent users, and the latency requirements tend to be more relaxed when compared to OLTP systems.

![alt text here](/img/about/office-2.jpg)

### What is OLAP on Hadoop?

Many companies have embraced a Data Lake strategy for modern data analytics. In this model data from operational systems is moved to Hadoop for long term storage, processing, and analytics. Hadoop’s rich ecosystem of tools and integrations addresses a wide range of workloads through a shared resource model. Furthermore, Hadoop’s architecture and scalability allow companies to secure and centrally manage storage and compute resources of virtually any scale.

OLAP on Hadoop is a category of products that leverage Hadoop to:

- Stage raw data that has been moved to HDFS by a user-managed, external process
- Build and store data cubes that contain pre-computed measures across many dimensions of data   to improve the speed of analytical queries
- Execute queries using a distributed SQL engine running in the Hadoop cluster
- Provide proprietary BI features as part of their product, or ODBC drivers for third party BI tools.

### What is Dremio?

Dremio is a new and unique approach to data analytics that let’s you do more with your data, with less effort, and at an end-to-end speed never before possible. Unlike OLAP on Hadoop products, Dremio is a comprehensive solution that eliminates the need for complex ETL, aggregation tables, or data cubes. Instead of cobbling together products from multiple vendors, Dremio lets you start seeing value in minutes, with a user experience whose quality is unprecedented in the Hadoop market. 

Dremio seamlessly accelerates all of your data, not just the things you’ve moved to HDFS, with optimized push downs to relational and nonrelational systems like MongoDB, Elasticsearch, and S3. Dremio lets you reach your data faster, with far less effort.

Analysts connect to Dremio with their favorite BI tool (Tableau, Power BI, Qlik Sense, etc.) or language (SQL, R, Python, etc.). To an analyst, all data appears as tables, no matter what system it came from, with the full power of SQL to join, aggregate, transform and sort data across one or more data sources. And entirely transparent to your users, Dremio’s autonomous cache accelerates your data so that no matter how big it is or where it came from, it feels small, approachable, and instantaneous. Unlike cubes that only work for a small set of pre-defined queries, Dremio makes all your SQL fast, including ad-hoc row-level queries.

Dremio runs as a distributed process in your Hadoop cluster, provisioned and managed by YARN. With Dremio you can query data that’s already in HDFS, or you can query external systems directly, removing the need for ETL.

{:.blue}
Unlike OLAP on Hadoop, Dremio allows you to:

- *Run SQL on any data source.* Including optimized push downs and parallel connectivity to non-relational systems like MongoDB, Elasticsearch, S3 and HDFS.
- *Autonomously caches your data.* Using columnar, compressed Apache Arrow for efficient in-memory analytical processing, and Apache Parquet for persistence.
- *Accelerates all your BI queries.* Ad-hoc queries on row-level data as well as aggregation queries.
- *Integrated data curation.* Easy for business users, yet sufficiently powerful for your data engineers, and fully integrated into Dremio.
- *The Data Graph.* Full visibility into your data lineage, from your data sources, through transformations, joining with other data sources, and sharing with other users.

### Terminonoly & Concepts

OLTP
: Online Transaction Processing - workloads that represent high volumes of  low latency, transactional queries that create, read, update, or delete a few records.

OLAP
: Online Analytical Processing - workloads that represent low volumes of large, complex queries that read large numbers of records.

Measure
: An aggregation on a numeric field that summarizes the data, such as average, sum, min, max.

Dimension
: A field by which data is summarized, such as a date, location, or attribute of the records. For example, the zip code when calculating the average income of citizens by zip code.

Cube
: A physical data structure that stores pre-computed measures for many dimensions, and provides efficient access to this data.

SQL
: Structured Query Language - the standard query language for relational databases.

MDX
: Multidimensional eXpressions - a query language supported by some systems for cubes.

BI
: Business Intelligence - a category of tools for non-technical users to build analytical queries and reports, and to visualize data.

### Feature Comparison

{:.feature-table}
|---
|| Dremio | Olap on Dadoop
|:-:|:-:|:-:|
Runs in the Hadoop cluster | **optionally provisioned and managed via YARN** | **priviioned and manged via YARN**
Accelerates aggregation queries | **Queries are written for the logical structure of the data, and automatically rewritten to use accelerated aggregate data.** | **Requires queries to be written against the physical structure of the cubes.**
Accelerates ad-hoc queries | **Queries are written for the logical structure of the data, and automatically rewritten to use accelerated row-level data.** | ~~Reports must be rewritten against source systems.~~

### What Are Common Use Cases for Dremio?

Dremio lets you reimagine your end to end analytical processes, with a solution that makes your data engineers and your analysts more productive on day 1. Instead of using ETL and custom scripts to move your data between different environments, Dremio connects to your data sources directly, and automatically creates a highly optimized cache that makes even your biggest data feel small, approachable, and interactive. Dremio supports all your favorite BI tools, and advanced languages like Python/Pandas, R, and Apache Spark.

{:.blue}
**We see a wide range of applications, but here are a few popular first projects:**

- **BI on Non-Relational Data.** Fast access to Elasticsearch, MongoDB, HDFS, S3, plus joins to relational data.
- **Autonomous Data Acceleration.** Make PB-scale queries fast, without cubes or aggregation tables.
- **Self-Service Data.** Empower IT and analysts to discover, curate, accelerate, and share data.
- **The Data Graph.** Lineage of data flows, data reshaping, sharing, and access patterns

{:.center.buttons}
[Learn More](#something)





