TSL (Topic Structure Learning) consists of the software packages of a series of the state-of-the-art topic models for text analysis, which discovers topics with informative structures from documents in an unsupervised way. TSL enjoys significantly better performance and interpretability for analysing both long and short documents. MetaTM can be used to visualise the topical structures of a given corpus, as well as to performa tasks like document classification and clustering.

TSL consists of two packages:
1. [DirBN](https://github.com/ethanhezhao/DirBN) automatically discovers tree-structured topic hierarchies, where topics on the higher levels are more general than those on the lower levels. [paper](https://papers.nips.cc/paper/8020-dirichlet-belief-networks-for-topic-structure-learning.pdf)
2. [WEDTM](https://github.com/ethanhezhao/WEDTM) discovers sub-topics for each normal topic, which give finer-grained semantic interpretations of both topics and documents. [paper](http://proceedings.mlr.press/v80/zhao18a)
  
Author and developer: [He Zhao](https://ethanhezhao.github.io) @ Monash University, Australia.
