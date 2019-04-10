Word embeddings represent an efficient tool to model the semantics of words in a computational fashion. They are hence widely-used in the field of natural language processing and find applications in a variety of language-related tasks. This workshop seeks to introduce word embeddings to researchers working across the computational social sciences. 

The workshop will take place on September 2, 2019 at the [2019 European Symposium Series on Societal Challenges in Computational Social Science](http://symposium.computationalsocialscience.eu/2019/)] in Zurich, Switzerland. 

We invite researchers from the whole range of computational social science working with text data to participate in this workshop. Requirements for participants are a basic understanding of mathematical statistics and probability theory as well as a basic knowledge of the R programming language. 

Questions in advance? Ask us at [mozesmaj@gmail.com](mailto:mozesmaj@gmail.com).

### Introduction

The availability of large digital text corpora as well as the computational resources to analyse these corpora efficiently led to ground-breaking advancements in the area of natural language processing (NLP). Novel computational methods aiming at modelling the semantics of text utilise vector representations to encode the meaning of words mathematically. The resulting representations are widely-known as word embeddings [1]. These embedding vectors capture the semantic relatedness between words co-occurring in a predefined context and can be utilised to quantify the degree of similarity between different textual representations. For example, “man” and “woman” have vector representations that are very close although nowhere in the model building phase are any semantic relationships specifically induced. Moreover, word embeddings hint at potential arithmetic operations with semantics: for example, the vector representation of “king” minus that of “man” plus that of “woman” is closest in cosine similarity to the vector of “queen” (see [4]). Thus, word embeddings offer a means to harness vast amounts of data to automatically capture semantic relationships between words and have found applications across the broad spectrum of NLP.

In this workshop, we provide a theoretical and mathematical introduction as well as an overview of potential applications of vector space models and word embeddings in the social sciences. We thereby highlight the suitability of word embeddings for interdisciplinary tasks dealing with text data and also illustrate the limitations of this heavily data-reliant framework. In doing so, we aim to equip researchers with a critical understanding of and the practical knowledge to implement these advanced approaches to open up new avenues of research in their specific areas of expertise.

### Preliminary schedule

| Activity                                 | Timeframe     |
| ---------------------------------------- | :------------ |
| Introduction to word embeddings and vector space models (word2vec [2, 3] and GloVe [4]) | 09:00 - 10:00 |
| Applications and limitations of word embedding models in the computational social sciences | 10:00 - 10:30 |
| Coffee Break                             | 10:30 - 11:00 |
| Blind question round                     | 11:00 - 11:30 |
| Practical session: Developing vector space models in R | 11:30 - 12:30 |

### Outcomes

This workshop will help participants to understand the fundamental theory of vector space models and will provide them with potential applications of these methods for interdisciplinary tasks. Furthermore, participants will learn how to implement word embeddings models in a straightforward way using the R programming language.


### Organisers


|  [Maximilian Mozes](http://mmozes.net)  | [Bennett Kleinberg](https://bkleinberg.net) |
| :-------------------------------------: | :--------------------------------------: |
| PhD student (University College London) | Assistant Professor in Data Science (University College London) |

### References

[1] D. Jurafsky and J. H. Martin, “Speech and Language Processing 3rd ed. draft.” [Online]. Available at: [https://web.stanford.edu/~jurafsky/slp3/](https://web.stanford.edu/~jurafsky/slp3/). [Accessed: 09-Mar-2019].

[2] T. Mikolov, W. Yih, and G. Zweig, “Linguistic regularities in continuous space word representations.,” in NAACL-HLT, 2013, vol. 13, pp. 746–751.

[3] T. Mikolov, I. Sutskever, K. Chen, G. S. Corrado, and J. Dean, “Distributed Representations of Words and Phrases and their Compositionality,” in Advances in Neural Information Processing Systems, 2013, pp. 3111–3119.

[4] J. Pennington, R. Socher, and C. Manning, “Glove: Global Vectors for Word Representation,” in Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP), Doha, Qatar, 2014, pp. 1532–1543.