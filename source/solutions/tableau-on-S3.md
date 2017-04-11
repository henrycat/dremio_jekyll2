---
layout: page
title: Tableau on S3
description: Put all your data in the hands of the business, safely and securely. Any source - RDBMS, NoSQL, Hadoop. Any tool - BI, Python, R, SQL. Open source, download now.
---


### Tableau on S3

{:.solutions}
Connect Tableau to Amazon S3. Start running interactive visualizations in minutes.

{:.solutions.buttons}
[Download Dremio](/downloads/)


### Running TableauI on S3 is a Slow, Complex, Multi-Step Process
Amazon S3 has quickly become indispensable for many modern applications. It provides unlimited scalability, reliability, a simple API, and it is unbeatable in terms of cost. For architects S3 is an important tool that complements other data infrastructure - it’s where your data “lands” initially, and then later is “picked up” for processing, then moved into RDS, EMR, or your Hadoop cluster. 

If you’re using Tableau, then one of the end points of your data pipelines is a relational database like RDS, because that’s how Tableau works best. But think about all the steps it took to get the data from S3 into Tableau and the hands of your analysts. 

What if you could run Tableau on S3 directly, with an interactive experience, and without making any compromises in functionality? You could dramatically reduce the time and complexity to work with your data, and shrink your costs along the way. That’s Dremio.

![alt text here](/img/solutions/s3.png)

### Dremio Simplifies and Accelerates Analytics for Amazon S3
Dremio connects Tableau to S3, and accelerates your data and queries. SQL queries that are issued to Dremio by Tableau are compiled into Dremio’s distributed SQL execution engine, and pushed down to file reads in a massively parallel process. No matter how your data is stored, Dremio gives you full SQL access, including joins, aggregations, and sub-queries.

### Accelerate Your Data
With Dremio’s autonomous cache, your data is automatically optimized in columnarized, compressed data structures called reflections. Dremio’s reflections are stored in S3, and they can accelerate your analytics by 10-1000x. [Learn more about how Dremio works](/product/).

### Not Just S3, All Your Data Sources
Dremio is more than a solution for S3 - it works for all your data sources. Relational databases,[Hadoop](/solutions/tableau-on-hadoop/), [MongoDB](/solutions/tableau-on-mongodb/), [Elasticsearch,](/solutions/tableau-on-elasticsearch.html) and more. Dremio gives you the same rich query access to any source, and accelerates your data to make analysis interactive and fun.

#### Technical Details for S3
- Supports Elasticsearch 2.0 and later.
- Dremio runs on EC2 instances, with data stored in S3.
- [Documentation](docs) for Dremio and S3.

