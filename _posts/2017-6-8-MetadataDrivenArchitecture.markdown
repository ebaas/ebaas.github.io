---
layout: post
title:  "Ebaas: Metadata-driven Architecture"
date:   2017-6-8
visible: 1
---

<p class="intro"><span class="dropcap">E</span>baas is a high-productivity enterprise application platform. It supports a no-code and metadata-driven development method that enables nonprofessional developers to rapidly build single page applications for business data managements</p>

Some of the challenges found in developing enterprise applications are the ability to deliver a customized solution that meets complex and specific requirements for each customer under a time and budget constraints and adapting to business changes without big efforts.

Software companies have come to realize that it isn’t a good practice to develop enterprise application in a traditional way of implementing business logic in software due to the low-productivity nature of programming and ever-changing business requirements. The software developers have been using the metadata-driven (or model-driven) approach to describe business logic as a metadata which is external to the software code. There is a broad range of usage from a limited implementation where a few elements of an application are represented via metadata to maximum usage where the entire application is defined by metadata.

Ebaas is designed and built from the ground up based on a metadata-driven architecture (MDDA) in which all aspects of data management applications are defined by models, including:

* Data model
* Workflow model
* Form template and processing
* Data validations
* Full-text search indexing with Elasticsearch
* Access control policy
* User interface layout
* ETL (Extract, Transform, Load)
* Report generation
* Messaging

For example, you can use the object-oriented model to define data structure of your application (classes, relationships, and attributes) as well as access control policy, methods, events and actions to events. All parts of the data model are defined as metadata. Ebaas uses a relational database to store all metadata and all application data. To optimize application performance, Ebaas keeps all application metadata in memory.

To make meta-driven application feasible, Ebaas has implemented multiple engines that interpret metadata to render an entire application and provides an ability to define or modify the metadata via GUI tools. 

Ebaas has the following differences in comparison to other application platforms on the market:

* It is free: It provides a free version that comes with an embedded database. You can use it out-of-the-box after installation.
* No code development: It provides tools to create and modify models for building an entire application. It is possible to build a working enterprise application within a few days.
* Single Page Application: It is a platform for building web-based enterprise applications with a SPA architecture in which there is a clear separation of front-end and back-end.
* Object-relational Mapping: It supports mapping of an object-oriented data model to relational databases, such as Oracle, SQL Server or MySQL.
* Model interpretation: There are two different designs in MDDA, the code generation and the model interpretation. Ebaas is based model interpretation design, which is easy to maintain and deploy and enables changes in runtime without stopping applications.
* Multi-tenancy: Since an application is defined by model instead of code, one Ebaas installation can support applications for multiple customers, sharing the same application server and database.

Using Ebaas as a platform, efficiencies in application development, as well as custom modifications per customer, will become a reality.

Ebaas has been successfully used to build solutions for some of large manufacturers of Automobile, Construction Machinery, Renewal Energy, and Auto Parts industries in China, in the areas of test and measurement data management, master data management, etc.
