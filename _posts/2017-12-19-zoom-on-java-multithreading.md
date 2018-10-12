---
layout: post
title: "Zoom on java multithreading"
date: 2017-12-19
tags : Java Multithreading Zoomon
---

Par le menu
* introduction, travailler ses keywords java liés (synchronized, volatile, ....)
* Personnes à suivre sur le sujet
* l'API java.util.concurrent
* les principes de la JVM derrière, Java Memory Model, les memory barrier, ...
* les techniques : programmation lock free, programmation réactive, non blocking io
* plus loin pour l'optimisation, les performances, savoir où est stocké sa donnée (dans la JVM (cache thread, ...), sur la machine IO, RAM (NUMA), cache L1, L2, L3)

## Pour se tester :
[https://www.journaldev.com/1162/java-multithreading-concurrency-interview-questions-answers](https://www.journaldev.com/1162/java-multithreading-concurrency-interview-questions-answers)

## Une introduction rapide :
[https://www.guru99.com/multithreading-java.html](https://www.guru99.com/multithreading-java.html)

Threads in JVM: managing, observing and diagnosing     
[https://vimeo.com/291453280](https://vimeo.com/291453280)

## 2 personnes à suivre sur le sujet :
* Brian Goetz
--> Le livre : [https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601/](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601/)
--> Quelques papiers : [http://blog.vogella.com/2008/12/23/articles-from-brian-goetz/](http://blog.vogella.com/2008/12/23/articles-from-brian-goetz/)
* Doug Lea [http://g.oswego.edu/](http://g.oswego.edu/)

## Le coeur : API java.util.concurrent 
(curieux de savoir si quelqu'un utilise le Phaser sur son projet [http://www.baeldung.com/java-phaser](http://www.baeldung.com/java-phaser)
* [https://docs.oracle.com/javase/8/docs/api/?java/util/concurrent/package-summary.html](https://docs.oracle.com/javase/8/docs/api/?java/util/concurrent/package-summary.html)
* [http://www.baeldung.com/java-util-concurrent](http://www.baeldung.com/java-util-concurrent)
* [http://tutorials.jenkov.com/java-concurrency/index.html](http://tutorials.jenkov.com/java-concurrency/index.html)

## Le Java Memory Model
* [http://www.cs.umd.edu/~pugh/java/memoryModel/](http://www.cs.umd.edu/~pugh/java/memoryModel/)
* [https://gpetri.github.io/publis/jmm-vamp07.pdf](https://gpetri.github.io/publis/jmm-vamp07.pdf)

## Introduction memory barrier
[https://www.infoq.com/articles/memory_barriers_jvm_concurrency](https://www.infoq.com/articles/memory_barriers_jvm_concurrency)

Un classique la spec de la JVM (the hard way)
* [https://docs.oracle.com/javase/specs/jvms/se7/html/index.html](https://docs.oracle.com/javase/specs/jvms/se7/html/index.html)
* [https://docs.oracle.com/javase/specs/jvms/se8/jvms8.pdf](https://docs.oracle.com/javase/specs/jvms/se8/jvms8.pdf)

## Dans les manière de faire, la programmation lock free pour une introduction
* [https://fr.slideshare.net/JeanPhilippeBEMPEL/programmation-lock-free-les-techniques-des-pros-1ere-partie](https://fr.slideshare.net/JeanPhilippeBEMPEL/programmation-lock-free-les-techniques-des-pros-1ere-partie)
* [https://fr.slideshare.net/JeanPhilippeBEMPEL/programmation-lock-free-les-techniques-des-pros-2eme-partie](https://fr.slideshare.net/JeanPhilippeBEMPEL/programmation-lock-free-les-techniques-des-pros-2eme-partie)

## Non blocking IO
* [http://crunchify.com/java-nio-non-blocking-io-with-server-client-example-java-nio-bytebuffer-and-channels-selector-java-nio-vs-io/](http://crunchify.com/java-nio-non-blocking-io-with-server-client-example-java-nio-bytebuffer-and-channels-selector-java-nio-vs-io/)
* [https://medium.com/coderscorner/tale-of-client-server-and-socket-a6ef54a74763](https://medium.com/coderscorner/tale-of-client-server-and-socket-a6ef54a74763)

## programmation réactive
* [https://blog.zenika.com/2016/06/16/programmation-reactive-une-entree-en-matiere/](https://blog.zenika.com/2016/06/16/programmation-reactive-une-entree-en-matiere/)
* [https://github.com/ReactiveX/RxJava](https://github.com/ReactiveX/RxJava)

## Bonus, les changements en Java 9 (slides 10, 11, 18, 21 sur contend locking JEP143, 24, 27)
[https://fr.slideshare.net/SimonRitter/55-new-features-in-jdk-9](https://fr.slideshare.net/SimonRitter/55-new-features-in-jdk-9)

