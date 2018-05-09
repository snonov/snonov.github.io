---
layout: post
title: "Zoom on reactive programming"
date: 2018-02-13
tags : Zoomon Reactive Rxjava Java Stream Mongodb Reactor
---

## The beginning ReactiveManifesto

Reactive Manifesto : [https://www.reactivemanifesto.org/](https://www.reactivemanifesto.org/)

## exploring landscape

Some introduction articles on the subject

Notes on Reactive Programming :
* [Reactive landscape](https://spring.io/blog/2016/06/07/notes-on-reactive-programming-part-i-the-reactive-landscape)
* [Writing some code](https://spring.io/blog/2016/06/13/notes-on-reactive-programming-part-ii-writing-some-code)
* [Simple http server application](https://spring.io/blog/2016/07/20/notes-on-reactive-programming-part-iii-a-simple-http-server-application)

[Generation history of reactive](https://akarnokd.blogspot.fr/2016/03/operator-fusion-part-1.html)

[RxJava at Netflix](https://medium.com/netflix-techblog/reactive-programming-in-the-netflix-api-with-rxjava-7811c3a1496a)

[Reactive programming : development model structured around asynchronous data streams](https://developers.redhat.com/blog/2017/06/30/5-things-to-know-about-reactive-programming/)

[Reactive landscape from RedHat](https://static.rainfocus.com/oracle/oow17/sess/1492515839907001F0ry/PF/The%20reactive%20landscape_1507191401874001RJgz.pdf)

[ReactiveStream Java introduction](https://springframework.guru/reactive-streams-in-java/)   
[Compare Reactor and RxJava](http://blog.xebia.fr/2018/03/06/introduction-aux-flux-reactifs-en-java/)

[Reactive programming](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)

## API and implementation

### Specification

Reactive Stream : initiative to provide a standard for asynchronous stream processing with non-blocking back pressure.
[https://github.com/reactive-streams/reactive-streams-jvm/](https://github.com/reactive-streams/reactive-streams-jvm/)

### Implementations

* RxJava [https://github.com/ReactiveX/RxJava](https://github.com/ReactiveX/RxJava)
* Akka Streams [https://doc.akka.io/docs/akka/2.5/stream/index.html](https://doc.akka.io/docs/akka/2.5/stream/index.html)=
* Reactor [https://projectreactor.io/](https://projectreactor.io/)
* Vert.x [http://vertx.io/](http://vertx.io/)
* Ratpack (basic implementation of the Reactive Stream API but is not designed to be a fully-featured reactive toolkit) [https://ratpack.io/](https://ratpack.io/)

Included in Java 9 (under JEP-266)
[http://www.baeldung.com/java-9-reactive-streams](http://www.baeldung.com/java-9-reactive-streams)

Included feature in Spring 5
[https://docs.spring.io/spring/docs/5.0.3.RELEASE/spring-framework-reference/web-reactive.html#spring-webflux](https://docs.spring.io/spring/docs/5.0.3.RELEASE/spring-framework-reference/web-reactive.html#spring-webflux)
[https://dzone.com/articles/reactive-programming-with-spring-5](https://dzone.com/articles/reactive-programming-with-spring-5)

Also some product driver : MongoDb reactive java driver
[https://mongodb.github.io/mongo-java-driver-reactivestreams/](https://mongodb.github.io/mongo-java-driver-reactivestreams/)

## Some code

Code notes : [https://github.com/dsyer/reactive-notes](https://github.com/dsyer/reactive-notes)   
Compare them : [https://www.hascode.com/2018/01/reactive-streams-java-9-flow-api-rxjava-and-reactor-examples/](https://www.hascode.com/2018/01/reactive-streams-java-9-flow-api-rxjava-and-reactor-examples/)     
Hands On : [https://github.com/reactor/lite-rx-api-hands-on](https://github.com/reactor/lite-rx-api-hands-on)
Workshop : [https://github.com/nurkiewicz/rxjava-workshop](https://github.com/nurkiewicz/rxjava-workshop)
