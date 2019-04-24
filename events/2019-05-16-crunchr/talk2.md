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