Welcome again!
================

We are happy to announce the second instance of the PyAmsterdam meetup. 
This event will be kindly hosted by 
[Crunchr](https://www.crunchrapps.com/career). This time we want to make 
space for 3 talks. And of course as usual, beers and food will be 
provided.

Schedule
=========

Thursday, 16 May 2019

18:30 - 19:00 - Welcome with drinks and food

19:00 - 19:30 - Battle testing your web API using OpenAPI and hypothesis

19:30 - 19:50 - Short break

19:50 - 20:20 - Writing Custom Kubernetes Resource Controllers with Python

20:30 - 20:50 - Internal implementation of the python dict

20:50 - 21:30 - Networking

21:30 - closing time

Talk1: Battle testing your web API using OpenAPI and hypothesis
==============================================================

by [Daniel Bradburn](https://github.com/danielbradburn)

Daniel is a full-stack developer at crunchr where he is focused on 
making the product scalable and robust.

Abstract
------------

Implementing a web API is full of difficulties, it can be
frightening to change the smallest thing, since breaking the contract
can have devastating effects on your consumers. So how can you ensure
that you don't inadvertently introduce errors?

In this talk we will present openapi-conformance, an open source python
library which helps you check that your API implementation does what it
is supposed to. This library is built on top of hypothesis and
openapi-core and brings the power of property based testing to the world
of web API development.

We are starting to use this library at crunchr to help us specify and
test our API, we will share with you some of the insights gained from
this experience.

Talk2: Writing Custom Kubernetes Resource Controllers with Python
=================================================================

by [Jan van der Vegt](https://github.com/janvdvegt)

Jan is a data scientist that worked at KLM for 3.5 years before starting
Cubonacci, a machine learning life cycle management platform.

Abstract
------------

Kubernetes allows you to orchestrate microservices and batchjobs in a
declerative way. The base Kubernetes resources like Pods, Deployments,
Services and Jobs can get you far but there are benefits to creating
project specific abstractions on top of those. Kubernetes gives you the
option to easily define custom resources that can be managed via the
Kubernetes API.

Of course, what actually needs to happen when you create, patch or
delete these components needs to be coded. Metacontroller is a project
that makes it easy to manage these custom resources via your custom
rolled API. In this talk I will show you what the benefits of custom
resources are, how metacontroller works and how to use a framework like
Flask to implement the business logic for your custom resources.

Talk3: Internal implementation of the python dict
===============================================

by Olga Sentemova

Olga is a backend-developer with QA Automation background.

Abstract
------------

The dictionary is probably the most popular data structure in Python.
Lots of iterations of improvements have made it super efficient and
beautiful. Let's see what's under the hood and dive into a world of
open addressing, hash cache and double list keys.