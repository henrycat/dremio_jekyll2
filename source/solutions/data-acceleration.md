---
layout: page
title: Data Acceleration
description: Accelerate your data analytics 10x - 1000x. Any source - RDBMS, NoSQL, Hadoop. Any tool - BI, Python, R, SQL. Open source, download now.
---

## Data Acceleration

{:.solutions}
Make your data analytics 10x - 1000x faster. Use your favorite tools. Without cubes, ETL, aggregation tables, BI extracts, or changing your SQL.

{:.solutions.buttons}
[Download Dremio](/downloads/)

## All your systems are different, but they have one thing in common: they’re too slow.
Your analysts and data scientists are hungry for data. They expect instantaneous access, and an interactive experience. They work at the speed of thought. Are they getting data at the speed they need, or are they wasting precious time, waiting because your data is too slow?

## The options we’ve had for 30 years are outdated
You’re probably doing one or all of the following. Each is a non-trivial projects that involves significant IT investment to build out and maintain over time. None of them work well for non-relational sources and the volume and variety of modern data.

- **Staging data.** Using ETL and custom scripts, data is copied out operational systems into a staging area. This removes analytical load from the concerns of operational SLAs, but the process is slow, complex, expensive, and fragile. When sources or schemas change, these scripts need to be revisited and potentially reengineered.
- **Data warehouse.** The idea of a single, non-volatile, authoritative version of the truth is grand. However, building a data warehouse is an enormous undertaking, and most project fail, or fail to deliver what the business really needs.
- **Cubes.** When the data warehouse fails to deliver the performance needed for analysts, IT can turn to cubes, an improvement on performance for a narrow set of known queries. Each BI tool needs its own kind of cube, and analysts need to understand which queries will work on each cube, and which need to be directed at other technologies.
- **Aggregation tables.** Analytics on aggregations of one or more dimensions can be especially demanding on data warehouses. Materialized aggregation tables can dramatically improve the performance of aggregation queries. However, like cubes, analysts need to know which table to use for a given query.
- **BI extracts.** Most BI tools have a proprietary format they use for fast desktop access to data. For dashboards on small datasets, this can be effective, but each of these extracts is 1) specific to a given BI technology, 2) immediately stale, 3) must be distributed to desktops of hundreds or thousands of users, imposing a large cost to enterprise infrastructure teams.

### It’s time for a new way. Dremio.
For 30 years we’ve been trying and failing the same way, and it’s time for a change. No more data warehouses, no more ETL, cubes, aggregation tables, or BI extracts. No more months of waiting for stale, brittle data that fails to tell the whole story. It’s time to rethink data analytics.

Dremio is a fundamentally new approach that starts to deliver value in minutes. 
No matter how you’re storing your data, Dremio makes it all work like a single relational database. 

![alt text here](/img/solutions/acceleration.png)


So whether you’re an analyst using Tableau, Power BI, or Qlik, or a data scientist working in R or Python, Dremio makes all your data easy to access. And Dremio accelerates your data so you can be interactive as your explore and analyze at the speed of thought.

## Optimize your data without changing your data model
To make queries on massive volumes of data fast, you have optimize how the data is organized, on disk and in memory. There’s no way around this - we are all subject to the basic laws of physics. Techniques like columnarization, compression, partitioning, co-location, and sorting can all make massive improvements to processing efficiency. 

But all these options have a big downside - they change the physical model of your data, and  your analysts and data scientists have to change too. They all require your users to understand each of the physical optimizations, and to know which queries to send to each data structure - cubes, data warehouses, BI extracts, aggregation tables, and more. 

## How Dremio is different
Dremio looks like a single, high-performance relational database to any tool. You simply connect over ODBC, JDBC, or REST and send standard SQL queries. Meanwhile, Dremio automatically optimizes the physical organization of your data for different workloads in a cache. Or queries your data sources directly, when you need access to live datasets. 

As your needs evolve over time, your queries and tools can stay the same, and Dremio will automatically rewrite your queries to use the most efficient data structures available. In many cases the same data may be optimized in multiple physical “reflections” to meet the needs of different query patterns.

You get all the benefits of sorting, partitioning, compressing, columnarizing, and aggregating your data, but without the cognitive overhead for your users. And because Dremio is distributed and runs on 1-1000+ servers, you can scale your acceleration to meet even the largest data volumes and number of concurrent users.

#### Technical Details for Data Acceleration
- Supports Tableau, Power BI, Qlik, and any SQL-based tool.
- Supports virtually any data source, including relational, NoSQL, Hadoop, Excel, and others.
- [Documentation](/docs/) for Data Acceleration.
