## A Gentle Introduction to Word Embeddings for the Computational Social Sciences

Word embeddings represent an efficient tool to model the semantics of words in a computational fashion. The methods are hence widely-used in the field of natural language processing and find applications in a variety of language-related tasks. This workshop seeks to introduce word embeddings to researchers working across the computational social sciences. We provide a theoretical and mathematical introduction as well as an overview of potential applications of vector space models and word embeddings in the social sciences. This workshop highlights the suitability of word embeddings for interdisciplinary tasks dealing with text data and also illustrates the limitations of this heavily data-reliant framework. In doing so, we aim to equip researchers with a critical understanding of and the practical knowledge to implement these advanced approaches to open up new avenues of research in their specific areas of expertise.

### Introduction

The availability of large digital text corpora as well as the computational resources to analyse these corpora efficiently led to ground-breaking advancements in the area of natural language processing (NLP). Novel computational methods aiming at modelling the semantics of text utilise vector representations to encode the meaning of words mathematically. The resulting representations are widely-known as word embeddings [1]. These embedding vectors capture the semantic relatedness between words co-occurring in a predefined context and can be utilised to quantify the degree of similarity between different textual representations. For example, “man” and “woman” have vector representations that are very close although nowhere in the model building phase are any semantic relationships specifically induced. Moreover, word embeddings hint at potential arithmetic operations with semantics: for example, the vector representation of “king” minus that of “man” plus that of “woman” is closest in cosine similarity to the vector of “queen” (see [2]). Thus, word embeddings offer a means to harness vast amounts of data to automatically capture semantic relationships between words and have found applications across the broad spectrum of NLP.

### Structure

The first part of this workshop will provide participants with a historical background of computational semantics,
will give a concise overview of the relevance of modelling semantics in the context of linguistic analyses and will
formally introduce word embeddings. For the latter, we will restrict our presentation to two widely-known vector
space models that have been developed in recent years, namely word2vec [3], [4] and GloVe [2].
Afterwards, we introduce applications of word embeddings for modelling, descriptive and predictive approaches.
We elaborate on existing lines of research utilising vector space models to tackle problems related to the
computational social sciences. To this end, we will present and discuss our work and related other studies. Topics
include using word embedding models to identify Chicago gang member profiles on Twitter [5], analysing political
text corpora sourced from the British and Canadian parliaments with word embeddings [6], and harnessing word
embeddings to potentially capture the meaning of unknown idiomatic niche language [7].
Finally, we pay attention to the limitations of word embeddings. These include the risks involved in reasoning from
embedding models that inherently propagate stereotypes (e.g., female/male gender that “doctor” – “male” +
“female” is closer to “nurse” than to “[female] doctor”) even when trained on massive amounts of textual data
[8]. Another aspect we will elaborate on is the methodological limitations that are currently reaching the research
community [9].
The last part of our workshop will introduce participants to the implementation of word embedding models
operating on large corpora of text, and we will explain how researchers can employ and utilise existing vector
space models for their purposes to given text corpora in order to build their own vector space models (e.g., with
the text2vec R package [10]).

### Target audience

We invite researchers from the whole range of computational social science working with text data to participate
in this workshop. Requirements for participants are a basic understanding of mathematical statistics and
probability theory as well as a basic knowledge of the R programming language. This workshop might be of
particular interest for young researchers that have no or only a little experience with natural language processing
but would like to acquire knowledge about recent state-of-the-art word embedding methods and how these can
be utilised to solve problems operating on textual structures.

### Outcomes

This workshop will help participants to understand the fundamental theory of vector space models and will provide
them with potential applications of these methods for interdisciplinary tasks. Furthermore, participants will learn
how to implement word embeddings models in a straightforward way using the R programming language.


### Organisers


| [Bennett Kleinberg](https://bkleinberg.net) | [Maximilian Mozes](http://mmozes.net)   |
| :--------------------------------------: | :--------------------------------------: |
| PhD student (University College London) | Assistant Professor in Data Science (University College London) | 



