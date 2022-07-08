---
layout: post
title: "Zoom on API protocols"
date: 2022-07-07
tags : API Protocol Rest Soap Graphql Grpc Thrift Zoomon
---

Par le menu
* introduction and overview
* SOAP
* REST
* gRPC
* GraphQL
* and some more (Json-RPC, XML-RPC, Apache Thrift)

## Introduction

API (Application Programming Interface) enable commuication between services. Request/Reponse model using protocol to exchange data.

Exchange based on transport (and protocol) would be view as :   
* Request/Response format   
* Request structure   
* Response Structure  
* Transport layer 
* Endpoint   

Web service - W3C definition : software system designed to support interoperable machine-to-machine interaction over a network.
* designed for machine-to-machine (or application-to-application) interaction   
* interoperable (not plateform dependent)   
* allow communication over a network   

[Review of various API protocols](https://iq.opengenus.org/different-types-of-api-protocols/)    
[RedHat Architecture guide to APIs](https://www.redhat.com/architect/apis-soap-rest-graphql-grpc)    
[Roy T Fielding : Architectural Styles and the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)    
Perspective in Microservice world : [SOA vs Microservice](https://www.jrebel.com/blog/microservices-vs-soa)

## SOAP (Simple Object Access Protocol)

[SOAP on W3 org](https://www.w3.org/TR/soap/)

* Format : SOAP XML Request and Response (with envelope, optional Header and Body)
* Transport
   * SOAP over MQ
   * SOAP over HTTP
* Service definition : WSDL

## REST (Representational State Transfert)

REST is the set of constraints. RESTful refers to an API adhering to those constraints

[Wikipedia REST page](https://en.wikipedia.org/wiki/Representational_state_transfer)   
[Richardson Maturity Model](https://en.wikipedia.org/wiki/Richardson_Maturity_Model)   

## gRPC

An open source high performance Remote Procedure Call (RPC)   
[gRPC](https://grpc.io/) is using [protocol buffer](https://developers.google.com/protocol-buffers/docs/overview)    

## GraphQL

GraphQL, intially from Facebook (2012) is now under GraphQL foundation (under Linux foundation)

[GraphQL](https://graphql.org/)    
[GraphQL Spec](https://spec.graphql.org/)

## Some more

 [Apache Thrift](https://thrift.apache.org/) software framework, for scalable cross-language services development
 
 
