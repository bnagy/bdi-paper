# fail-paper [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) 

LaTeX and figures for the preprint '(Not) Understanding Latin Poetic Style with
Deep Learning'.

![poster summarizing the project](fail-poster.jpg?raw=true "The Poster")

The compiled [preprint](paper/fail.pdf) is also included.

Further information will be added if the paper is ever submitted (and accepted)
for publication. Right now it's kind of not working :/

*WARNING* This is a preprint, which has not been peer reviewed. Any final paper
will almost certainly include changes, which can sometimes be quite substantial.
The results listed are also subject to change. 

LaTeX 'ceur' style modified from the CEUR Workshop [template](paper/ceurart.cls)
(see copyrights etc)

## ABSTRACT

This article summarizes some mostly unsuccessful attempts to understand
authorial style by examining the attention of various neural networks (LSTMs and
CNNs) trained on a corpus of classical Latin verse that has been encoded to
include sonic and metrical features. Carefully configured neural networks are
shown to be extremely strong authorship classifiers, so it is hoped that they
might therefore teach 'traditional' readers something about how the authors
differ in style. Sadly their reasoning is, so far, inscrutable. While the
overall goal has not yet been reached, this work reports some useful findings in
terms of effective ways to encode and embed verse, the relative strengths and
weaknesses of the neural network families, and useful (and not so useful)
techniques for designing and inspecting NN models in this domain. This article
suggests that, for poetry, CNNs are better choices than LSTMs---they train more
quickly, have equivalent accuracy, and (potentially) offer better
interpretability. Based on a great deal of experimentation, it also suggests
that simple, trainable embeddings are more effective than domain-specific
schemes, and stresses the importance of techniques to reduce overfitting, like
dropout and batch normalization.

## Citation

If you are also playing the Fun Academia Game, please help me refill my Academia
Hearts.

```
@article{nagy_fail_2022,
    author          = "Nagy, Ben",
    title           = "(Preprint) (Not) Understanding {L}atin Poetic Style with Deep Learning",
    year            = "2022",
    publisher       = {Zenodo},
    version         = {v1.0.0},
    doi             = {TBD},
    howpublished    = "\url{https://github.com/bnagy/fail-paper}"
}
```

## LICENSE

CC-BY 4.0 (see LICENSE.txt)
