---
layout: post
title: "Walk on the web flow 20240312"
date: 2024-03-12
tags : Linux Workenvironment Langchain4j Openai Ollama Ai Kata Refactoring Patternmatching Optional Java Stephencolebourne Spring Troubleshooting Leaks Servicemesh Generativeai Patricklewis Meta 1brc Donaldraab Lambda Githubcopilot Jmx Azure Refs Filesystem Codecomplexity Jvp Performance Cto Wikimedia Rag Terraform Biceps Polling Webhook Google Monorepo Netflix Engineering Unixdaemons Cloud Edge Boundaries Llm Microsoft Vectordatabase Mach Api Microservices Jmm Javamemorymodel Jcp Conwayslaw Microfrontend Designpattern constraint Exceptionhandling Modularmonolith 
---

## Architecture  

What is service mesh    
* [https://medium.com/@lucar720/what-is-servicemesh-and-why-do-you-need-it-b4153a7f7570](https://medium.com/@lucar720/what-is-servicemesh-and-why-do-you-need-it-b4153a7f7570)   

Azure AI microsoft recommanded architecture     
* [https://www.infoq.com/news/2024/02/chat-ref-arch-openai/](https://www.infoq.com/news/2024/02/chat-ref-arch-openai/)

Minimum viable architecture     
* [https://www.youtube.com/watch?v=9Q7GANXn02k](https://www.youtube.com/watch?v=9Q7GANXn02k)    

History of Google monorepo      
* [https://qeunit.com/fr/blog/le-monorepo-a-la-google/](https://qeunit.com/fr/blog/le-monorepo-a-la-google/)
* [https://www.thoughtworks.com/insights/blog/agile-engineering-practices/monorepo-vs-multirepo](https://www.thoughtworks.com/insights/blog/agile-engineering-practices/monorepo-vs-multirepo)   

Custom LLM rex and architecture   
* [https://github.blog/2023-10-30-the-architecture-of-todays-llm-applications/](https://github.blog/2023-10-30-the-architecture-of-todays-llm-applications/)    
* Microsoft REX [https://www.infoq.com/news/2024/02/ms-lessons-learned-copilots/](https://www.infoq.com/news/2024/02/ms-lessons-learned-copilots/)     
* How to customize your LLM (RAG, In-context learning, Fine-tuning, Supervised learning, RLHF) [https://github.blog/2024-02-28-customizing-and-fine-tuning-llms-what-you-need-to-know/](https://github.blog/2024-02-28-customizing-and-fine-tuning-llms-what-you-need-to-know/)    
* [https://nexocode.com/blog/posts/customizing-large-language-models-a-comprehensive-guide/](https://nexocode.com/blog/posts/customizing-large-language-models-a-comprehensive-guide/)   
* [https://blog.octo.com/comment-utiliser-un-llm-open-source-1](https://blog.octo.com/comment-utiliser-un-llm-open-source-1)   
* Ai design pattern comprehensive guide [https://towardsdatascience.com/generative-ai-design-patterns-a-comprehensive-guide-41425a40d7d0](https://towardsdatascience.com/generative-ai-design-patterns-a-comprehensive-guide-41425a40d7d0)     

MACH architecture      
* [https://machalliance.org/](https://machalliance.org/)

Back to Java Memory Model (JMM) consideration 
* [https://www.infoq.com/fr/articles/The-OpenJDK9-Revised-Java-Memory-Model/](https://www.infoq.com/fr/articles/The-OpenJDK9-Revised-Java-Memory-Model/)
* [https://www.cs.umd.edu/](https://www.cs.umd.edu/)~pugh/java/memoryModel/jsr133.pdf
* [https://mail.openjdk.org/pipermail/core-libs-dev/2014-January/024287.html](https://mail.openjdk.org/pipermail/core-libs-dev/2014-January/024287.html)
* [https://shipilev.net/talks/narnia-2555-jmm-pragmatics-en.pdf](https://shipilev.net/talks/narnia-2555-jmm-pragmatics-en.pdf)

Beyond Micro Front end      
* [https://www.infoq.com/presentations/micro-frontend-cloud-native/](https://www.infoq.com/presentations/micro-frontend-cloud-native/)  

Definition of modular monolith     
* [https://medium.com/@MilanJovanovicTech/what-is-a-modular-monolith-babd989a4ea2](https://medium.com/@MilanJovanovicTech/what-is-a-modular-monolith-babd989a4ea2)     

## Dev   

Kata refactoring list    
* [https://understandlegacycode.com/blog/5-coding-exercises-to-practice-refactoring-legacy-code/](https://understandlegacycode.com/blog/5-coding-exercises-to-practice-refactoring-legacy-code/)     

A constraint is a challenge during a kata     
* [https://blog.code-cop.org/2024/03/programming-with-nothing.html](https://blog.code-cop.org/2024/03/programming-with-nothing.html)

Stephen Colebourne about Pattern matching with optional in Java    
* [https://blog.joda.org/2024/02/pattern-match-optional-in-java-21.html](https://blog.joda.org/2024/02/pattern-match-optional-in-java-21.html)    

One more 1brc post, optimization step by step    
* [https://questdb.io/blog/billion-row-challenge-step-by-step/](https://questdb.io/blog/billion-row-challenge-step-by-step/)   

All the performance changes in the JVM since Java/JDK/JVM 10     
* [https://htmlpreview.github.io/?https](https://htmlpreview.github.io/?https)://github.com/jackshirazi/perf-changes/blob/main/docs/changes.html

Donald Raab, My ten-year quest for concise lambda expressions in Java     
* [https://betterprogramming.pub/my-ten-year-quest-for-concise-lambda-expressions-in-java-39fde576b950](https://betterprogramming.pub/my-ten-year-quest-for-concise-lambda-expressions-in-java-39fde576b950)      

Java and Ai llm (langchain4j, openai, ollama)    
* [https://www.sivalabs.in/getting-started-with-generative-ai-using-java-langchain4j-openai-ollama/](https://www.sivalabs.in/getting-started-with-generative-ai-using-java-langchain4j-openai-ollama/)     
* [https://www.youtube.com/watch?v=Ewr1KYPtLa0](https://www.youtube.com/watch?v=Ewr1KYPtLa0)      
* [https://www.sivalabs.in/langchain4j-ai-services-tutorial/](https://www.sivalabs.in/langchain4j-ai-services-tutorial/)     
* LangChain4j RAG tuto [https://www.sivalabs.in/langchain4j-retrieval-augmented-generation-tutorial/](https://www.sivalabs.in/langchain4j-retrieval-augmented-generation-tutorial/)     

AI code generation github copilot       
* [https://github.blog/2024-02-22-how-ai-code-generation-works/](https://github.blog/2024-02-22-how-ai-code-generation-works/)      

Why still using Java      
* [https://medium.com/javarevisited/25-reasons-why-java-is-still-around-in-2024-452c582d55d0](https://medium.com/javarevisited/25-reasons-why-java-is-still-around-in-2024-452c582d55d0)   

Debug using JMX revisited     
* [https://debugagent.com/debugging-using-jmx-revisited](https://debugagent.com/debugging-using-jmx-revisited)    

Code complexity in practises     
* [https://dzone.com/articles/code-complexity-in-practice](https://dzone.com/articles/code-complexity-in-practice)

Bare metal Java    
* [https://www.youtube.com/watch?v=HDLEmXH2AwM](https://www.youtube.com/watch?v=HDLEmXH2AwM)

Practises, first-class collection     
* [https://blog.ippon.fr/2024/02/26/first-class-collections-encapsulons-nos-collections/](https://blog.ippon.fr/2024/02/26/first-class-collections-encapsulons-nos-collections/)     

Polling vs Webhook    
* [https://blog.bytebytego.com/p/ep100-polling-vs-webhooks](https://blog.bytebytego.com/p/ep100-polling-vs-webhooks)   

Netflix use of Java     
* [https://www.infoq.com/presentations/netflix-java](https://www.infoq.com/presentations/netflix-java)

Reflections on Writing Unix Daemons     
* [https://tratt.net/laurie/blog/2024/some_reflections_on_writing_unix_daemons.html](https://tratt.net/laurie/blog/2024/some_reflections_on_writing_unix_daemons.html)    

Java Lambda and exception handling     
* [https://dzone.com/articles/mastering-exception-handling-in-java-lambda-expres](https://dzone.com/articles/mastering-exception-handling-in-java-lambda-expres)

## Tool   

Set up your efficient linux environment    
* [https://blog.eleven-labs.com/fr/environnement-travail-linux/](https://blog.eleven-labs.com/fr/environnement-travail-linux/)

Troubleshooting spring boot thread (and more) leak       
* [https://blog.ycrash.io/2024/02/20/troubleshooting-spring-boot-thread-leaks/](https://blog.ycrash.io/2024/02/20/troubleshooting-spring-boot-thread-leaks/)   

Java Development on Windows with Dev Drive (ReFS Resilient File System)       
* [https://devblogs.microsoft.com/java/speed-up-your-java-development-on-windows-with-microsoft-dev-drive/](https://devblogs.microsoft.com/java/speed-up-your-java-development-on-windows-with-microsoft-dev-drive/)    

Iac terraform vs biceps     
* [https://blog.xmi.fr/posts/terraform-vs-bicep/](https://blog.xmi.fr/posts/terraform-vs-bicep/)

Time series tool     
* [https://github.com/questdb/questdb](https://github.com/questdb/questdb)   

Vector Database      
* [https://www.youtube.com/watch?v=Si-TFUSo2wk](https://www.youtube.com/watch?v=Si-TFUSo2wk)
* [https://github.com/dangkhoasdc/awesome-vector-database](https://github.com/dangkhoasdc/awesome-vector-database)

## Various

Generative Ai    
* GenAI in a nutshell [https://www.youtube.com/watch?v=2IK3DFHRFfw](https://www.youtube.com/watch?v=2IK3DFHRFfw)   
* RAG and AI (Patrick Lewis and Facebook aka Meta AI Team) [https://arxiv.org/abs/2005.11401](https://arxiv.org/abs/2005.11401)    
* concrete cases [https://www.tech.rocks/vods/a5a9fa2b-fe98-ee11-8925-000d3a28bef0/ia-generative-chez-teads-de-l-idee-a-la-realite](https://www.tech.rocks/vods/a5a9fa2b-fe98-ee11-8925-000d3a28bef0/ia-generative-chez-teads-de-l-idee-a-la-realite)     
* Wikimedia’s CTO: In the age of AI, human contributors still matter [https://www.technologyreview.com/2024/02/26/1088137/wikimedia-wikipedia-cto-selena-deckelmann-ai-human-contributions/](https://www.technologyreview.com/2024/02/26/1088137/wikimedia-wikipedia-cto-selena-deckelmann-ai-human-contributions/)      

Engineering practises       
* [https://newsletter.pragmaticengineer.com/p/zirp-engineering-practices](https://newsletter.pragmaticengineer.com/p/zirp-engineering-practices)    

Boundaries between cloud and edge computing will continue to blur, predicts Jonas Bonér of Lightbend       
* [https://tfir.io/boundaries-between-cloud-and-edge-computing-will-continue-to-blur-predicts-jonas-boner-of-lightbend/](https://tfir.io/boundaries-between-cloud-and-edge-computing-will-continue-to-blur-predicts-jonas-boner-of-lightbend/)
* [https://www.kalix.io/](https://www.kalix.io/)

Measuring GitHub Copilot’s Impact on Productivity 
* [https://cacm.acm.org/research/measuring-github-copilots-impact-on-productivity/](https://cacm.acm.org/research/measuring-github-copilots-impact-on-productivity/)     

JCP, 25 years old
* [https://www.agilejava.eu/2024/03/01/javaforum-malmo-february-2024/](https://www.agilejava.eu/2024/03/01/javaforum-malmo-february-2024/)

Shade of Conways law    
* [https://thinkinglabs.io/talks/2022/08/26/shades-of-conways-law.html](https://thinkinglabs.io/talks/2022/08/26/shades-of-conways-law.html)

Competencies and Responsibilities of a Research Software Engineer     
* [https://arxiv.org/pdf/2311.11457.pdf](https://arxiv.org/pdf/2311.11457.pdf)
* [https://github.com/RSEToolkit/rse-competencies-toolkit](https://github.com/RSEToolkit/rse-competencies-toolkit)
