---
layout: page
title: Tableau on MongoDB
---


### Tableau on MongoDB

{:.solutions}
Connect Tableau to MongoDB. Replica Sets. Sharded Clusters. Dremio has you covered.

{:.solutions.buttons}
[Download Dremio](/downloads/)


### Analyzing Data in MongoDB is Hard
Today’s strategic apps for social, mobile, and web applications are built on MongoDB. This fast, agile database allows developers to build and evolve applications quickly. Companies like MongoDB because it is cost effective and reduces their time to value.

But MongoDB manages data in JSON documents and has no support for standard SQL. As a result, Tableau is limited in how it works with MongoDB, and most companies copy their data into a relational database for analytics. And while this makes Tableau work great, moving the data can be a massive engineering project.


![alt text here](/img/solutions/mongo.png)

### Dremio Simplifies and Accelerates Analytics for MongoDB
Dremio connects Tableau to your MongoDB clusters, and accelerates your data and queries. SQL queries that are issued to Dremio by Tableau are rewritten in MongoDB’s query language and automatically pushed down to the replicas. Query results are transformed into rows, including complex data structures like arrays and sub-documents. For joins and other operations that aren’t supported by MongoDB, processing is transparently performed in Dremio’s distributed SQL execution engine. Learn more about [how Dremio works.](/product/)

### Offload Your Analytics With Dremio
MongoDB can provide exceptional performance for write-intensive workloads. But full table scans and other scan-intensive queries can crush performance and disrupt your SLA. Dremio can offload your analytical queries by maintaining an up-to-date cache of your data in a compressed, columnarized representation that is optimized for analytics. 

You have full control for how this cache is maintained - via secondaries, full or incremental, and according to a freshness SLA that you configure. Dremio can issue a single read on your data when you choose, and process all your analytics without adding load to your operational deployment.

### Not Just MongoDB, All Your Data Sources
Dremio is more than a solution for MongoDB - it works for all your data sources. Relational databases, [Hadoop](/solutions/tableau-on-hadoop/), [MongoDB](/solutions/tableau-on-mongodb/), [S3](/solutions/tableau-on-s3.html) and more. Dremio gives you the same rich query access to any source, and accelerates your data to make analysis interactive and fun.

#### Technical Details for MongoDB
- Supports MongoDB 3.0 and later.
- Supports replica sets and sharded clusters.
- [Documentation](/docs) for Dremio and MongoDB.

