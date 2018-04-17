---
layout: post
title: "Zoom on Apache Parquet"
date: 2018-04-17
tags : Zoomon Hadoop Apache Parquet Avro Impala Twitter Cloudera
---

Zoom on Apache Parquet     

Apache Parquet is a columnar storage format available to any project in the Hadoop ecosystem, regardless of    
* the choice of data processing framework
* data model
* programming language

## Parquet inspiration     

Built on Twitter and Cloudera collaboration, first version Apache parquet 1.0 was released on july 2013.

Inspired from Dremel google paper     
* Dremel paper [http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf][http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf]http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf)
* Twitter blog article [https://blog.twitter.com/engineering/en_us/a/2013/dremel-made-simple-with-parquet.html](https://blog.twitter.com/engineering/en_us/a/2013/dremel-made-simple-with-parquet.html][https://blog.twitter.com/engineering/en_us/a/2013/dremel-made-simple-with-parquet.html]https://blog.twitter.com/engineering/en_us/a/2013/dremel-made-simple-with-parquet.html)
* Twitter blog article [https://blog.twitter.com/engineering/en_us/a/2013/announcing-parquet-10-columnar-storage-for-hadoop.html](https://blog.twitter.com/engineering/en_us/a/2013/announcing-parquet-10-columnar-storage-for-hadoop.html][https://blog.twitter.com/engineering/en_us/a/2013/announcing-parquet-10-columnar-storage-for-hadoop.html]https://blog.twitter.com/engineering/en_us/a/2013/announcing-parquet-10-columnar-storage-for-hadoop.html)

## Main references urls     

* Apache Parquet [https://parquet.apache.org/]https://parquet.apache.org/
* Source code parquet-compatibility (compatibility tests to make sur C and Java implementations can read each other) [https://github.com/Parquet/parquet-compatibility](https://github.com/Parquet/parquet-compatibility)
* Source code Parquet-MR (java implementation of the Parquet format) [https://github.com/apache/parquet-mr](https://github.com/apache/parquet-mr)
* Source code Parquet-format (contains all Thrift definitions) [https://github.com/apache/parquet-format](https://github.com/apache/parquet-format)

Cloudera supports some but not all of the object models from the upstream Parquet-MR project     
* parquet-avro
* parquet-thrift
* parquet-protobuf
* parquet-pig

The Impala and Hive object models that are built into those components, not available in external libraries (built in support)

## Ecosystem integration    

Data serialization libraries   
* Apache Avro [https://avro.apache.org/]https://avro.apache.org/
* Protocol Buffer [https://developers.google.com/protocol-buffers/]https://developers.google.com/protocol-buffers/
* Apache Thrift [https://thrift.apache.org/]https://thrift.apache.org/

But also integrate with Hadoop ecosystem (MapReduce, Pig, Hive and Impala)

## Resources    

### Projects    
 
* Simple Parquet manipulation project [https://github.com/paul-rogers/parquet-builder](https://github.com/paul-rogers/parquet-builder)
* Cloudera Parquet examples [https://github.com/cloudera/parquet-examples](https://github.com/cloudera/parquet-examples)

### Articles    

* Understanding how Parquet integrates with Avro, Thrift and Protocol Buffers [http://grepalex.com/2014/05/13/parquet-file-format-and-object-model/](http://grepalex.com/2014/05/13/parquet-file-format-and-object-model/)
* How to Write Data into Parquet [http://blog.antlypls.com/blog/2015/12/02/how-to-write-data-into-parquet/](http://blog.antlypls.com/blog/2015/12/02/how-to-write-data-into-parquet/)
* Open source columnar data format and AWS [https://blog.openbridge.com/how-to-be-a-hero-with-powerful-parquet-google-and-amazon-f2ae0f35ee04](https://blog.openbridge.com/how-to-be-a-hero-with-powerful-parquet-google-and-amazon-f2ae0f35ee04)
* Working with Parquet files [https://layer4.fr/blog/2016/11/19/parquet-files-hadoop/](https://layer4.fr/blog/2016/11/19/parquet-files-hadoop/)
* Hadoop API introduction [http://www.myhadoopexamples.com/2017/09/18/hdfs-java-hadoop-api/](http://www.myhadoopexamples.com/2017/09/18/hdfs-java-hadoop-api/)
