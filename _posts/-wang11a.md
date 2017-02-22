---
title: Online Variational Inference for the Hierarchical Dirichlet Process
abstract: The hierarchical Dirichlet process (HDP) is a Bayesian nonparametric model
  that can be used to model mixed-membership data with a potentially infinite number
  of components.  It has been applied widely in probabilistic topic modeling, where
  the data are documents and the components are distributions of terms that reflect
  recurring patterns (or ``topics'') in the collection.  Given a document collection,
  posterior inference is used to determine the number of topics needed and to characterize
  their distributions.  One limitation of HDP analysis is that existing posterior
  inference algorithms require multiple passes through all the data---these algorithms
  are intractable for very large scale applications.  We propose an online variational
  inference algorithm for the HDP, an algorithm that is easily applicable to massive
  and streaming data.  Our algorithm is significantly faster than traditional inference
  algorithms for the HDP, and lets us analyze much larger data sets.  We illustrate
  the approach on two large collections of text, showing improved performance over
  online LDA, the finite counterpart to the HDP topic model. [pdf]
pdf: "./wang11a/wang11a.pdf"
layout: inproceedings
key: wang11a
month: 0
firstpage: 752
lastpage: 760
origpdf: http://jmlr.org/proceedings/papers/v15/wang11a/wang11a.pdf
sections: 
authors:
- given: Chong
  family: Wang
- given: John
  family: Paisley
- given: David
  family: Blei
---