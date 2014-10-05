## Latent Dirichlet allocation

This is a C implementation of variational EM for latent Dirichlet allocation (LDA), a topic model for text or other discrete data. LDA allows you to analyze of corpus, and extract the topics that combined to form its documents. For example, click [here](https://github.com/Blei-Lab/lda-c/blob/master/example/ap-topics.pdf) to see the topics estimated from a small corpus of Associated Press documents. LDA is fully described in [Blei et al. (2003)](http://www.cs.columbia.edu/~blei/papers/BleiNgJordan2003.pdf).

This code contains:

* an implementation of variational inference for the per-document topic proportions and per-word topic assignments
* a variational EM procedure for estimating the topics and exchangeable Dirichlet hyperparameter

## Readme

View the [readme.txt](https://github.com/Blei-Lab/lda-c/blob/master/readme.txt) and fork or clone the repository.

## Sample data

2246 documents from the Associated Press **[download](https://github.com/Blei-Lab/lda-c/blob/master/example/ap.tgz)**.

Top 20 words from 100 topics estimated from the AP corpus **[pdf](https://github.com/Blei-Lab/lda-c/blob/master/example/ap-topics.pdf)**.

## Bug fixes and updates

To learn about bug-fixes, updates, and discuss LDA and related techniques, please join the topic-models mailing list, topic-models [at] lists.cs.princeton.edu.

To join, click [here](https://lists.cs.princeton.edu/mailman/listinfo/topic-models).

## Other implementations on the web

There are several other implementations of LDA on the web:
* [R package
](http://cran.r-project.org/web/packages/lda/)
* [The Mallet Toolkit from UMass](http://mallet.cs.umass.edu/)
* [Gregor Heinrich's LDA-J](http://www.arbylon.net/projects/)
* [Multinomial PCA](http://cosco.hiit.fi/search/MPCA/)
