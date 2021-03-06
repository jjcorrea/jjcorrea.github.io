---
layout: post
title: Big Data / NoSQL Reference
---

### Challenges

<span class="label label-primary">Processing</span>
<span class="label label-primary">Compression</span>
<span class="label label-primary">Statistics</span>
<span class="label label-primary">Storage</span>
<span class="label label-primary">Search</span>
<span class="label label-primary">Analysis</span>
<span class="label label-primary">Visualization</span>
<span class="label label-primary">Transport</span>

### Highlights

* Auto-sharding – A NoSQL database automatically spreads data across servers, without requiring applications to participate. Servers can be added or removed from the data layer without application downtime, with data (and I/O) automatically spread across the servers. Most NoSQL databases also support data replication, storing multiple copies of data across the cluster, and even across data centers, to ensure high availability and support disaster recovery. A properly managed NoSQL database system should never need to be taken offline, for any reason, supporting 24x365 continuous operation of applications.

* Distributed query support – “Sharding” a relational database can reduce, or eliminate in certain cases, the ability to perform complex data queries. NoSQL database systems retain their full query expressive power even when distributed across hundreds of servers.

* Integrated caching – To reduce latency and increase sustained data throughput, advanced NoSQL database technologies transparently cache data in system memory. This behavior is transparent to the application developer and the operations team, compared to relational technology where a caching tier is usually a separate infrastructure tier that must be developed to, deployed on separate servers, and explicitly managed by the ops team.

### References & Related stuff

* [Courses](http://www.edureka.co/about-big-data-and-hadoop)
* [Spark & Scala](https://www.youtube.com/watch?v=Q76-fCqVjhU)
* [Hadoop alternatives](http://howtojboss.com/2013/09/04/ampd-for-hadoop-alternatives/)