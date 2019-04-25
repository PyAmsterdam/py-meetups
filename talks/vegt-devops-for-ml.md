Industrialization of Machine Learning models is a complex task. 
==================================

by [Jan van der Vegt](https://github.com/janvdvegt)

Abstract
--------

Going from training a model in a Jupyter Notebook to serving predictions via an API or a batch process can take a while. Even after this is done, retraining models, monitoring performance and running tests on new versions requires a lot of manual work. By applying what is possible from current CI/CD philosophies and developing other strategies and tooling for the differences between traditional development and data science projects, Cubonacci aims to minimize the time between development and industrialization. Given the rich Python ecosystem in the data science space, Cubonacci uses a stack of Python, Docker, Kubernetes and Node.js to manage the complete machine learning model lifecycle. In this talk we will go over the journey a Python ML model takes to allow for distributed training to inference and monitoring and what the similarities and differences with regards to DevOps between traditional development and Data Science projects are.
