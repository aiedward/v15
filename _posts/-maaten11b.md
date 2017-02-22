---
title: Hidden-Unit Conditional Random Fields
abstract: The paper explores a generalization of conditional random fields (CRFs)
  in which binary stochastic hidden units appear between the data and the labels.
  Hidden-unit CRFs are potentially more powerful than standard CRFs because they can
  represent nonlinear dependencies at each frame. The hidden units in these models
  also learn to discover latent distributed structure in the data that improves classification.
  We derive efficient algorithms for inference and learning in these models by observing
  that the hidden units are conditionally independent given the data and the labels.
  Finally, we show that hidden-unit CRFs perform well in experiments on a range of
  tasks, including optical character recognition, text classification, protein structure
  prediction, and part-of-speech tagging. [pdf]
pdf: "./maaten11b/maaten11b.pdf"
layout: inproceedings
key: maaten11b
month: 0
firstpage: 479
lastpage: 488
origpdf: http://jmlr.org/proceedings/papers/v15/maaten11b/maaten11b.pdf
sections: 
authors:
- given: Laurens
  family: Maaten
- given: Max
  family: Welling
- given: Lawrence
  family: Saul
---