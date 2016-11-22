% Hands-on Apache Spark
% Dirk Hesse
% *iKnow Solutions Norge*

# What is Spark?


> **Apache Spark™** is a fast and general engine for large-scale data
> processing. 

- Distributed.
- Fast.
- General.
- In-memory.

---

# Myths and Facts

- Spark $\neq$ Hadoop!
- Distributed: You need a **cluster**.
- In-memory: You (sort of) need lots of **memory**.
- "Fast and general": You need to write **code** (Scala, Python, R).

---

# Input

+------------------+---------------------+
|- Out of the box  | - 3rd party packages|
|    - local files |     - MongoDB       |
|    - HDFS        |     - Power BI      |
|    - Cassandra   |     - Sequoia       |
|    - HBase       |     - Cloudant      |
|    - Amazon S3   |     - Couchbase     |
|    - ...         |     - Solr          |
|                  |     - salesforce    |
|                  |     - many more     |
+------------------+---------------------+

---

# Live Demo

[Reading Data]

---

# The RDD - At the ♥ of Spark.

---

# Live Demo

[RDD Demo]


---

# Beyond data exploration

![Spark Stack](img/spark-stack.png)\

---

# Spark SQL

[SQL]


[Reading Data]: http://localhost:8888/notebooks/ReadData.ipynb
[RDD Demo]: http://localhost:8888/notebooks/RDD.ipynb
[SQL]: http://localhost:8888/notebooks/SQL.ipynb
