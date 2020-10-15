---
title: "LSTMs Compose (and Learn) Bottom-Up"
date: 2020-01-01
publishDate: 2020-10-14T12:08:57.271448Z
authors: ["Naomi Saphra", "Adam Lopez"]
publication_types: ["1"]
abstract: "Recent work in NLP shows that LSTM language models capture hierarchical structure in language data. In contrast to existing work, we consider the *learning* process that leads to their compositional behavior. For a closer look at how an LSTM's sequential representations are composed hierarchically, we present a related measure of Decompositional Interdependence (DI) between word meanings in an LSTM, based on their gate interactions. We connect this measure to syntax with experiments on English language data, where DI is higher on pairs of words with lower syntactic distance. To explore the inductive biases that cause these compositional representations to arise during training, we conduct simple experiments on synthetic data. These synthetic experiments support a specific hypothesis about how hierarchical structures are discovered over the course of training: that LSTM constituent representations are learned bottom-up, relying on effective representations of their shorter children, rather than learning the longer-range relations independently from children."
selected: true
publication: "*Findings of EMNLP*"
url_pdf: "http://arxiv.org/abs/2010.04650"
---
