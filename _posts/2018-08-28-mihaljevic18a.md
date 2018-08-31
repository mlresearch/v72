---
title: Learning Bayesian network classifiers with completed partially directed acyclic
  graphs
abstract: Most search and score algorithms for learning Bayesian network classifiers
  from data traverse the space of directed acyclic graphs (DAGs), making arbitrary
  yet possibly suboptimal arc directionality decisions. This can be remedied by learning
  in the space of DAG equivalence classes. We provide a number of contributions to
  existing work along this line. First, we identify the smallest subspace of DAGs
  that covers all possible class-posterior distributions when data is complete. All
  the DAGs in this space, which we call \textit{minimal class-focused} DAGs (MC-DAGs),
  are such that their every arc is directed towards a child of the class variable.
  Second, in order to traverse the equivalence classes of MC-DAGs, we adapt the greedy
  equivalence search (GES) by adding operator validity criteria which ensure GES only
  visits states within our space. Third, we specify how to efficiently evaluate the
  discriminative score of a GES operator for MC-DAG in time independent of the number
  of variables and without converting the completed partially DAG, which represents
  an equivalence class, into a DAG. The adapted GES perfomed well on real-world data
  sets.
section: Accepted Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
id: mihaljevic18a
month: 0
tex_title: Learning Bayesian network classifiers with completed partially directed
  acyclic graphs
firstpage: 272
lastpage: 283
page: 272-283
order: 272
cycles: false
bibtex_author: Mihaljevi\'{c}, Bojan and Bielza, Concha and Larra\~{n}aga, Pedro
author:
- given: Bojan
  family: Mihaljević
- given: Concha
  family: Bielza
- given: Pedro
  family: Larrañaga
date: 2018-08-28
address: 
publisher: PMLR
container-title: Proceedings of the Ninth International Conference on Probabilistic
  Graphical Models
volume: '72'
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 8
  - 28
pdf: http://proceedings.mlr.press/v72/mihaljevic18a/mihaljevic18a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
