# Large-scale L-BFGS using MapReduce

Project for the course "Eléments logiciels pour le traitement des données massives" at ENSAE ParisTech.

## Context

Nowadays, there is an increasing demand to deal with massive instances and variables. In such a context, it is important to scale up and parallelize the L-BFGS algorithm in a distributed system. In this project, we implement (i) the L-BFGS algorithm and (ii) the Vector-free L-BFGS (VL-BFGS) using MapReduce and Pyspark. The VL-BFGS, developed by Weizhu Chen, Zhenghao Wang and Jingren Zhou (Microsoft - "[Large-scale L-BFGS using MapReduce](https://papers.nips.cc/paper/5333-large-scale-l-bfgs-using-mapreduce)" ), is a modification of the L-BFGS algorithm to avoid the expensive dot product operations in the L-BFGS implementation. The methods are illustrated using a logistic function with ridge penalization.

## Authors

Léa Bresson (lea.bresson@ensae.fr) - Kolia Iakovlev (kolia.iakovlev@ensae.fr)
