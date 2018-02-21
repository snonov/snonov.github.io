---
layout: post
title: "Walk on the web flow 20171002"
date: 2017-10-02
tags : Grpc Spring5 Fiber Loom Quantum Nginx Certification Strata Time Outofmemory Java9 Java Briangoetz Patternmatching Machinelearning AWS Coursera Graphql API Webflowwalk
---

## Architecture

Comment choisir les données et API à exposer en premier
[https://www.programmableweb.com/news/what-data-and-services-should-your-api-expose-first/analysis/2017/09/27](https://www.programmableweb.com/news/what-data-and-services-should-your-api-expose-first/analysis/2017/09/27)

Quelles architectures pour vos API
[https://www.programmableweb.com/news/how-to-choose-architectural-styles-and-specification-formats-your-apis/analysis/2017/09/27](https://www.programmableweb.com/news/how-to-choose-architectural-styles-and-specification-formats-your-apis/analysis/2017/09/27)

Passage de Coursera au GraphQL
[https://www.infoq.com/presentations/coursera-graphql](https://www.infoq.com/presentations/coursera-graphql)

Petit record pour du machine learning
Nb de CPU : more than 1,100,000 vCPUs on Amazon EC2 Spot Instances running in a single AWS region
Dataset : The models have been applied to 17 years of computer science journal abstracts (533,560 documents and 32,551,540 words) and full text papers from the NIPS (Neural Information Processing Systems) Conference (2,484 documents and 3,280,697 words)
[https://aws.amazon.com/fr/blogs/aws/natural-language-processing-at-clemson-university-1-1-million-vcpus-ec2-spot-instances/](https://aws.amazon.com/fr/blogs/aws/natural-language-processing-at-clemson-university-1-1-million-vcpus-ec2-spot-instances/)

## Dev

Pattern matching en Java par Brian Goetz
[https://www.infoq.com/news/2017/09/pattern-matching-for-java](https://www.infoq.com/news/2017/09/pattern-matching-for-java)

Java 9 Unified Logging
[http://blog.codefx.org/java/unified-logging-with-the-xlog-option/](http://blog.codefx.org/java/unified-logging-with-the-xlog-option/)

Top 5 Features Java Developers Miss in C#
[http://blog.takipi.com/c-vs-java-the-top-5-features-java-developers-miss-in-c/](http://blog.takipi.com/c-vs-java-the-top-5-features-java-developers-miss-in-c/)

Java OutOfMemory, symptomes, analyse
* [https://plumbr.eu/outofmemoryerror](https://plumbr.eu/outofmemoryerror)
* [https://stackify.com/memory-leaks-java/](https://stackify.com/memory-leaks-java/)
* [https://stackify.com/java-memory-leaks-solutions/](https://stackify.com/java-memory-leaks-solutions/)

pour comprendre : [Times: user=4.21 sys=0.03, real=0.75 secs]
* [https://dzone.com/articles/gc-explained-times](https://dzone.com/articles/gc-explained-times)

## Tool

Spring 5 est sortie
[https://spring.io/blog/2017/09/28/spring-framework-5-0-goes-ga](https://spring.io/blog/2017/09/28/spring-framework-5-0-goes-ga)

gRPC framework
[https://grpc.io/](https://grpc.io/)

Apache Ignite
[https://ignite.apache.org/](https://ignite.apache.org/)

Jetty et son LeakDetector
[http://www.eclipse.org/jetty/javadoc/current/org/eclipse/jetty/util/LeakDetector.html](http://www.eclipse.org/jetty/javadoc/current/org/eclipse/jetty/util/LeakDetector.html)

## Conférence

Strata 2017, les temps forts
[https://www.oreilly.com/ideas/highlights-from-strata-ny-2017](https://www.oreilly.com/ideas/highlights-from-strata-ny-2017)

## Certifications

Feedback pour le passage de certificaiton AWS
[https://howtotrainyourjava.com/2017/09/28/how-to-pass-aws-certified-developer-and-architect-exams/](https://howtotrainyourjava.com/2017/09/28/how-to-pass-aws-certified-developer-and-architect-exams/)

Passage de certificaiton Java 8
[https://dzone.com/articles/prepare-yourself-for-java-8-certification](https://dzone.com/articles/prepare-yourself-for-java-8-certification)

## Various

Keynote NGinx sur l'open source
[https://www.nginx.com/blog/the-future-of-open-source-at-nginx/](https://www.nginx.com/blog/the-future-of-open-source-at-nginx/)

Data source : YAGO is a large semantic knowledge base, derived from Wikipedia, WordNet, WikiData, GeoNames, and other data sources.
[https://github.com/yago-naga/yago3](https://github.com/yago-naga/yago3)

Pour le futur Quantum computing
[https://vimeo.com/235197584](https://vimeo.com/235197584)

Appel à échanges et discusison : “Project Loom”, which is intended to add alternative, user-mode thread
implementations, delimited continuations (coroutines) and other constructs
involving call-stack manipulation, such as tail calls, to the Java platform
* [http://cr.openjdk.java.net/~rpressler/loom/Loom-Proposal.html](http://cr.openjdk.java.net/~rpressler/loom/Loom-Proposal.html)
* [http://mail.openjdk.java.net/pipermail/discuss/2017-September/004390.html](http://mail.openjdk.java.net/pipermail/discuss/2017-September/004390.html)

