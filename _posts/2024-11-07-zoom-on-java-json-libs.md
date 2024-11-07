---
layout: post
title: "Zoom on java Json Libraries"
date: 2024-11-07
tags : Java Ecosystem Librairies Json Zoomon Jackson Openapi Swagger Pojo Contract Generate
---

Quick drop it on some Java references libraries to work with Json.      

Two purposes :
* Handle Json format with Java
* Automatic class (records) generation

# Java libs to handle Json

* Jackson (easy Spring integration) [https://github.com/FasterXML/jackson](https://github.com/FasterXML/jackson)    
* Gson [https://github.com/google/gson](https://github.com/google/gson)     
* JsonB [https://javaee.github.io/jsonb-spec/](https://javaee.github.io/jsonb-spec/)      
* Moshi [https://github.com/square/moshi](https://github.com/square/moshi) 

# Generate your Java Pojo

## From an OpenAPI definition (usually in a swagger.json or openapi.yaml file) 

Swagger codegen       
* [https://swagger.io/tools/swagger-codegen/](https://swagger.io/tools/swagger-codegen/)      
* [https://github.com/swagger-api/swagger-codegen](https://github.com/swagger-api/swagger-codegen)     

With Spring and Feign (using OpenAPI Generator)           
* [https://spring.io/projects/spring-cloud-openfeign#overview](https://spring.io/projects/spring-cloud-openfeign#overview)

## From a Json schema 
Jsonschema2Pojo : [https://github.com/joelittlejohn/jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo)

## From raw JSon

Online generator :        
Quicktype : [https://quicktype.io/](https://quicktype.io/)  and [https://app.quicktype.io/#l=Java](https://app.quicktype.io/#l=Java)        
JsonSchema2pojo : [https://www.jsonschema2pojo.org/](https://www.jsonschema2pojo.org/)  (from json AND json schema)      

Ide integration : 
Json2java plugin : [https://plugins.jetbrains.com/plugin/18267-json2java](https://plugins.jetbrains.com/plugin/18267-json2java)      

# Generate your json schema from json

Tool/Library Name: JSONSchema.net      
Nature: Online Tool       
Language: -       
URL: [https://www.jsonschema.net/](https://www.jsonschema.net/)      

Tool/Library Name: Quicktype      
Nature: Online Tool      
Language: -      
URL: [https://quicktype.io/](https://quicktype.io/)      

Tool/Library Name: JSON to JSON Schema (IntelliJ Plugin)      
Nature: IDE Plugin      
Language: Java      
URL: [https://plugins.jetbrains.com/plugin/17611-json-to-schema](https://plugins.jetbrains.com/plugin/17611-json-to-schema)         

Tool/Library Name: GenSON      
Nature: Library, CLI Tool      
Language: Python      
URL: [https://github.com/wolverdude/genson](https://github.com/wolverdude/genson)      

Tool/Library Name: jsonschema-generator (Java)      
Nature: Library      
Language: Java      
URL: [https://github.com/victools/jsonschema-generator](https://github.com/victools/jsonschema-generator)      

Tool/Library Name: jq (Custom Script)      
Nature: Script Tool (with jq)      
Language: Linux/Unix Shell      
URL: [https://stedolan.github.io/jq/](https://stedolan.github.io/jq/)      



