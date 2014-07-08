# Awesome Big Data

A curated list of awesome big data frameworks, ressources and other awesomeness. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby) & [hadoopecosystemtable](http://hadoopecosystemtable.github.io/).

Your contributions are always welcome!

- [Awesome Big Data](#awesome-bigdata)
    - [Frameworks](#frameworks)
    - [Distributed Programming](#distributed-programming)
    - [Distributed Filesystem](#distributed-filesystem)
    - [Column Data Model](#column-data-model)
    - [Document Data Model](#document-data-model)
    - [Key-value Data Model](#key-value-data-model)
    - [Graph Data Model](#graph-data-model)
    - [NewSQL Databases](#newsql-databases)
    - [SQL-like processing](#sql-like-processing)
    - [Data Ingestion](#data-ingestion)
    - [Service Programming](#service-programming)
    - [Scheduling](#scheduling)
    - [Machine Learning](#machine-learning)
    - [Bechmarking](#benchmarking)
    - [Security](#security)
    - [System Deployment](#system-deployment)
    - [Applications](#applications)
    - [Search engine and framework](#search-engine-and-framework)
    - [MySQL forks and evolutions](#mysql-forks-and-evolutions)
    - [Memcached forks and evolutions](#memcached-forks-and-evolutions)
    - [Embedded Databases](#embedded-databases)
    - [Data Visualization](#data-visualization)

## Frameworks

* [Apache Hadoop](http://hadoop.apache.org/) - framework for distributed processing. Integrated MapReduce, YARN and HDFS.

## Distributed Programming

* [AddThis Hydra](https://github.com/addthis/hydra) - distributed data processing and storage system.
* [AMPLab SIMR](http://databricks.github.io/simr/) - run Spark on Hadoop MapReduce v1.
* [Apache Crunch](http://crunch.apache.org/) - a simple Java API for tasks like joining and data aggregation that are tedious to implement on plain MapReduce.
* [Apache DataFu](http://incubator.apache.org/projects/datafu.html) - collection of user-defined functions for Hadoop and Pig developed by LinkedIn.
* [Apache Gora](http://gora.apache.org/) - framework for in-memory data model and persistence.
* [Apache Hama](http://hama.apache.org/) - BSP (Bulk Synchronous Parallel) computing framework.
* [Apache MapReduce](http://template.io) - programming model for processing large data sets with a parallel, distributed algorithm on a cluster.
* [Apache Pig](https://pig.apache.org/) - high level language to express data analysis programs for Hadoop.
* [Apache S4](http://incubator.apache.org/s4/) - framework for stream processing, implementation of S4.
* [Apache Spark](http://spark.incubator.apache.org/) - framework for in-memory cluster computing.
* [Apache Spark Streaming](http://spark.incubator.apache.org/docs/0.7.3/streaming-programming-guide.html) - framework for stream processing, part of Spark.
* [Apache Storm](http://storm-project.net/) - framework for stream processing by Twitter also on YARN.
* [Apache Tez](http://tez.incubator.apache.org/) - application framework for executing a complex DAG (directed acyclic graph) of tasks, built on YARN.
* [Apache Twill](https://incubator.apache.org/projects/twill.html) - abstraction over YARN that reduces the complexity of developing distributed applications.
* [Cascalog](http://cascalog.org/) - data processing and querying library.
* [Cheetah](http://vldbarc.org/pvldb/vldb2010/pvldb_vol3/I08.pdf) - High Performance, Custom Data Warehouse on Top of MapReduce.
* [Concurrent Cascading](http://www.cascading.org/) - framework for data management/analytics on Hadoop.
* [Damballa Parkour](https://github.com/damballa/parkour) - MapReduce library for Clojure.
* [Datasalt Pangool](https://github.com/datasalt/pangool) - alternative MapReduce paradigm.
* [DataTorrent StrAM](https://www.datatorrent.com/) - real-time engine is designed to enable distributed, asynchronous, real time in-memory big-data computations in as unblocked a way as possible, with minimal overhead and impact on performance..
* [Facebook Corona](https://www.facebook.com/notes/facebook-engineering/under-the-hood-scheduling-mapreduce-jobs-more-efficiently-with-corona/10151142560538920) - Hadoop enhancement which removes single point of failure.
* [Facebook Peregrine](http://peregrine_mapreduce.bitbucket.org/) - Map Reduce framework.
* [Facebook Scuba](https://www.facebook.com/notes/facebook-engineering/under-the-hood-data-diving-with-scuba/10150599692628920) - distributed in-memory datastore.
* [Google MapReduce](http://research.google.com/archive/mapreduce.html) - map reduce framework.
* [Google MillWheel](http://research.google.com/pubs/pub41378.html) - fault tolerant stream processing framework.
* [HadoopDB](http://db.cs.yale.edu/hadoopdb/hadoopdb.html) - hybrid of MapReduce and DBMS.
* [JAQL](https://code.google.com/p/jaql/) - declarative programming language for working with structured, semi-structured and unstructured data.
* [Kite](http://kitesdk.org/docs/current/) - is a set of libraries, tools, examples, and documentation focused on making it easier to build systems on top of the Hadoop ecosystem.
* [Metamarkers Druid](http://druid.io/) - framework for real-time analysis of large datasets.
* [Netflix PigPen](https://github.com/Netflix/PigPen) - map-reduce for Clojure whiche compiles to Apache Pig.
* [Nokia Disco](http://discoproject.org/) - MapReduce framework developed by Nokia.
* [Pydoop](http://pydoop.sourceforge.net/docs/) - Python MapReduce and HDFS API for Hadoop.
* [Stratosphere](http://stratosphere.eu/) - general purpose cluster computing framework.
* [Twitter Scalding](https://github.com/twitter/scalding) - Scala library for Map Reduce jobs, built on Cascading.
* [Twitter Summingbird](https://github.com/twitter/summingbird) - Streaming MapReduce with Scalding and Storm, by Twitter.

## Distributed Filesystem

* [Apache HDFS](http://hadoop.apache.org/) - a way to store large files across multiple machines.
* [Ceph Filesystem](http://ceph.com/ceph-storage/file-system/) - software storage platform designed.
* [Facebook Haystack](https://www.facebook.com/note.php?note_id=76191543919) - object storage system.
* [Google Colossus](https://google.com/) - distributed filesystem (GFS2).
* [Google GFS](https://google.com/) - distributed filesystem.
* [Google Megastore](http://research.google.com/pubs/pub36971.html) - scalable, highly available storage.
* [GridGain](http://www.gridgain.org/) - GGFS, Hadoop compliant in-memory file system.
* [Lustre file system](http://wiki.lustre.org/) - high-performance distributed filesystem.
* [Quantcast File System QFS](https://www.quantcast.com/engineering/qfs/) - open-source distributed file system.
* [Red Hat GlusterFS](http://www.gluster.org/) - scale-out network-attached storage file system.
* [Tachyon](http://tachyon-project.org/) - reliable file sharing at memory speed across cluster frameworks.

## Column Data Model

* [Actian Vector](http://www.actian.com/) -  column-oriented analytic database.
* [Apache Accumulo](http://accumulo.apache.org/) - distribuited key/value store, built on Hadoop.
* [Apache Cassandra](http://cassandra.apache.org/) - column-oriented distribuited datastore, inspired by BigTable.
* [Apache HBase](http://hbase.apache.org/) - column-oriented distribuited datastore, inspired by BigTable.
* [C-Store](http://db.lcs.mit.edu/projects/cstore/) - column oriented DBMS.
* [Facebook HydraBase](https://code.facebook.com/posts/321111638043166/hydrabase-the-evolution-of-hbase-facebook/) - evolution of HBase made by Facebook.
* [Google BigTable](http://static.googleusercontent.com/external_content/untrusted_dlcp/research.google.com/en//archive/bigtable-osdi06.pdf) - column-oriented distributed datastore.
* [Google Cloud Datastore](https://developers.google.com/datastore/) - is a fully managed, schemaless database for storing non-relational data over BigTable
* [Hypertable](http://hypertable.org/) - column-oriented distribuited datastore, inspired by BigTable.
* [InfiniDB](http://infinidb.co/) - is accessed through a MySQL interface and use massive parallel processing to parallelize queries.
* [MonetDB](https://www.monetdb.org/) - column store database.
* [OhmData C5](http://ohmdata.com/) - improved version of HBase.
* [Parquet](http://parquet.io/) - columnar storage format for Hadoop.
* [Twitter Manhattan](https://blog.twitter.com/2014/manhattan-our-real-time-multi-tenant-distributed-database-for-twitter-scale) - real-time, multi-tenant distributed database for Twitter scale.
* [Vertica](http://www.vertica.com/) - is designed to manage large, fast-growing volumes of data and provide very fast query performance when used for data warehouses.

## Document Data Model

* [Crate Data](https://crate.io/) - is an open source massively scalable data store. It requires zero administration.
* [Facebook Apollo](http://www.infoq.com/news/2014/06/facebook-apollo/) - Facebook’s Paxos-like NoSQL database.
* [jumboDB](http://comsysto.github.io/jumbodb/) - document oriented datastore over Hadoop.
* [LinkedIn Espresso](http://data.linkedin.com/projects/espresso) - horizontally scalable document-oriented NoSQL data store.
* [MarkLogic](http://www.marklogic.com/) - Schema-agnostic Enterprise NoSQL database technology.
* [MongoDB](http://www.mongodb.org/) - Document-oriented database system.
* [RethinkDB](http://www.rethinkdb.com/) - document database that supports queries like table joins and group by.

## Key-value Data Model

* [Amazon DynamoDB](http://aws.amazon.com/dynamodb/) - distributed key/value store, implementation of Dynamo paper.
* [Edis](http://inaka.github.io/edis/) - is a protocol-compatible Server replacement for Redis.
* [ElephantDB](https://github.com/nathanmarz/elephantdb) - Distributed database specialized in exporting data from Hadoop.
* [EventStore](http://geteventstore.com/) - distributed time series database.
* [LinkedIn Krati](https://github.com/linkedin-sna/sna-page/tree/master/krati) - is a simple persistent data store with very low latency and high throughput.
* [Linkedin Voldemort](http://www.project-voldemort.com/voldemort/) - distributed key/value storage system.
* [OpenTSDB](http://opentsdb.net/) - distributed time series database on top of HBase.
* [Redis](http://redis.io/) - in memory key value datastore.
* [Storehaus](https://github.com/twitter/storehaus) - library to work with asynchronous key value stores, by Twitter.

## Graph Data Model

* [Apache Giraph](http://giraph.apache.org/) - implementation of Pregel, based on Hadoop.
* [Apache Spark Bagel](http://spark.incubator.apache.org/docs/0.7.3/bagel-programming-guide.html) - implementation of Pregel, part of Spark.
* [ArangoDB](https://www.arangodb.org/) - multi model distribuited database.
* [Facebook TAO](https://www.facebook.com/notes/facebook-engineering/tao-the-power-of-the-graph/10151525983993920) - TAO is the distributed data store that is widely used at facebook to store and serve the social graph.
* [Google Cayley](https://github.com/google/cayley) - open-source graph database.
* [Google Pregel](http://kowshik.github.io/JPregel/pregel_paper.pdf) - graph processing framework.
* [GraphLab PowerGraph](http://graphlab.org/projects/source.html) - a core C++ GraphLab API and a collection of high-performance machine learning and data mining toolkits built on top of the GraphLab API.
* [GraphX](https://amplab.cs.berkeley.edu/publication/graphx-grades/) - resilient Distributed Graph System on Spark.
* [Intel GraphBuilder](https://01.org/graphbuilder/) - tools to construct large-scale graphs on top of Hadoop.
* [Neo4j](http://www.neo4j.org/) - graph database writting entirely in Java.
* [OrientDB](http://www.orientechnologies.com/) - document and graph database.
* [Phoebus](https://github.com/xslogic/phoebus) - framework for large scale graph processing.
* [Titan](http://thinkaurelius.github.io/titan/) - distributed graph database, built over Cassandra.
* [Twitter FlockDB](https://github.com/twitter/flockdb) - distribuited graph database.

## NewSQL Databases

## SQL-like processing

## Data Ingestion

## Service Programming

## Scheduling

## Machine Learning

## Bechmarking

## Security

## System Deployment

## Applications

## Search engine and framework

## MySQL forks and evolutions

## Memcached forks and evolutions

## Embedded Databases

## Data Visualization
