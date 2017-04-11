---
layout: page
title: Tableau on Hadoop
Description: Connect Tableau to Hadoop. Start running interactive visualizations in minutes.
---

### Tableau on Hadoop

{:.solutions}
Connect Tableau to Hadoop. Experience interactive visualizations in minutes.

{:.solutions.buttons}
[Download Dremio](/downloads/)


### Running Tableau on Hadoop is Slow, But It Doesn’t Have to Be
You’ve built your data lake, but your Tableau users don’t have the interactive experience they expect. As a result, you’re moving data out of your data lake into a data warehouse, or you’re building cubes in a proprietary system that is expensive and complex to maintain. This isn’t the end solution you envisioned, and all the heavy lifting you did to get here isn’t paying off the way you had hoped. 

What if you could run Tableau on Hadoop directly, providing an interactive experience users, without building TDE files, and without worrying about concurrency limitations? Instead of building cubes or moving data into a data warehouse. That’s Dremio.

![alt text here](/img/solutions/hadoop.png)

### Dremio Simplifies and Accelerates Tableau for Hadoop
Dremio connects Tableau to Hadoop, and accelerates your data and queries. SQL queries that are issued to Dremio by Tableau are compiled into Dremio’s distributed SQL execution engine, and pushed down to file reads in a massively parallel process. No matter how your data is stored, Dremio gives you full SQL access, including joins, aggregations, and subqueries. 

### Accelerate Your Data
With Dremio’s autonomous cache, your data is automatically optimized in columnarized, compressed data structures called reflections. Dremio’s reflections are stored in HDFS, and they can accelerate your analytics by 10-1000x. This approach lets you physically optimize the data for multiple workloads without changing the logical model that your Tableau users work with. Learn more about [how Dremio works.](/product)


### Not Just Hadoop, All Your Data Sources
Dremio is more than a solution for Hadoop - it works for all your data sources. Relational databases,[S3](/solutions/tableau-on-s3.html), [MongoDB](/solutions/tableau-on-mongodb/), [Elasticsearch](/solutions/tableau-on-elasticsearch/) and more. Dremio gives you the same rich query access to any source, and accelerates your data to make analysis interactive and fun.

#### Technical Details for Hadoop
- Supports CDH, HDP, and MapR distributions.
- Provisioned and managed via YARN.
- Documentation for [Dremio and Hadoop](/compare/dremio-olap-on-hadoop/).

