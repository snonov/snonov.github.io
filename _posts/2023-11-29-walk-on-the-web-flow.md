---
layout: post
title: "Walk on the web flow 20231129"
date: 2023-11-29
tags : Java Loom Virtualthread Storage Nosql Models Github Search Architecture Shell Nushell Sshx Sadservers Debug System Llm Langchain4j Jakartaee1 Jakarta Solid Curl Nix Juliaevans Flakes Optimisation Memq Pubsub Pinterest Ivarjacobson Alistaircockburn Agility Usecases Dependencymatrix Intellij Azcagit Gitops Modernizing Upgrade Olap Oltp Etl Engineering Blog Jvm Docker Image Size Microsoft Streams Collector Migration Terraform OpenTofu Teeing Senor Experience Work Datastore Newgeneration Roaring Bitmap Jfr Profiler Testkube Zgc Garbagecollector Trends Survey Javalin JReleaser Webserver Datastructure Tribuo Semantickernel Cinnamon Uber Pattern Distributedsystem Excalidraw Maven Kata Mutate Json Processor Jackson Fasterxml Latency Refactoring Mass Ai Aws Qcode CodeWhisperer
---

## Architecture  

Github search engine architecture    
* [https://scaleyourapp.com/system-design-github-code-search-engine/](https://scaleyourapp.com/system-design-github-code-search-engine/)     
* [https://github.blog/2023-02-06-the-technology-behind-githubs-new-code-search/](https://github.blog/2023-02-06-the-technology-behind-githubs-new-code-search/)    

Database cheatsheet (models and cloud providers)   
* [https://medium.com/](https://medium.com/)@sureshpodeti/database-cheat-sheet-db5363a7b997

Four kinds of optimisation    
* [https://tratt.net/laurie/blog/2023/four_kinds_of_optimisation.html](https://tratt.net/laurie/blog/2023/four_kinds_of_optimisation.html)     

Olap and Oltp in Etl   
* [https://medium.com/](https://medium.com/)@shivajiofficial5088/unraveling-olap-oltp-and-htap-in-etl-system-architecture-1b4fad936665     

New generation of datastore       
* [https://spinscale.de/posts/2022-08-02-the-new-generation-data-stores.html](https://spinscale.de/posts/2022-08-02-the-new-generation-data-stores.html)      
* [https://speakerdeck.com/spinscale/the-new-generation-of-data-stores-8a3b40b5-c3b8-4a1a-a4d9-df83d8aa6c25](https://speakerdeck.com/spinscale/the-new-generation-of-data-stores-8a3b40b5-c3b8-4a1a-a4d9-df83d8aa6c25)   

Java trends 2023    
* InfoQ [https://www.infoq.com/articles/java-trends-report-2023/](https://www.infoq.com/articles/java-trends-report-2023/)        
* JetBrain 2023 survey [https://www.jetbrains.com/lp/devecosystem-2023/java/](https://www.jetbrains.com/lp/devecosystem-2023/java/)    

Cinnamon, a new resiliency approach at Uber    
* [https://medium.com/](https://medium.com/)@bmarquie/bits-of-thought-cinnamon-a-new-resiliency-approach-at-uber-996c078b5b7b      

Pattern of distributed system    
* [https://martinfowler.com/articles/patterns-of-distributed-systems/](https://martinfowler.com/articles/patterns-of-distributed-systems/)     

Brief History of Jackson the JSON processor      
* [http://www.cowtowncoder.com/blog/archives/2013/08/entry_479.html](http://www.cowtowncoder.com/blog/archives/2013/08/entry_479.html)    
* [https://github.com/FasterXML/jackson](https://github.com/FasterXML/jackson)    

Mass refactoring with AI (Aws Qcode CodeWhisperer and Openrewrite)   
* [https://aws.amazon.com/fr/blogs/aws/upgrade-your-java-applications-with-amazon-q-code-transformation-preview/](https://aws.amazon.com/fr/blogs/aws/upgrade-your-java-applications-with-amazon-q-code-transformation-preview/)     
* [https://docs.openrewrite.org/](https://docs.openrewrite.org/)     
* [https://www.moderne.io/](https://www.moderne.io/)     

## Dev   

Still quite new some loom and virtualthread    
* Limits of loom [https://softwaremill.com/limits-of-looms-performance/](https://softwaremill.com/limits-of-looms-performance/)    
* Advantage of vThread : [https://blog.heaphero.io/2023/11/18/virtual-threads-a-definite-advantage/](https://blog.heaphero.io/2023/11/18/virtual-threads-a-definite-advantage/)   
* Journey from 1.1 to 21 : [https://dzone.com/articles/the-resurrection-of-virtual-threads-unraveling-the](https://dzone.com/articles/the-resurrection-of-virtual-threads-unraveling-the)    
* Loom is just hyperthreading [https://foojay.io/today/loom-is-just-hyperthreading-in-java/](https://foojay.io/today/loom-is-just-hyperthreading-in-java/)     

Learn to debug system on real emulate cases     
* [https://sadservers.com/scenarios](https://sadservers.com/scenarios)    

Jakarta EE 11 : what is coming ?     
* [https://speakerdeck.com/reza_rahman/contributors-guide-to-the-jakarta-ee-10-galaxy](https://speakerdeck.com/reza_rahman/contributors-guide-to-the-jakarta-ee-10-galaxy)    

Solid exercice in Java     
* [https://github.com/nerdschoolbergen/solid/tree/master](https://github.com/nerdschoolbergen/solid/tree/master)     

Java at AWS: Lessons Learned from Upgrading and Modernizing a Massive JVM      
* [https://www.youtube.com/watch?v=Yu2BhWk9mKY](https://www.youtube.com/watch?v=Yu2BhWk9mKY)

Reduce JVM docker image size     
* [https://dzone.com/articles/ways-to-reduce-jvm-docker-image-size](https://dzone.com/articles/ways-to-reduce-jvm-docker-image-size)     

Explanation about Java Streams collector      
[https://www.javabrahman.com/java-8/java-8-java-util-stream-collector-basics-tutorial-with-examples/](https://www.javabrahman.com/java-8/java-8-java-util-stream-collector-basics-tutorial-with-examples/)    

Java Collector Teeing     
* [https://mail.openjdk.org/pipermail/core-libs-dev/2018-June/053987.html](https://mail.openjdk.org/pipermail/core-libs-dev/2018-June/053987.html)      
* [https://dzone.com/articles/java-12-the-teeing-collector](https://dzone.com/articles/java-12-the-teeing-collector)    

Migration Terraform to OpenTofu       
* [https://medium.com/](https://medium.com/)@bisinet/from-terraform-to-opentofu-ebb23863b6a7
* [https://spacelift.io/blog/terraform-tools](https://spacelift.io/blog/terraform-tools)

How Roaring Bitmap wworks     
* [https://vikramoberoi.com/a-primer-on-roaring-bitmaps-what-they-are-and-how-they-work/](https://vikramoberoi.com/a-primer-on-roaring-bitmaps-what-they-are-and-how-they-work/)       

How ZGC works    
* [https://inside.java/2023/11/28/gen-zgc-explainer/](https://inside.java/2023/11/28/gen-zgc-explainer/)      

Java Kata : mutatio testing     
* [https://github.com/vmzakharov/mutate-test-kata](https://github.com/vmzakharov/mutate-test-kata)    

Maven basics (really clear explanations)     
* [https://cguntur.me/2020/05/23/understanding-apache-maven-part-1/](https://cguntur.me/2020/05/23/understanding-apache-maven-part-1/)    

Latency problem      
* [https://github.com/jabrena/latency-problems](https://github.com/jabrena/latency-problems)     

## Tool   

Some shells tools 
Nu Shell    
* [https://www.nushell.sh/](https://www.nushell.sh/)    
* [https://github.com/nushell/nushell](https://github.com/nushell/nushell)    
Sshx (A secure web-based, collaborative terminal)    
* [https://sshx.io/](https://sshx.io/)     

Curl evolution     
* [https://daniel.haxx.se/blog/2023/11/14/curl-on-100-operating-systems/](https://daniel.haxx.se/blog/2023/11/14/curl-on-100-operating-systems/)       

Nix flakes and Julia Evans feedback     
* [https://jvns.ca/blog/2023/11/11/notes-on-nix-flakes/](https://jvns.ca/blog/2023/11/11/notes-on-nix-flakes/)     

Tool from pinterest Memq (an efficient, scalable cloud native PubSub system)     
* [https://github.com/pinterest/memq](https://github.com/pinterest/memq)      

Explore Intellij dependency matrix on project structure      
* [https://foojay.io/today/explore-project-structure-with-intellij-ideas-dependency-matrix/](https://foojay.io/today/explore-project-structure-with-intellij-ideas-dependency-matrix/)    

Azcagit (Azure, Gitops and Azure container app)    
* [https://github.com/XenitAB/azcagit](https://github.com/XenitAB/azcagit)    

JFR profiler introduction      
* [https://foojay.io/today/custom-jfr-events-a-short-introduction/](https://foojay.io/today/custom-jfr-events-a-short-introduction/)       
* All JFR events [https://sap.github.io/SapMachine/jfrevents/](https://sap.github.io/SapMachine/jfrevents/)     

Testkube    
* [https://piotrminkowski.com/2023/11/27/testing-java-apps-on-kubernetes-with-testkube/](https://piotrminkowski.com/2023/11/27/testing-java-apps-on-kubernetes-with-testkube/)     
* [https://testkube.io/](https://testkube.io/)     

Tool Javalin (simple web framework for Java)   
* [https://javalin.io/](https://javalin.io/)    
* [https://github.com/javalin/javalin](https://github.com/javalin/javalin)    

Tool Jreleaser     
* [https://jreleaser.org/guide/latest/index.html](https://jreleaser.org/guide/latest/index.html)   

Java AI tools     
* [https://github.com/oracle/tribuo](https://github.com/oracle/tribuo)     
* [https://github.com/microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel)    

Tool Excalidraw (now integrate OpenAI), build shared schemas      
* [https://github.com/excalidraw/excalidraw](https://github.com/excalidraw/excalidraw)    
* [https://excalidraw.com/](https://excalidraw.com/)    

## Various

Llm subjects :     
* LLM and Java (genAI, LangChain4J) [https://glaforge.dev/talks/2023/11/13/gen-ai-with-palm-2-and-java/](https://glaforge.dev/talks/2023/11/13/gen-ai-with-palm-2-and-java/)     
* LLM models resources [https://lifearchitect.ai/models/](https://lifearchitect.ai/models/)   
* Microsoft generative AI Course [https://github.com/microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners)
* Llm course [https://github.com/mlabonne/llm-course](https://github.com/mlabonne/llm-course)      

Agility (Ivar Jacobson and Alistair Cockburn)    
* [https://www.youtube.com/watch?v=QqKcuXB8PDo](https://www.youtube.com/watch?v=QqKcuXB8PDo)      

List of resources      
* Engineering blogs [https://blog.bytebytego.com/p/79-engineering-blogs-to-level-up](https://blog.bytebytego.com/p/79-engineering-blogs-to-level-up)      
* Blogs collection [https://lists.eatonphil.com/blogs.html](https://lists.eatonphil.com/blogs.html)      

Framework to analyze Senor, principal engineer work    
* [https://twitter.com/thiagoghisi/status/1727535141440942431](https://twitter.com/thiagoghisi/status/1727535141440942431)     

Open datastructure    
* [http://opendatastructures.org/](http://opendatastructures.org/)   

