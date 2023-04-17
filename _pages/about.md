---
permalink: /
title: "A free database researcher"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Wu Chen, a master in WHU currently, and my major research is database. 
Database is a critical component in modern information infrastructure, which plays an important role in internet applications. From the perspective of research, database covers many branches of computer science, including storage, network, compilation, optimization, etc. My goal is to design efficient data structures, e.g., index, and utilize hardware characteristics to reach the Pareto frontier of physical performance. 

Research Area
======
1. **Key-value Storage**. There are many open source key value databases, i.e., [LevelDB](https://github.com/google/leveldb) and [RocksDB](https://github.com/facebook/rocksdb). LSM tree is the key data structure in these databases. There are many optimizations in LSM tree based storage, including **memory cost(e.g., bloom filter)**, **write amplification**, **read/space amplification**, **range query**, and **secondary indexes**. LSM tree extends existing indexes in update-intensive workloads due to its intrinsic write-friendly mechanism. I have been trying to optimize **secondary indexes** in LSM tree storage engine. 

2. **Spatio-temporal Data**. Spatio-temporal data has become increasingly important and has far-reaching implications, given the popularity of mobile phones, GPS devices, and Internet-based map services. One of my works is to monitor potential contact by spatio-temporal data mining during a pandemic. 

3. **Computational Geometry**. It aims to study the algorithms stated in terms of geometry, such as spatial objects, graph. Some conventional data mining tasks are related to computational geometry, i.e., [skyline query](https://en.wikipedia.org/w/index.php?title=Skyline_query&redirect=no), *k*NN query, [shortest path](https://en.wikipedia.org/wiki/Shortest_path_problem#:~:text=In%20graph%20theory%2C%20the%20shortest,its%20constituent%20edges%20is%20minimized.).

4. **Data Structure Design**. Modern search systems require efficient data structures including but not limited to **filters**, **tree-style index** and **hash function**. With the development of machine learning, these items are also equipped with learned features, like leanred index or learned hash. 

Contact Me
======
If you have any interest in my research area, please feel free to contact me by [github](https://github.com/whuwuchen) or [kerinchanser@gmail.com](kerinchanser@gmail.com).



<!-- For more info
------
The web page is built with [academicpages](https://github.com/academicpages/academicpages.github.io). -->


<!-- 3. **Query optimization**. Query optimization is an important feature in many databases such as [PostgreSQL](https://www.postgresql.org/), [Sqlite](https://www.sqlite.org/index.html), [Spark](https://spark.apache.org/).  -->