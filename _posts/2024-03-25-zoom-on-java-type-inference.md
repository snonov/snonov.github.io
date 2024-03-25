---
layout: post
title: "Zoom on java type inference"
date: 2024-03-25
tags : Java Type Inference Zoomon
---

Nice coverage of the subject in "The Well-Grounded Java Developer, Second Edition" by Jason Clark, Benjamin Evans, Martijn Verburg. This zoom on is a synthesis extended by some external references.

Enhanced type inference in java is done with var keyword that is not a reserved keyword (you can name a variable var). This feature of the source code compiler enables the compiler to work out some of the type information in programs automatically. As a result, it doesn’t need to be told everything explicitly.   
But here are some steps before :
* Java 5, when generic methods were introduced with [JSR 14](https://jcp.org/en/jsr/detail?id=14) inspired by [GJ](https://homepages.inf.ed.ac.uk/wadler/gj/)
* Java 7, significant enhancement to type inference in Java came with diamond syntax, part of [JSR 334](https://jcp.org/en/jsr/detail?id=334) with Improved Type Inference for Generic Instance Creation (diamond). Those enhancement were called also named Coin project.
* Java 8, more type inference to support usage with lambda expressions with [JEP 101](https://openjdk.org/jeps/101), example
```
Function<String, Integer> lengthFn = s -> s.length();
```
* Java 10, major change with arrival of Local Variable Type Inference (LVTI), otherwise known as var. This come with [JEP 286](https://openjdk.org/jeps/286)
* Java 11, linked to previous JEP 286, [JEP 323](https://openjdk.org/jeps/323) LVTI for lambda parameters delivered     

Take care : 
* does not introduce dynamic typing, and all Java variables continue to have static types at all times
* compiler applies a form of constraint solving
* var is implemented solely in the source code compiler (javac) and has no runtime or performance effect whatsoever

LVTI style guide with best practises : [https://openjdk.org/projects/amber/guides/lvti-style-guide](https://openjdk.org/projects/amber/guides/lvti-style-guide)

Giving **Principles** :
* Reading code is more important than writing code
* Code should be clear from local reasoning
* Code readability shouldn’t depend on IDEs
* Explicit types are a tradeoff

and **Guidelines** :
* Choose variable names that provide useful information
* Minimize the scope of local variables
* Consider var when the initializer provides sufficient information to the reader
* Use var to break up chained or nested expressions with local variables
* Don’t worry too much about “programming to the interface” with local variables
* Take care when using var with diamond or generic methods 
* Take care when using var with literals











