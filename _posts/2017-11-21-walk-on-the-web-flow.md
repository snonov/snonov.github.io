---
layout: post
title: "Walk on the web flow 20171121"
date: 2017-11-21
tags : Apache Gearpump Lambda Netflixoss NetFlix AWS Kibana Grafana Garbagecollector Zgc Performance Java10 Java Eventdriven Kafka Event Webflowwalk
---

## Architecture

Event driven d'accord mais pourquoi
[https://jobs.zalando.com/tech/blog/why-event-driven/index.html](https://jobs.zalando.com/tech/blog/why-event-driven/index.html)

Les transactions dans Kafka
[https://www.confluent.io/blog/transactions-apache-kafka/](https://www.confluent.io/blog/transactions-apache-kafka/)

## Dev

Java 10 is coming (pattern matching, var, ...)
[https://medium.com/codefx-weekly/java-10-is-coming-e6807eb5de6e](https://medium.com/codefx-weekly/java-10-is-coming-e6807eb5de6e)
[https://blog.codefx.org/java/java-10-var-type-inference/](https://blog.codefx.org/java/java-10-var-type-inference/)
[https://www.infoq.com/news/2017/11/Java10JEPs](https://www.infoq.com/news/2017/11/Java10JEPs)

Dont la [JEP 312](http://openjdk.java.net/jeps/312) pour ceux intéressé par les aspects performance
* Reducing the impact of acquiring a stack trace sample (e.g. for profiling)
* Better stack trace sampling by reducing reliance on signals.
* Improving biased locking by only stopping individual threads for revoking biases.
* Removing some memory barriers from the JVM

Nouveau Garbage Collector ? Le ZGC
[https://www.infoq.com/news/2017/11/zgc](https://www.infoq.com/news/2017/11/zgc)

## Tool

Grafana vs Kibana
[http://blog.takipi.com/grafana-vs-kibana-how-to-get-the-most-out-of-your-data-visualization/](http://blog.takipi.com/grafana-vs-kibana-how-to-get-the-most-out-of-your-data-visualization/)

AWS cost explorer
[https://aws.amazon.com/fr/blogs/aws/new-interactive-aws-cost-explorer-api/](https://aws.amazon.com/fr/blogs/aws/new-interactive-aws-cost-explorer-api/)
[https://aws.amazon.com/fr/blogs/aws/the-new-cost-explorer-for-aws/](https://aws.amazon.com/fr/blogs/aws/the-new-cost-explorer-for-aws/)

Contribuer à Netflix OSS ?
[https://medium.com/netflix-techblog/making-it-easier-to-contribute-to-netflix-oss-cffc3276974a](https://medium.com/netflix-techblog/making-it-easier-to-contribute-to-netflix-oss-cffc3276974a)

AWS Lambda, le cold start
[http://blog.xebia.fr/2017/11/20/serverless-aws-lambda-vous-saurez-tout-sur-le-cold-start/](http://blog.xebia.fr/2017/11/20/serverless-aws-lambda-vous-saurez-tout-sur-le-cold-start/)

real-time big data streaming engine
[https://gearpump.apache.org/overview.html](https://gearpump.apache.org/overview.html)

