<h1>
 Awesome Data Engineering
</h1>
<p>
 A curated list of data engineering tools for software developers
 <a href="https://github.com/sindresorhus/awesome">
  <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"/>
 </a>
</p>
<p>
 List of content
</p>
<ol>
 <li>
  [Databases] (#databases)
 </li>
 <li>
  <a href="#data-ingestion">
   Ingestion
  </a>
 </li>
 <li>
  [File System] (#file-system)
 </li>
 <li>
  <a href="#serialization-format">
   Serialization format
  </a>
 </li>
 <li>
  <a href="#stream-processing">
   Stream Processing
  </a>
 </li>
 <li>
  [Batch Processing] (#batch-processing)
 </li>
 <li>
  [Charts and Dashboards] (#charts-and-dashboards)
 </li>
 <li>
  [Workflow] (#workflow)
 </li>
 <li>
  <a href="#datasets">
   Datasets
  </a>
 </li>
 <li>
  [Monitoring] (#monitoring)
 </li>
 <li>
  <a href="#docker">
   Docker
  </a>
 </li>
</ol>
<h1>
 Databases
</h1>
<ul>
 <li>
  Relational
  <ul>
   <li>
    <a href="https://github.com/otoolep/rqlite">
     RQLite
    </a>
    Replicated SQLite using the Raft consensus protocol
   </li>
   <li>
    <a href="http://www.mysql.com/">
     MySQL
    </a>
    The world's most popular open source database.
    <ul>
     <li>
      <a href="https://www.percona.com/software/mysql-database/percona-xtrabackup">
       Percona XtraBackup
      </a>
      Percona XtraBackup is a free, open source, complete online backup solution for all versions of Percona Server, MySQL® and MariaDB®
     </li>
     <li>
      <a href="https://github.com/pinterest/mysql_utils">
       mysql_utils
      </a>
      Pinterest MySQL Management Tools
      <sup>
       &#9733 616, pushed 77 days ago
      </sup>
     </li>
    </ul>
   </li>
   <li>
    <a href="https://mariadb.org/">
     MariaDB
    </a>
    An enhanced, drop-in replacement for MySQL.
   </li>
   <li>
    <a href="http://www.postgresql.org/">
     PostgreSQL
    </a>
    The world's most advanced open source database.
   </li>
   <li>
    <a href="http://aws.amazon.com/rds/">
     Amazon RDS
    </a>
    Amazon RDS makes it easy to set up, operate, and scale a relational database in the cloud.
   </li>
   <li>
    <a href="https://crate.io/">
     Crate.IO
    </a>
    Scalable SQL database with the NOSQL goodies.
   </li>
  </ul>
 </li>
 <li>
  Key-Value
  <ul>
   <li>
    <a href="http://redis.io/">
     Redis
    </a>
    An open source, BSD licensed, advanced key-value cache and store.
   </li>
   <li>
    <a href="https://docs.basho.com/riak/latest/">
     Riak
    </a>
    A distributed database designed to deliver maximum data availability by distributing data across multiple servers.
   </li>
   <li>
    <a href="http://aws.amazon.com/dynamodb/">
     AWS DynamoDB
    </a>
    A fast and flexible NoSQL database service for all applications that need consistent, single-digit millisecond latency at any scale.
   </li>
   <li>
    <a href="https://github.com/rescrv/HyperDex">
     HyperDex
    </a>
    HyperDex is a scalable, searchable key-value store
    <sup>
     &#9733 1064, pushed 19 days ago
    </sup>
   </li>
   <li>
    <a href="http://ssdb.io">
     SSDB
    </a>
    A high performance NoSQL database supporting many data structures, an alternative to Redis
   </li>
   <li>
    <a href="https://github.com/sapo/kyoto">
     Kyoto Tycoon
    </a>
    Kyoto Tycoon is a lightweight network server on top of the Kyoto Cabinet key-value database, built for high-performance and concurrency
   </li>
   <li>
    <a href="https://github.com/iondbproject/iondb">
     IonDB
    </a>
    A key-value store for microcontroller and IoT applications
    <sup>
     &#9733 409, pushed 104 days ago
    </sup>
   </li>
  </ul>
 </li>
 <li>
  Column
  <ul>
   <li>
    <a href="http://cassandra.apache.org/">
     Cassandra
    </a>
    The right choice when you need scalability and high availability without compromising performance.
    <ul>
     <li>
      <a href="http://www.ecyrd.com/cassandracalculator/">
       Cassandra Calculator
      </a>
      This simple form allows you to try out different values for your Apache Cassandra cluster and see what the impact is for your application.
     </li>
     <li>
      <a href="https://github.com/pcmanus/ccm">
       CCM
      </a>
      A script to easily create and destroy an Apache Cassandra cluster on localhost
      <sup>
       &#9733 672, pushed 7 days ago
      </sup>
     </li>
     <li>
      <a href="https://github.com/scylladb/scylla">
       ScyllaDB
      </a>
      NoSQL data store using the seastar framework, compatible with Apache Cassandra http://www.scylladb.com/
      <sup>
       &#9733 1896, pushed 1 days ago
      </sup>
     </li>
    </ul>
   </li>
   <li>
    <a href="http://hbase.apache.org/">
     HBase
    </a>
    The Hadoop database, a distributed, scalable, big data store.
   </li>
   <li>
    <a href="http://www.infobright.org">
     Infobright
    </a>
    Column oriented, open-source analytic database provides both speed and efficiency.
   </li>
   <li>
    <a href="http://aws.amazon.com/redshift/">
     AWS Redshift
    </a>
    A fast, fully managed, petabyte-scale data warehouse that makes it simple and cost-effective to analyze all your data using your existing business intelligence tools.
   </li>
   <li>
    FiloDB (https://github.com/tuplejump/FiloDB) Distributed. Columnar. Versioned. Streaming. SQL.
   </li>
  </ul>
 </li>
 <li>
  Document
  <ul>
   <li>
    <a href="https://www.mongodb.org/">
     MongoDB
    </a>
    An open-source, document database designed for ease of development and scaling.
    <ul>
     <li>
      <a href="https://www.percona.com/software/mongo-database/percona-server-for-mongodb">
       Percona Server for MongoDB
      </a>
      Percona Server for MongoDB® is a free, enhanced, fully compatible, open source, drop-in replacement for the MongoDB® Community Edition that includes enterprise-grade features and functionality.
     </li>
     <li>
      <a href="https://github.com/rain1017/memdb">
       MemDB
      </a>
      Distributed Transactional In-Memory Database (based on MongoDB)
      <sup>
       &#9733 488, pushed 135 days ago
      </sup>
     </li>
    </ul>
   </li>
   <li>
    <a href="https://www.elastic.co/">
     Elasticsearch
    </a>
    Search & Analyze Data in Real Time.
   </li>
   <li>
    <a href="http://www.couchbase.com/">
     Couchbase
    </a>
    The highest performing NoSQL distributed database.
   </li>
   <li>
    <a href="http://rethinkdb.com/">
     RethinkDB
    </a>
    The open-source database for the realtime web.
   </li>
  </ul>
 </li>
 <li>
  Graph
  <ul>
   <li>
    <a href="http://neo4j.com/">
     Neo4j
    </a>
    The world’s leading graph database.
   </li>
   <li>
    <a href="http://orientdb.com/orientdb/">
     OrientDB
    </a>
    2nd Generation Distributed Graph Database with the flexibility of Documents in one product with an Open Source commercial friendly license.
   </li>
   <li>
    <a href="https://www.arangodb.com/">
     ArangoDB
    </a>
    A distributed free and open-source database with a flexible data model for documents, graphs, and key-values.
   </li>
   <li>
    <a href="http://thinkaurelius.github.io/titan/">
     Titan
    </a>
    A scalable graph database optimized for storing and querying graphs containing hundreds of billions of vertices and edges distributed across a multi-machine cluster.
   </li>
   <li>
    <a href="https://github.com/twitter/flockdb">
     FlockDB
    </a>
    A distributed, fault-tolerant graph database by Twitter.
    <sup>
     &#9733 2814, pushed 216 days ago
    </sup>
   </li>
  </ul>
 </li>
 <li>
  Distributed
  <ul>
   <li>
    <a href="http://www.datomic.com">
     DAtomic
    </a>
    The fully transactional, cloud-ready, distributed database.
   </li>
   <li>
    <a href="http://geode.incubator.apache.org">
     Apache Geode
    </a>
    An open source, distributed, in-memory database for scale-out applications.
   </li>
   <li>
    <a href="https://github.com/GovernmentCommunicationsHeadquarters/Gaffer">
     Gaffer
    </a>
    A large-scale graph database
    <sup>
     &#9733 1163, pushed 2 days ago
    </sup>
   </li>
  </ul>
 </li>
 <li>
  Timeseries
  <ul>
   <li>
    <a href="https://github.com/influxdata/influxdb">
     InfluxDB
    </a>
    Scalable datastore for metrics, events, and real-time analytics.
   </li>
   <li>
    <a href="https://github.com/OpenTSDB/opentsdb">
     OpenTSDB
    </a>
    A scalable, distributed Time Series Database.
    <sup>
     &#9733 1963, pushed 1 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/kairosdb/kairosdb">
     kairosdb
    </a>
    Fast scalable time series database.
    <sup>
     &#9733 814, pushed 4 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/spotify/heroic">
     Heroic
    </a>
    A scalable time series database based on Cassandra and Elasticsearch, by Spotify
    <sup>
     &#9733 371, pushed 8 days ago
    </sup>
   </li>
  </ul>
  <sup>
   &#9733 7943, pushed 2 days ago
  </sup>
 </li>
 <li>
  Other
  <ul>
   <li>
    <a href="https://github.com/tarantool/tarantool/">
     Tarantool
    </a>
    Tarantool is an in-memory database and application server.
   </li>
   <li>
    <a href="https://github.com/greenplum-db/gpdb">
     GreenPlum
    </a>
    The Greenplum Database (GPDB) is an advanced, fully featured, open source data warehouse. It provides powerful and rapid analytics on petabyte scale data volumes.
    <sup>
     &#9733 1417, pushed 1 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/google/cayley">
     cayley
    </a>
    An open-source graph database. Google.
    <sup>
     &#9733 7409, pushed 8 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/SnappyDataInc/snappydata">
     Snappydata
    </a>
    SnappyData: OLTP + OLAP Database built on Apache Spark
    <sup>
     &#9733 264, pushed 2 days ago
    </sup>
   </li>
  </ul>
 </li>
</ul>
<h1>
 Data Ingestion
</h1>
<ul>
 <li>
  <a href="http://kafka.apache.org/">
   Kafka
  </a>
  Publish-subscribe messaging rethought as a distributed commit log.
  <ul>
   <li>
    <a href="https://github.com/linkedin/camus">
     Camus
    </a>
    LinkedIn's Kafka to HDFS pipeline.
    <sup>
     &#9733 642, pushed 147 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/confluentinc/bottledwater-pg">
     BottledWater
    </a>
    Change data capture from PostgreSQL into Kafka
    <sup>
     &#9733 658, pushed 4 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/airbnb/kafkat">
     kafkat
    </a>
    Simplified command-line administration for Kafka brokers
    <sup>
     &#9733 114, pushed 12 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/edenhill/kafkacat">
     kafkacat
    </a>
    Generic command line non-JVM Apache Kafka producer and consumer
    <sup>
     &#9733 356, pushed 15 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/xstevens/pg_kafka">
     pg-kafka
    </a>
    A PostgreSQL extension to produce messages to Apache Kafka
    <sup>
     &#9733 46, pushed 397 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/edenhill/librdkafka">
     librdkafka
    </a>
    The Apache Kafka C/C++ library
    <sup>
     &#9733 508, pushed 4 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/wurstmeister/kafka-docker">
     kafka-docker
    </a>
    Kafka in Docker
    <sup>
     &#9733 377, pushed 13 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/yahoo/kafka-manager">
     kafka-manager
    </a>
    A tool for managing Apache Kafka
    <sup>
     &#9733 2165, pushed 8 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/SOHU-Co/kafka-node">
     kafka-node
    </a>
    Node.js client for Apache Kafka 0.8
    <sup>
     &#9733 452, pushed 3 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/pinterest/secor">
     Secor
    </a>
    Pinterest's Kafka to S3 distributed consumer
    <sup>
     &#9733 615, pushed 1 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/uber/kafka-logger">
     Kafka-logger
    </a>
    Kafka-winston logger for nodejs from uber
    <sup>
     &#9733 11, pushed 25 days ago
    </sup>
   </li>
  </ul>
 </li>
 <li>
  <a href="http://aws.amazon.com/kinesis/">
   AWS Kinesis
  </a>
  A fully managed, cloud-based service for real-time data processing over large, distributed data streams.
 </li>
 <li>
  <a href="http://www.rabbitmq.com/">
   RabbitMQ
  </a>
  Robust messaging for applications.
 </li>
 <li>
  <a href="http://www.fluentd.org">
   FluentD
  </a>
  An open source data collector for unified logging layer.
 </li>
 <li>
  <a href="https://sqoop.apache.org">
   Apache Sqoop
  </a>
  A tool designed for efficiently transferring bulk data between Apache Hadoop and structured datastores such as relational databases.
 </li>
 <li>
  <a href="https://github.com/mozilla-services/heka">
   Heka
  </a>
  Data Acquisition and Processing Made Easy
  <sup>
   &#9733 3045, pushed 4 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/linkedin/gobblin">
   Gobblin
  </a>
  Universal data ingestion framework for Hadoop from Linkedin
  <sup>
   &#9733 545, pushed 1 days ago
  </sup>
 </li>
</ul>
<h1>
 File System
</h1>
<ul>
 <li>
  <a href="https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html">
   HDFS
  </a>
  <ul>
   <li>
    <a href="https://github.com/spotify/snakebite">
     Snakebite
    </a>
    A pure python HDFS client
    <sup>
     &#9733 430, pushed 25 days ago
    </sup>
   </li>
  </ul>
 </li>
 <li>
  <a href="http://aws.amazon.com/s3/">
   AWS S3
  </a>
  <ul>
   <li>
    <a href="https://github.com/piskvorky/smart_open">
     smart_open
    </a>
    Utils for streaming large files (S3, HDFS, gzip, bz2)
    <sup>
     &#9733 386, pushed 8 days ago
    </sup>
   </li>
  </ul>
 </li>
 <li>
  <a href="http://tachyon-project.org/">
   Tachyon
  </a>
  Tachyon is a memory-centric distributed storage system enabling reliable data sharing at memory-speed across cluster frameworks, such as Spark and MapReduce
 </li>
 <li>
  <a href="http://ceph.com/">
   CEPH
  </a>
  Ceph is a unified, distributed storage system designed for excellent performance, reliability and scalability
 </li>
 <li>
  <a href="http://www.orangefs.org/">
   OrangeFS
  </a>
  Orange File System is a branch of the Parallel Virtual File System
 </li>
 <li>
  <a href="https://github.com/tuplejump/snackfs-release">
   SnackFS
  </a>
  SnackFS is our bite-sized, lightweight HDFS compatible FileSystem built over Cassandra
  <sup>
   &#9733 14, pushed 299 days ago
  </sup>
 </li>
 <li>
  <a href="http://www.gluster.org/">
   GlusterFS
  </a>
  Gluster Filesystem
 </li>
 <li>
  <a href="http://www.xtreemfs.org/">
   XtreemFS
  </a>
  fault-tolerant distributed file system for all storage needs
 </li>
 <li>
  <a href="https://github.com/chrislusf/seaweedfs">
   SeaweedFS
  </a>
  Seaweed-FS is a simple and highly scalable distributed file system. There are two objectives: to store billions of files! to serve the files fast! Instead of supporting full POSIX file system semantics, Seaweed-FS choose to implement only a key~file mapping. Similar to the word "NoSQL", you can call it as "NoFS".
  <sup>
   &#9733 2415, pushed 5 days ago
  </sup>
 </li>
 <li>
  <a href="https://bitbucket.org/nikratio/s3ql">
   S3QL
  </a>
  S3QL is a file system that stores all its data online using storage services like Google Storage, Amazon S3, or OpenStack.
 </li>
</ul>
<h1>
 Serialization format
</h1>
<ul>
 <li>
  <a href="https://avro.apache.org">
   Apache Avro
  </a>
  Apache Avro™ is a data serialization system
 </li>
 <li>
  <a href="https://parquet.apache.org">
   Apache Parquet
  </a>
  Apache Parquet is a columnar storage format available to any project in the Hadoop ecosystem, regardless of the choice of data processing framework, data model or programming language.
  <ul>
   <li>
    <a href="https://github.com/google/snappy">
     Snappy
    </a>
    A fast compressor/decompressor. Used with Parquet
    <sup>
     &#9733 1121, pushed 28 days ago
    </sup>
   </li>
   <li>
    <a href="http://zlib.net/pigz/">
     PigZ
    </a>
    A parallel implementation of gzip for modern
multi-processor, multi-core machines
   </li>
  </ul>
 </li>
 <li>
  <a href="https://orc.apache.org/">
   Apache ORC
  </a>
  The smallest, fastest columnar storage for Hadoop workloads
 </li>
 <li>
  <a href="https://thrift.apache.org">
   Apache Thrift
  </a>
  The Apache Thrift software framework, for scalable cross-language services development
 </li>
 <li>
  <a href="https://github.com/google/protobuf">
   ProtoBuf
  </a>
  Protocol Buffers - Google's data interchange format
  <sup>
   &#9733 8709, pushed 2 days ago
  </sup>
 </li>
 <li>
  <a href="http://wiki.apache.org/hadoop/SequenceFile">
   SequenceFile
  </a>
  SequenceFile is a flat file consisting of binary key/value pairs. It is extensively used in MapReduce as input/output formats
 </li>
 <li>
  <a href="https://github.com/EsotericSoftware/kryo">
   Kryo
  </a>
  Kryo is a fast and efficient object graph serialization framework for Java
  <sup>
   &#9733 1847, pushed 9 days ago
  </sup>
 </li>
</ul>
<h1>
 Stream Processing
</h1>
<ul>
 <li>
  <a href="https://spark.apache.org/streaming/">
   Spark Streaming
  </a>
  Spark Streaming makes it easy to build scalable fault-tolerant streaming applications.
 </li>
 <li>
  <a href="https://flink.apache.org/">
   Apache Flink
  </a>
  Apache Flink is a streaming dataflow engine that provides data distribution, communication, and fault tolerance for distributed computations over data streams.
 </li>
 <li>
  <a href="https://storm.apache.org">
   Apache Storm
  </a>
  Apache Storm is a free and open source distributed realtime computation system
 </li>
 <li>
  <a href="https://samza.apache.org">
   Apache Samza
  </a>
  Apache Samza is a distributed stream processing framework
 </li>
 <li>
  <a href="http://nifi.apache.org/">
   Apache NiFi
  </a>
  is an easy to use, powerful, and reliable system to process and distribute data
 </li>
 <li>
  <a href="https://voltdb.com/">
   VoltDB
  </a>
 </li>
 <li>
  <a href="https://github.com/pipelinedb/pipelinedb">
   PipelineDB
  </a>
  The Streaming SQL Database https://www.pipelinedb.com
  <sup>
   &#9733 864, pushed 5 days ago
  </sup>
 </li>
</ul>
<h1>
 Batch Processing
</h1>
<ul>
 <li>
  <a href="http://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html">
   Hadoop MapReduce
  </a>
  Hadoop MapReduce is a software framework for easily writing applications which process vast amounts of data (multi-terabyte data-sets) in-parallel on large clusters (thousands of nodes) of commodity hardware in a reliable, fault-tolerant manner
 </li>
 <li>
  <a href="https://spark.apache.org/">
   Spark
  </a>
  <ul>
   <li>
    <a href="http://spark-packages.org">
     Spark Packages
    </a>
    A community index of packages for Apache Spark
   </li>
   <li>
    <a href="https://github.com/Stratio/deep-spark">
     Deep Spark
    </a>
    Connecting Apache Spark with different data stores
    <sup>
     &#9733 174, pushed 292 days ago
    </sup>
   </li>
   <li>
    <a href="http://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html">
     Spark RDD API Examples
    </a>
    by Zhen He
   </li>
   <li>
    <a href="https://github.com/cloudera/hue/tree/master/apps/spark/java#welcome-to-livy-the-rest-spark-server">
     Livy
    </a>
    Livy, the REST Spark Server
   </li>
  </ul>
 </li>
 <li>
  <a href="http://aws.amazon.com/elasticmapreduce/">
   AWS EMR
  </a>
  A web service that makes it easy to quickly and cost-effectively process vast amounts of data.
 </li>
 <li>
  <a href="https://flink.apache.org/">
   Flink
  </a>
  An open source platform for scalable batch and stream data processing.
 </li>
 <li>
  <a href="https://tez.apache.org/">
   Tez
  </a>
  An application framework which allows for a complex directed-acyclic-graph of tasks for processing data.
 </li>
 <li>
  Batch ML
  <ul>
   <li>
    <a href="http://www.h2o.ai/">
     H2O
    </a>
    Fast scalable machine learning API for smarter applications.
   </li>
   <li>
    <a href="http://mahout.apache.org/">
     Mahout
    </a>
    An environment for quickly creating scalable performant machine learning applications.
   </li>
   <li>
    <a href="https://spark.apache.org/docs/1.2.1/mllib-guide.html">
     Spark MLlib
    </a>
    Spark’s scalable machine learning library consisting of common learning algorithms and utilities, including classification, regression, clustering, collaborative filtering, dimensionality reduction, as well as underlying optimization primitives.
   </li>
  </ul>
 </li>
 <li>
  Batch Graph
  <ul>
   <li>
    <a href="https://dato.com/products/create/">
     GraphLab Create
    </a>
    A machine learning platform that enables data scientists and app developers to easily create intelligent apps at scale.
   </li>
   <li>
    <a href="http://giraph.apache.org/">
     Giraph
    </a>
    An iterative graph processing system built for high scalability.
   </li>
   <li>
    <a href="https://spark.apache.org/graphx/">
     Spark GraphX
    </a>
    Apache Spark's API for graphs and graph-parallel computation.
   </li>
  </ul>
 </li>
 <li>
  Batch SQL
  <ul>
   <li>
    <a href="https://prestodb.io/docs/current/index.html">
     Presto
    </a>
    A distributed SQL query engine designed to query large data sets distributed over one or more heterogeneous data sources.
   </li>
   <li>
    <a href="http://hive.apache.org">
     Hive
    </a>
    Data warehouse software facilitates querying and managing large datasets residing in distributed storage.
    <ul>
     <li>
      <a href="https://github.com/myui/hivemall">
       Hivemall
      </a>
      Scalable machine learning library for Hive/Hadoop.
      <sup>
       &#9733 391, pushed 2 days ago
      </sup>
     </li>
     <li>
      <a href="https://github.com/dropbox/PyHive">
       PyHive
      </a>
      Python interface to Hive and Presto.
      <sup>
       &#9733 179, pushed 22 days ago
      </sup>
     </li>
    </ul>
   </li>
   <li>
    <a href="https://drill.apache.org/">
     Drill
    </a>
    Schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage.
   </li>
  </ul>
 </li>
</ul>
<h1>
 Charts and Dashboards
</h1>
<ul>
 <li>
  <a href="http://www.highcharts.com/">
   Highcharts
  </a>
  A charting library written in pure JavaScript, offering an easy way of adding interactive charts to your web site or web application.
 </li>
 <li>
  <a href="http://www.zingchart.com/">
   ZingChart
  </a>
  Fast JavaScript charts for any data set.
 </li>
 <li>
  <a href="http://c3js.org">
   C3.js
  </a>
  D3-based reusable chart library.
 </li>
 <li>
  <a href="http://d3js.org/">
   D3.js
  </a>
  A JavaScript library for manipulating documents based on data.
  <ul>
   <li>
    <a href="http://d3plus.org">
     D3Plus
    </a>
    D3's simplier, easier to use cousin. Mostly predefined templates that you can just plug data in.
   </li>
  </ul>
 </li>
 <li>
  <a href="http://smoothiecharts.org">
   SmoothieCharts
  </a>
  A JavaScript Charting Library for Streaming Data.
 </li>
 <li>
  <a href="https://github.com/stitchfix/pyxley">
   PyXley
  </a>
  Python helpers for building dashboards using Flask and React
  <sup>
   &#9733 1426, pushed 43 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/plotly/dash">
   Plotly
  </a>
  Flask, JS, and CSS boilerplate for interactive, web-based visualization apps in Python
  <sup>
   &#9733 149, pushed 13 days ago
  </sup>
 </li>
</ul>
<h1>
 Workflow
</h1>
<ul>
 <li>
  <a href="https://github.com/spotify/luigi">
   Luigi
  </a>
  Luigi is a Python module that helps you build complex pipelines of batch jobs.
  <ul>
   <li>
    <a href="https://github.com/seatgeek/cronq">
     CronQ
    </a>
    An application cron-like system.
    <a href="http://chairnerd.seatgeek.com/building-out-the-seatgeek-data-pipeline/">
     Used
    </a>
    w/Luige
    <sup>
     &#9733 35, pushed 25 days ago
    </sup>
   </li>
  </ul>
  <sup>
   &#9733 4510, pushed 1 days ago
  </sup>
 </li>
 <li>
  <a href="http://www.cascading.org/">
   Cascading
  </a>
  Java based application development platform.
 </li>
 <li>
  <a href="https://github.com/airbnb/airflow">
   Airflow
  </a>
  Airflow is a system to programmaticaly author, schedule and monitor data pipelines.
  <sup>
   &#9733 2594, pushed 2 days ago
  </sup>
 </li>
 <li>
  <a href="https://azkaban.github.io/">
   Azkaban
  </a>
  Azkaban is a batch workflow job scheduler created at LinkedIn to run Hadoop jobs. Azkaban resolves the ordering through job dependencies and provides an easy to use web user interface to maintain and track your workflows.
 </li>
 <li>
  <a href="http://oozie.apache.org/">
   Oozie
  </a>
  Oozie is a workflow scheduler system to manage Apache Hadoop jobs
 </li>
</ul>
<h1>
 ELK Elastic Logstash Kibana
</h1>
<ul>
 <li>
  <a href="https://github.com/pblittle/docker-logstash">
   docker-logstash
  </a>
  A highly configurable logstash (1.4.4) docker image running Elasticsearch (1.7.0) and Kibana (3.1.2).
  <sup>
   &#9733 227, pushed 134 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/jprante/elasticsearch-jdbc">
   elasticsearch-jdbc
  </a>
  JDBC importer for Elasticsearch
  <sup>
   &#9733 1360, pushed 23 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/zombodb/zombodb">
   ZomboDB
  </a>
  Postgres Extension that allows creating an index backed by Elasticsearch
  <sup>
   &#9733 716, pushed 2 days ago
  </sup>
 </li>
</ul>
<h1>
 Docker
</h1>
<ul>
 <li>
  <a href="https://github.com/aerofs/gockerize">
   Gockerize
  </a>
  Package golang service into minimal docker containers
  <sup>
   &#9733 584, pushed 78 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/ClusterHQ/flocker">
   Flocker
  </a>
  Easily manage Docker containers & their data
  <sup>
   &#9733 2285, pushed 1 days ago
  </sup>
 </li>
 <li>
  <a href="http://rancher.com/rancher-os/">
   Rancher
  </a>
  RancherOS is a 20mb Linux distro that runs the entire OS as Docker containers
 </li>
 <li>
  <a href="http://www.kontena.io/">
   Kontena
  </a>
  Application Containers for Masses
 </li>
 <li>
  <a href="https://github.com/weaveworks/weave">
   Weave
  </a>
  Weaving Docker containers into applications http://www.weave.works/
  <sup>
   &#9733 4182, pushed 4 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/CenturyLinkLabs/zodiac">
   Zodiac
  </a>
  A lightweight tool for easy deployment and rollback of dockerized applications
  <sup>
   &#9733 133, pushed 259 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/google/cadvisor">
   cAdvisor
  </a>
  Analyzes resource usage and performance characteristics of running containers
  <sup>
   &#9733 3861, pushed 2 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/shinymayhem/micro-s3-persistence">
   Micro S3 persistence
  </a>
  Docker microservice for saving/restoring volume data to S3
  <sup>
   &#9733 8, pushed 391 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/tutumcloud/dockup">
   Dockup
  </a>
  Docker image to backup/restore your Docker container volumes to AWS S3
  <sup>
   &#9733 111, pushed 40 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/grammarly/rocker-compose">
   Rocker-compose
  </a>
  Docker composition tool with idempotency features for deploying apps composed of multiple containers.
  <sup>
   &#9733 296, pushed 10 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/hashicorp/nomad">
   Nomad
  </a>
  Nomad is a cluster manager, designed for both long lived services and short lived batch processing workloads
  <sup>
   &#9733 1537, pushed 1 days ago
  </sup>
 </li>
 <li>
  <a href="https://imagelayers.io/">
   ImageLayers
  </a>
  Vizualize docker images and the layers that compose them
 </li>
</ul>
<h1>
 Datasets
</h1>
<h2>
 Realtime
</h2>
<ul>
 <li>
  <a href="https://instagram.com/developer/realtime/">
   Instagram Realtime
  </a>
  Real-time photo updates provide your application with instant notifications of new photos as they are posted on Instagram.
 </li>
 <li>
  <a href="https://dev.twitter.com/streaming/overview">
   Twitter Realtime
  </a>
  The Streaming APIs give developers low latency access to Twitter’s global stream of Tweet data.
 </li>
 <li>
  <a href="https://www.firebase.com/docs/open-data/">
   Firebase Realtime
  </a>
  Airport delays, Parking,  Cryptocurrencies, Earthquakes, Transit, Weather
 </li>
 <li>
  <a href="https://github.com/Interana/eventsim">
   Eventsim
  </a>
  Event data simulator. Generates a stream of pseudo-random events from a set of users, designed to simulate web traffic.
  <sup>
   &#9733 125, pushed 5 days ago
  </sup>
 </li>
 <li>
  <a href="https://www.reddit.com/r/datasets/comments/3mk1vg/realtime_data_is_available_including_comments/">
   Reddit
  </a>
  Real-time data is available including comments, submissions and links posted to reddit
 </li>
</ul>
<h2>
 Data Dumps
</h2>
<ul>
 <li>
  <a href="https://www.githubarchive.org/">
   GitHub Archive
  </a>
  GitHub's public timeline since 2011, updated every hour
 </li>
 <li>
  <a href="https://commoncrawl.org/">
   Common Crawl
  </a>
  Open source repository of web crawl data
 </li>
 <li>
  <a href="https://dumps.wikimedia.org/enwiki/latest/">
   Wikipedia
  </a>
  Wikipedia's complete copy of all wikis, in the form of wikitext source and metadata embedded in XML. A number of raw database tables in SQL form are also available.
 </li>
</ul>
<h1>
 Monitoring
</h1>
<h2>
 Prometheus
</h2>
<ul>
 <li>
  <a href="https://github.com/prometheus/prometheus">
   Prometheus.io
  </a>
  An open-source service monitoring system and time series database
  <sup>
   &#9733 4515, pushed 2 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/prometheus/haproxy_exporter">
   HAProxy Exporter
  </a>
  Simple server that scrapes HAProxy stats and exports them via HTTP for Prometheus consumption
  <sup>
   &#9733 38, pushed 5 days ago
  </sup>
 </li>
</ul>
<p>
 Cheers to
 <a href="http://insightdataengineering.com/blog/pipeline_map.html">
  The Data Engineering Ecosystem: An Interactive Map
 </a>
</p>
<p>
 Inspired by the
 <a href="https://github.com/sindresorhus/awesome">
  awesome
 </a>
 list. Created by
 <a href="http://insightdataengineering.com">
  Insight Data Engineering
 </a>
 fellows.
</p>
<h2>
 License
</h2>
<p>
 <a href="http://creativecommons.org/publicdomain/zero/1.0/">
  <img alt="CC0" src="http://i.creativecommons.org/p/zero/1.0/88x31.png"/>
 </a>
</p>
<p>
 To the extent possible under law,
 <a href="https://github.com/igorbarinov/">
  Igor Barinov
 </a>
 has waived all copyright and related or neighboring rights to this work.
</p>
<p>
 <a href="https://bitdeli.com/free" title="Bitdeli Badge">
  <img alt="Bitdeli Badge" src="https://d2weczhvl823v0.cloudfront.net/igorbarinov/awesome-data-engineering/trend.png"/>
 </a>
</p>
