Battle testing your web API using OpenAPI and hypothesis
========================================================

by [Daniel Bradburn](https://github.com/danielbradburn)

Abstract
--------

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
