---
layout: post
title: "Walk on the web flow 20231107"
date: 2023-11-07
tags : Llm GenerativeAI Curl Cleancode Functionnal Fp Webcrawler Oreilly Knowledge Jvmsummit Conference Graalvm C4 Structurizr Architecture Hotswap JRebel Github Java Baremetal Stream Gatherers Jep461 Microservice Viktorklang Profiler Memoryleak Debug Jeyzer Jvm Tuning Performance Alibaba Offheap Api Asynchronous Tdd Doubleloop Langchain4j Java21 Switch Patternmatching Countdown Openai Jmc Jrockit Javamissioncontrol Jacoco Deadcode Coverage Kappa Deeplearning4j Encog Weka Ai Machinelearning Guillaumelaforge Lizraes
---

## Architecture  

Design a web crawler    
* [https://medium.com/@sureshpodeti/system-design-web-crawler-4daebb84cd62](https://medium.com/@sureshpodeti/system-design-web-crawler-4daebb84cd62)

GraalVM explain    
* [https://www.slideshare.net/martintoshev/jvm-the-graal-vm](https://www.slideshare.net/martintoshev/jvm-the-graal-vm)    

JVM summit Keynote    
* [https://www.youtube.com/watch?v=Ma0NtbG0mHY&list=PLX8CzqL3ArzW90jKUCf4H6xCKpStxsOzp&index=5](https://www.youtube.com/watch?v=Ma0NtbG0mHY&list=PLX8CzqL3ArzW90jKUCf4H6xCKpStxsOzp&index=5)    

Microservice definition (Viktor Klang)    
* [https://viktorklang.com/blog/Microservices-definition.html](https://viktorklang.com/blog/Microservices-definition.html)    

Asynchronous API design     
* [https://blog.stackademic.com/asynchronous-api-design-best-practices-server-sent-event-sse-for-real-time-communication-a3a3e20233d2](https://blog.stackademic.com/asynchronous-api-design-best-practices-server-sent-event-sse-for-real-time-communication-a3a3e20233d2)    

Architecture Kappa     
* [https://www.infoq.com/presentations/kappa-architecture-1/](https://www.infoq.com/presentations/kappa-architecture-1/)     

## Dev   

Clean Code, Two Decades Later (includes functionnal programming)    
* [https://www.youtube.com/watch?v=CRvtx0MeGCY](https://www.youtube.com/watch?v=CRvtx0MeGCY)     

Jvm Hotswap guide     
* [https://www.jrebel.com/blog/java-hotswap-guide](https://www.jrebel.com/blog/java-hotswap-guide)     

Bare metal Java (devoxx)    
* [https://www.youtube.com/watch?v=pBe407IRA4M](https://www.youtube.com/watch?v=pBe407IRA4M)    

Design of Java futur Stream gatherers (Jep 461)    
* [https://cr.openjdk.org/~vklang/Gatherers.html](https://cr.openjdk.org/~vklang/Gatherers.html)
* [https://www.youtube.com/watch?v=8fMFa6OqlY8](https://www.youtube.com/watch?v=8fMFa6OqlY8) 

Don't bindly trust your Java profiler    
* [https://stefan-marr.de/2023/09/dont-blindly-trust-your-profiler/](https://stefan-marr.de/2023/09/dont-blindly-trust-your-profiler/)    

Some articles about memory leak         
* Off heap memory leak analysis [https://medium.com/pinterest-engineering/lessons-from-debugging-a-tricky-direct-memory-leak-f638c722d9f2](https://medium.com/pinterest-engineering/lessons-from-debugging-a-tricky-direct-memory-leak-f638c722d9f2)   
* [https://dip-mazumder.medium.com/java-memory-leaks-a-comprehensive-guide-to-causes-and-solutions-17e319523499](https://dip-mazumder.medium.com/java-memory-leaks-a-comprehensive-guide-to-causes-and-solutions-17e319523499)      

Alibaba on JVM performance tuning     
* [https://www.alibabacloud.com/blog/how-to-properly-plan-jvm-performance-tuning_594663](https://www.alibabacloud.com/blog/how-to-properly-plan-jvm-performance-tuning_594663)     

TDD double loop refactoring     
* [https://blog.octo.com/le-double-cycle-tdd/](https://blog.octo.com/le-double-cycle-tdd/)     
* [http://coding-is-like-cooking.info/2013/04/outside-in-development-with-double-loop-tdd/](http://coding-is-like-cooking.info/2013/04/outside-in-development-with-double-loop-tdd/)    

Java 21 solving countdown problem with new stuff (switch, records, pattern matching, ....)     
* [https://inside.java/2023/11/03/countdown-haskell-java/](https://inside.java/2023/11/03/countdown-haskell-java/)     
* [https://github.com/java/samples/blob/main/countdown-problem-java21/CountDownProblem.java](https://github.com/java/samples/blob/main/countdown-problem-java21/CountDownProblem.java)       

## Tool   

Curl lifecycle :    
* [https://daniel.haxx.se/blog/2023/10/24/curl-from-start-to-end/](https://daniel.haxx.se/blog/2023/10/24/curl-from-start-to-end/)    

Tool for C4 architecture model     
* [https://github.com/structurizr/java](https://github.com/structurizr/java)    

Java tool Jeyzer (incident analysis solution)     
* [https://jeyzer.org/](https://jeyzer.org/)
* [https://github.com/jeyzer-community](https://github.com/jeyzer-community)

Langchain4j
* Home project [https://github.com/langchain4j/langchain4j](https://github.com/langchain4j/langchain4j)    
* [https://www.baeldung.com/java-langchain-basics](https://www.baeldung.com/java-langchain-basics)    
* Liz Raes talk at Devoxx [https://youtu.be/BD1MSLbs9KE?si=Hhc0vamMwCkEsXlc](https://youtu.be/BD1MSLbs9KE?si=Hhc0vamMwCkEsXlc)     
* Guillaume Laforge article [https://glaforge.dev/posts/2023/09/25/discovering-langchain4j/](https://glaforge.dev/posts/2023/09/25/discovering-langchain4j/)    

Piece of history (from JRockit) of JMC     
* [https://fr.slideshare.net/DavidBuck7/jdk-mission-control-where-we-are-where-we-are-going-code-one-2019](https://fr.slideshare.net/DavidBuck7/jdk-mission-control-where-we-are-where-we-are-going-code-one-2019)     

Use Jacoco to find dead code     
* [https://foojay.io/today/how-to-find-dead-code-in-your-java-services/](https://foojay.io/today/how-to-find-dead-code-in-your-java-services/)     

Some Java Lib for AI, machine learning Development :    
* Deeplearning4j : [https://github.com/deeplearning4j/deeplearning4j](https://github.com/deeplearning4j/deeplearning4j)    
* Weka [https://www.cs.waikato.ac.nz/ml/weka/](https://www.cs.waikato.ac.nz/ml/weka/)    
* Encog : [https://www.heatonresearch.com/encog/](https://www.heatonresearch.com/encog/)    

## Various

LLM and generative AI blog post    
* [https://www.confluent.io/blog/get-started-with-generative-ai/](https://www.confluent.io/blog/get-started-with-generative-ai/)    

Oreilly about knowledge     
* [https://www.forbes.com/sites/brucerogers/2023/09/21/how-oreilly-media-helped-change-the-world-by-sharing-knowledge/?sh=4a05c95274f9](https://www.forbes.com/sites/brucerogers/2023/09/21/how-oreilly-media-helped-change-the-world-by-sharing-knowledge/?sh=4a05c95274f9)    

Tips for your Github profile    
* [https://github.blog/2023-10-26-5-tips-for-making-your-github-profile-page-accessible/](https://github.blog/2023-10-26-5-tips-for-making-your-github-profile-page-accessible/)     

OpenAI interview     
* [https://www.wired.com/story/what-openai-really-wants/](https://www.wired.com/story/what-openai-really-wants/)     
