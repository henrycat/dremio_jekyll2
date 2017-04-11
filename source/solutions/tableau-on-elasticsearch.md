---
layout: page
title: Tableau on Elasticsearch
description: Connect Tableau to Elasticsearch. Start running interactive SQL in minutes
---

### Using Tableau with Elasticsearch is Hard


{:.solutions}
Connect Tableau to Elasticsearch. Start running interactive visualizations in minutes.

{:.solutions.buttons}
[Download Dremio](/downloads/)




Increasingly companies rely on Elasticsearch for a wide range of strategic applications, like search, machine data analysis, and eCommerce. Elasticsearch makes it easy to build applications quickly, and the community has built a vibrant collection of complementary projects, like Kibana and Logstash.

But Elasticsearch manages data in JSON documents and has no support for SQL. This means Tableau doesn’t work with Elasticsearch. As a result, most companies copy their data from Elasticsearch into a relational database for analytics. And while this makes Tableau work great, moving the data can be a massive engineering project.

![alt text here](/img/solutions/elastic.png)

### Dremio Simplifies and Accelerates Analytics for Elasticsearch
Dremio connects Tableau to your Elasticsearch clusters, and accelerates your data and queries. SQL queries that are issued to Dremio by Tableau are rewritten in Elasticsearch’s DSL, including compiling expressions to Groovy and Painless scripts, and automatically pushed down to your cluster. The results are transformed into rows, including complex data structures like arrays and sub-documents. For joins and other operations that aren’t supported by Elasticsearch, processing is transparently performed in Dremio’s distributed SQL execution engine. Learn more about [how Dremio works](/product/).

### Accelerate Your Data
With Dremio’s autonomous cache, your data is automatically optimized in columnarized, compressed data structures called reflections. Dremio’s reflections can accelerate your analytics by 10-1000x. Learn more about how Dremio works.

### Provide Accurate Analytics With Dremio
Elasticsearch indexes are designed to provide fast estimates of counts while supporting high concurrency. While it is possible to tradeoff performance for accuracy with small data sets, large data sets do not provide this option. Dremio can ensure the accuracy of your analytical queries by maintaining a cache of your data in a compressed, columnarized representation that is optimized for analytics. You have full control for how this cache is maintained, according to a freshness SLA that you configure. Dremio can issue a single read on your data when you choose, and process all your analytics without adding load to your operational deployment.

### Not Just Elasticsearch, All Your Data Sources
Dremio is more than a solution for Elasticsearch - it works for all your data sources. Relational databases, [Hadoop](/solutions/tableau-on-hadoop/), [MongoDB](/solutions/tableau-on-mongodb/), [S3](/solutions/tableau-on-s3.html), and more. Dremio gives you the same rich query access to any source, and accelerates your data to make analysis interactive and fun.

#### Technical Details for Elasticsearch
- Supports CDH, HDP, and MapR distributions.
- Provisioned and managed via YARN.
- Documentation for [Dremio and Hadoop](/doc/).



