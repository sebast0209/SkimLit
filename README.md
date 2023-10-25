# SkimLit
Repo for NLP Sentence Classifier to aid academic paper skimming.

In this notebook, I created an NLP model that can classify sentences which appear in sequential order.

**The model will take an abstract wall of text and predict the section label each sentence should have.**

This is based on a 2017 paper [PubMed 200k RCT: a Dataset for Sequenctial Sentence Classification in Medical Abstracts](https://arxiv.org/abs/1710.06071).

When it was released, the paper presented a new dataset called PubMed 200k RCT which consists of ~200,000 labelled Randomized Controlled Trial (RCT) abstracts.

## Problem statement
The number of RCT papers released is continuing to increase, those without structured abstracts can be hard to read and in turn slow down researchers moving through the literature.

## Solution
Create an NLP model to classify abstract sentences into the role they play (e.g. objective, methods, results, etc) to enable researchers to skim through the literature and dive deeper when necessary.
