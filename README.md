# Awesome Big Data

A curated list of awesome big data frameworks, ressources and other awesomeness. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby), [hadoopecosystemtable](http://hadoopecosystemtable.github.io/) & [big-data](http://blog.andreamostosi.name/big-data/).

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
    - [Business Intelligence](#business-intelligence)
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

* [Amazon RedShift](http://aws.amazon.com/redshift/) - data warehouse service, based on PostgreSQL.
* [BayesDB](http://probcomp.csail.mit.edu/bayesdb/index.html) - statistic oriented SQL database.
* [FoundationDB](https://foundationdb.com/) - distributed database, inspired by F1.
* [Google F1](http://research.google.com/pubs/pub41344.html) - distributed SQL database built on Spanner.
* [Google Spanner](http://research.google.com/archive/spanner.html) - globally distributed semi-relational database.
* [H-Store](http://hstore.cs.brown.edu/) - is an experimental main-memory, parallel database management system that is optimized for on-line transaction processing (OLTP) applications.
* [Haeinsa](https://github.com/VCNC/haeinsa) - linearly scalable multi-row, multi-table transaction library for HBase based on Percolator.
* [HandlerSocket](http://www.percona.com/doc/percona-server/5.5/performance/handlersocket.html) - NoSQL plugin for MySQL/MariaDB.
* [InfiniSQL](http://www.infinisql.org/) - infinity scalable RDBMS.
* [InfluxDB](https://github.com/influxdb/influxdb) - distributed time series database.
* [MemSQL](http://www.memsql.com/) - in memory SQL database witho optimized columnar storage on flash.
* [NuoDB](http://www.nuodb.com/) - SQL/ACID compliant distributed database.
* [Postgres-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based Database Cluster.
* [SenseiDB](http://senseidb.com/) - distributed, realtime, semi-structured database.
* [Sky](http://skydb.io/) - database used for flexible, high performance analysis of behavioral data.
* [SymmetricDS](http://www.symmetricds.org/) - open source software for both file and database synchronization.

## SQL-like processing

* [AMPLAB Shark](https://github.com/amplab/shark/) - data warehouse system for Spark.
* [Apache Drill](http://incubator.apache.org/drill/) - framework for interactive analysis, inspired by Dremel.
* [Apache HCatalog](http://hive.apache.org/docs/hcat_r0.5.0/) - table and storage management layer for Hadoop.
* [Apache Hive](http://hive.apache.org/) - SQL-like data warehouse system for Hadoop.
* [Apache Phoenix](http://phoenix.incubator.apache.org/index.html) - SQL skin over HBase.
* [BlinkDB](http://blinkdb.org/) - massively parallel, approximate query engine.
* [Cloudera Impala](http://www.cloudera.com/content/cloudera/en/products/cdh/impala.html) - framework for interactive analysis, Inspired by Dremel.
* [Concurrent Lingual](http://www.cascading.org/lingual/) - SQL-like query language for Cascading.
* [Datasalt Splout SQL](http://www.datasalt.com/products/splout-sql/) - full SQL query engine for big datasets.
* [Facebook PrestoDB](http://prestodb.io/) - distributed SQL query engine.
* [Google BigQuery](http://research.google.com/pubs/pub36632.html) - framework for interactive analysis, implementation of Dremel.
* [Pivotal HAWQ](http://www.gopivotal.com/pivotal-products/data/pivotal-hd) - SQL-like data warehouse system for Hadoop.
* [Spark Catalyst](https://github.com/apache/spark/tree/master/sql) - is a Query Optimization Framework for Spark and Shark.
* [SparkSQL](http://databricks.com/blog/2014/03/26/Spark-SQL-manipulating-structured-data-using-Spark.html) - Manipulating Structured Data Using Spark.
* [Splice Machine](http://www.splicemachine.com/) - a full-featured SQL-on-Hadoop RDBMS with ACID transactions.
* [Stinger](http://hortonworks.com/labs/stinger/) - interactive query for Hive.
* [Tajo](http://tajo.incubator.apache.org/) - distributed data warehouse system on Hadoop.

## Data Ingestion

* [Amazon Kinesis](http://aws.amazon.com/kinesis/) - real-time processing of streaming data at massive scale.
* [Apache Chukwa](http://incubator.apache.org/chukwa/) - data collection system.
* [Apache Flume](http://flume.apache.org/) - service to manage large amount of log data.
* [Apache Kafka](http://kafka.apache.org/) - distributed publish-subscribe messaging system.
* [Apache Samza](http://samza.incubator.apache.org/) - stream processing framework, based on Kafla and YARN.
* [Apache Sqoop](http://sqoop.apache.org/) - tool to transfer data between Hadoop and a structured datastore.
* [Cloudera Morphlines](https://github.com/cloudera/cdk/tree/master/cdk-morphlines) - framework that help ETL to Solr, HBase and HDFS.
* [Facebook Scribe](https://github.com/facebook/scribe) - streamed log data aggregator.
* [Fluentd](http://fluentd.org/) - tool to collect events and logs.
* [HIHO](https://github.com/sonalgoyal/hiho) - framework for connecting disparate data sources with Hadoop.
* [Kestrel](http://robey.github.io/kestrel/) - distributed message queue system.
* [LinkedIn Databus](http://data.linkedin.com/projects/databus) - stream of change capture events for a database.
* [LinkedIn Kamikaze](https://github.com/linkedin/kamikaze) - utility package for compressing sorted integer arrays.
* [LinkedIn White Elephant](https://github.com/linkedin/white-elephant) -  log aggregator and dashboard.
* [Netflix Suro](https://github.com/Netflix/suro) - log agregattor like Storm and Samza based on Chukwa.
* [Pinterest Secor](https://github.com/pinterest/secor) - is a service implementing Kafka log persistance.

## Service Programming

* [Akka Toolkit](http://akka.io/) - runtime for distributed, and fault tolerant event-driven applications on the JVM.
* [Apache Avro](http://avro.apache.org/) - data serialization system.
* [Apache Curator](http://curator.apache.org/) - Java libaries for Apache ZooKeeper.
* [Apache Karaf](http://karaf.apache.org/) - OSGi runtime that runs on top of any OSGi framework.
* [Apache Thrift](http://thrift.apache.org//) - framework to build binary protocols.
* [Apache Zookeeper](http://zookeeper.apache.org/) - centralized service for process management.
* [Google Chubby](http://research.google.com/archive/chubby.html) - a lock service for loosely-coupled distributed systems.
* [Linkedin Norbert](http://data.linkedin.com/opensource/norbert) - cluster manager.
* [OpenMPI](http://www.open-mpi.org/) - message passing framework.
* [Serf](http://www.serfdom.io/) - decentralized solution for service discovery and orchestration.
* [Spring XD](https://github.com/spring-projects/spring-xd) - distributed and extensible system for data ingestion, real time analytics, batch processing, and data export.
* [Twitter Elephant Bird](https://github.com/kevinweil/elephant-bird) - libraries for working with LZOP-compressed data.
* [Twitter Finagle](https://twitter.github.io/finagle/) - asynchronous network stack for the JVM.

## Scheduling

* [Apache Aurora](http://aurora.incubator.apache.org/) - is a service scheduler that runs on top of Apache Mesos.
* [Apache Falcon](http://falcon.incubator.apache.org/) - data management framework.
* [Apache Oozie](http://oozie.apache.org/) - workflow job schedul.
* [Chronos](http://airbnb.github.io/chronos/) - distributed and fault-tolerant scheduler.
* [Linkedin Azkaban](http://azkaban.github.io/azkaban2/) - batch workflow job scheduler.
* [Sparrow](https://github.com/radlab/sparrow) - scheduling platform.

## Machine Learning

* [Apache Mahout](http://mahout.apache.org/) - machine learning library for Hadoop.
* [Cloudera Oryx](https://github.com/cloudera/oryx) - real-time large-scale machine learning.
* [Concurrent Pattern](http://www.cascading.org/pattern/) - machine learning library for Cascading.
* [etcML](http://www.etcml.com/) - text classification with machine learning.
* [Etsy Conjecture](https://github.com/etsy/Conjecture) - scalable Machine Learning in Scalding.
* [H2O](http://0xdata.github.io/h2o/) - statistical, machine learning and math runtime for Hadoop.
* [MLbase](http://www.mlbase.org/) - distributed machine learning libraries for the BDAS stack.
* [PredictionIO](http://prediction.io/) - machine learning server buit on Hadoop, Mahout and Cascading.
* [Spark MLlib](http://spark.apache.org/docs/0.9.0/mllib-guide.html) - a Spark implementation of some common machine learning (ML) functionality.
* [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/wiki) - learning system sponsored by Microsoft and Yahoo!.
* [WEKA](http://www.cs.waikato.ac.nz/ml/weka/) - suite of machine learning software.

## Bechmarking

* [Apache Hadoop Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-3561) - micro-benchmarks for testing Hadoop performances.
* [Berkeley SWIM Benchmark](https://github.com/SWIMProjectUCB/SWIM/wiki) - real-world big data workload benchmark.
* [Intel HiBench](https://github.com/intel-hadoop/HiBench) - a Hadoop benchmark suite.
* [PUMA Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-5116) - benchmark suite for MapReduce application.
* [Yahoo Gridmix3](https://developer.yahoo.com/blogs/hadoop/gridmix3-emulating-production-workload-apache-hadoop-450.html) - Hadoop cluster benchmarking from Yahoo engineer team.


## Security

* [Apache Knox Gateway](http://knox.apache.org/) - single point of secure access for Hadoop clusters.
* [Apache Sentr](http://incubator.apache.org/projects/sentry.html) - security module for data stored in Hadoop.

## System Deployment

## Applications

## Search engine and framework

## MySQL forks and evolutions

## Memcached forks and evolutions

## Embedded Databases

## Business Intelligence

## Data Visualization

## Interesting readings
