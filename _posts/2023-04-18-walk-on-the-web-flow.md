---
layout: post
title: "Walk on the web flow 20230418"
date: 2023-04-18 
tags : Diagram Sequence Devoxx Rex Keyboard Typing Web Fingerprint Miller File Wrangle Java17 Performance Git Springboot Joshlong Jmm Memory Java Micrometer Observability Developper Oracle Licenses Yaml Docker Distroless Kubernetes Migration Database Flyway Liquibase Loom Virtualthread Cloud Localstack Aws Distributedsystem Monorepo Bazel Google Buck Meta Ratelimiter Enum Twitter Opensource Recommandation Postgresql Test Fakes Mocks Spies Stubs Lamportclock Gof Designpattern dp
---

## Architecture  

Explaining Distributed Systems Like I'm 5    
* [https://www.youtube.com/watch?v=CESKgdNiKJw](https://www.youtube.com/watch?v=CESKgdNiKJw)    

Design a rate limiter    
* [https://medium.com/](https://medium.com/)@meenak1996/system-design-of-rate-limiter-from-basic-to-distributed-environment-44e05a42d2dc    

Lamport clock : Use logical timestamps as a version for a value to allow ordering of values across servers    
* [https://en.wikipedia.org/wiki/Lamport_timestamp](https://en.wikipedia.org/wiki/Lamport_timestamp)    
* [https://martinfowler.com/articles/patterns-of-distributed-systems/lamport-clock.html](https://martinfowler.com/articles/patterns-of-distributed-systems/lamport-clock.html)    
* [https://medium.com/](https://medium.com/)@girinath2452001/the-importance-of-lamport-clocks-in-distributed-systems-374019ac4081     

Review security aspect     
* [https://blog.bytebytego.com/p/password-session-cookie-token-jwt](https://blog.bytebytego.com/p/password-session-cookie-token-jwt)    
* [https://blog.bytebytego.com/p/password-session-cookie-token-jwt-ec1](https://blog.bytebytego.com/p/password-session-cookie-token-jwt-ec1)   

## Dev   

Java 17 perfomance    
* [https://ionutbalosin.com/2023/03/jvm-performance-comparison-for-jdk-17/](https://ionutbalosin.com/2023/03/jvm-performance-comparison-for-jdk-17/)     

JMM java memory model resources page    
* [http://www.cs.umd.edu/](http://www.cs.umd.edu/)~pugh/java/memoryModel/    

Be awre of Yaml trap     
* [https://ruudvanasseldonk.com/2023/01/11/the-yaml-document-from-hell](https://ruudvanasseldonk.com/2023/01/11/the-yaml-document-from-hell)    

Docker and distroless. No package manager, no shell, more secure but how to debug ?    
* [https://blog.frankel.ch/fearless-distroless/](https://blog.frankel.ch/fearless-distroless/)      
* [https://github.com/GoogleContainerTools/distroless](https://github.com/GoogleContainerTools/distroless)     

Loom is coming, go to virtual thread, migration tips    
* [https://devblogs.microsoft.com/java/embracing-virtual-threads-migration-tips-for-java-developers/](https://devblogs.microsoft.com/java/embracing-virtual-threads-migration-tips-for-java-developers/)   

Zoom on Java Enum     
* [https://foojay.io/today/hidden-beauties-of-java-enums/](https://foojay.io/today/hidden-beauties-of-java-enums/)   

Test with fakes, mocks, Spies and stubs    
* [https://github.com/pkainulainen/introduction-to-test-doubles](https://github.com/pkainulainen/introduction-to-test-doubles)    
* [https://www.petrikainulainen.net/blog/](https://www.petrikainulainen.net/blog/)    

Revisiting Gang of four aka GoF Design pattern with modern Java     
* Mario Fusco [https://github.com/mariofusco/from-gof-to-lambda](https://github.com/mariofusco/from-gof-to-lambda)
* Rémi Forax [https://github.com/forax/design-pattern-reloaded](https://github.com/forax/design-pattern-reloaded)
* Edson Yanaga [https://github.com/yanaga/revisiting-design-patterns](https://github.com/yanaga/revisiting-design-patterns)

## Tool   

Automatically generate interactive sequence diagrams of your Java code's runtime behavior : Appmap    
* [https://dev.to/appmap/automatically-generate-interactive-sequence-diagrams-of-your-java-codes-runtime-behavior-2jg0](https://dev.to/appmap/automatically-generate-interactive-sequence-diagrams-of-your-java-codes-runtime-behavior-2jg0)    
* [https://plugins.jetbrains.com/plugin/16701-appmap](https://plugins.jetbrains.com/plugin/16701-appmap)    

Miller, tool to wrangle CSV, TSV, JSON files    
* [https://github.com/johnkerl/miller](https://github.com/johnkerl/miller)    

Josh Long Git springboot tool    
* [https://github.com/joshlong/git-spring-boot-starter](https://github.com/joshlong/git-spring-boot-starter)    

Micrometer, application observability    
* [https://github.com/micrometer-metrics/micrometer](https://github.com/micrometer-metrics/micrometer)    
* [https://foojay.io/today/not-your-grandfathers-logs-a-java-librarys-new-approach-to-observability/](https://foojay.io/today/not-your-grandfathers-logs-a-java-librarys-new-approach-to-observability/)    

Collection of developper tools     
* [https://digma.ai/blog/the-modern-developer-stack-2022-edition/](https://digma.ai/blog/the-modern-developer-stack-2022-edition/)   

Databases migration tools    
* [https://www.baeldung.com/liquibase-vs-flyway](https://www.baeldung.com/liquibase-vs-flyway)    
* [https://www.liquibase.org/](https://www.liquibase.org/)    
* [https://flywaydb.org/](https://flywaydb.org/)    

Tool LocalStack : A fully functional local cloud stack Develop and test your cloud and serverless apps offline    
* [https://localstack.cloud/](https://localstack.cloud/)    
* [https://www.infoq.com/news/2023/04/localstack-aws-version-two-ga](https://www.infoq.com/news/2023/04/localstack-aws-version-two-ga)     
* ok but if i'm using Azure and not AWS ... [https://stackoverflow.com/questions/53888830/local-cloud-stack-for-azure-similar-to-localstack-for-aws](https://stackoverflow.com/questions/53888830/local-cloud-stack-for-azure-similar-to-localstack-for-aws)    

Monorepo tools to help    
* what is a monorepo [https://medium.com/](https://medium.com/)@deshpande.sakalya/what-is-a-monorepo-db434da94e5d     
* Bazel (Goole) : [https://bazel.build/](https://bazel.build/)   
* Buck (Meta) : [https://buck.build/](https://buck.build/)   

PostgreSQL super power   
* [https://event-driven.io/en/postgres_superpowers/](https://event-driven.io/en/postgres_superpowers/)    

## Various

Devoxx Paris 2023 was last week, some REX    
* [https://github.com/Ardemius/meetups-talks-conferences-notes/tree/master/202304-devoxx-france](https://github.com/Ardemius/meetups-talks-conferences-notes/tree/master/202304-devoxx-france)    
* [https://philippart-s.github.io/blog/articles/conf%C3%A9rences/devoxx-2023/](https://philippart-s.github.io/blog/articles/conf%C3%A9rences/devoxx-2023/)     
 
Learn, score and statistics keyboard typing test    
* [https://www.keybr.com/](https://www.keybr.com/)   

Web fingerprinting     
* [https://www.bitestring.com/posts/2023-03-19-web-fingerprinting-is-worse-than-I-thought.html](https://www.bitestring.com/posts/2023-03-19-web-fingerprinting-is-worse-than-I-thought.html)    

Learn git with gaming    
* [https://ohmygit.org/](https://ohmygit.org/)    

Various Java Oracle Licenses, to find your path    
* [https://redresscompliance.com/oracle-java-licensing-changes-explaned-free/](https://redresscompliance.com/oracle-java-licensing-changes-explaned-free/)    

Twitter  open sources recommandation algorithm     
* [https://www.infoq.com/news/2023/04/twitter-algorithm/](https://www.infoq.com/news/2023/04/twitter-algorithm/)    
* [https://blog.twitter.com/en_us/topics/company/2023/a-new-era-of-transparency-for-twitter](https://blog.twitter.com/en_us/topics/company/2023/a-new-era-of-transparency-for-twitter)    
* [https://github.com/twitter/the-algorithm](https://github.com/twitter/the-algorithm)    

