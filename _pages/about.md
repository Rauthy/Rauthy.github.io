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
1. **Key-value storage**. There are many open source key value databases, i.e., [LevelDB](https://github.com/google/leveldb) and [RocksDB](https://github.com/facebook/rocksdb). LSM tree is the key data structure in these databases. There are many optimizations in LSM tree based storage, including **memory cost(e.g., bloom filter)**, **write amplification**, **read/space amplification**, **range query**, and **secondary indexes**. LSM tree extends existing indexes in update-intensive workloads due to its intrinsic write-friendly mechanism. I have been trying to optimize **secondary indexes** in LSM tree storage engine. 

2. **Spatio-temporal data**. Spatio-temporal data has become increasingly important and has far-reaching implications, given the popularity of mobile phones, GPS devices, and Internet-based map services. One of my works is to monitor potential contact by spatio-temporal data mining during a pandemic. 

<!-- 3. **Query optimization**. Query optimization is an important feature in many databases such as [PostgreSQL](https://www.postgresql.org/), [Sqlite](https://www.sqlite.org/index.html), [Spark](https://spark.apache.org/).  -->

3. **Computational geometry**. It aims to study the algorithms stated in terms of geometry, such as spatial objects, graph. Some conventional data mining tasks are related to computational geometry, i.e., [skyline query](https://en.wikipedia.org/w/index.php?title=Skyline_query&redirect=no), *k*NN query, [shortest path](https://en.wikipedia.org/wiki/Shortest_path_problem#:~:text=In%20graph%20theory%2C%20the%20shortest,its%20constituent%20edges%20is%20minimized.). Some materials can be found in this [link](https://zhuanlan.zhihu.com/p/33355636). 

Contact Me
======
If you have any interest in my research area, please feel free to contact me by [github](https://github.com/whuwuchen) or [email](kerinchanser@gmail.com).



For more info
------
The web page is built with [academicpages](https://github.com/academicpages/academicpages.github.io).
