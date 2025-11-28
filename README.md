# bdi-paper [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) [![DOI](https://zenodo.org/badge/749673978.svg)](https://doi.org/10.5281/zenodo.17750605)


LaTeX and figures for the paper **Bootstrap Distance Imposters: High precision authorship verification with improved interpretability**

The compiled [paper](paper/main.pdf) is also included.

This paper was presented at CHR 2024, Aarhus, Denmark. It is published in [the full proceedings](https://ceur-ws.org/Vol-3834/) [here](https://ceur-ws.org/Vol-3834/paper61.pdf).

For the code, see [this repo](https://github.com/bnagy/ruzicka), which also has a [Quickstart](https://github.com/bnagy/ruzicka/blob/main/code/QuickstartBDI.ipynb).

## ABSTRACT


This paper describes an update to the open-source Python implementation of the General Imposters method of authorship verification by Mike Kestemont et al. The new algorithm, called Bootstrap Distance Imposters (henceforth BDI), incorporates a key improvement introduced by Potha and Stamatatos, as well as introducing a novel method of bootstrapping that has several attractive properties when compared to the reference algorithm. I supply an open-source implementation, as well as an updated version of the Kestemont et al. code (for Python 3.x) which incorporates the same basic improvements. Next, the two approaches are benchmarked using the problems from the multi-lingual PAN 2014 author identification task, as well as the more recent PAN 2021 task. Additionally, the interpretability advantages of BDI are showcased via real-world verification studies. When operating as a summary verifier, BDI tends to be more conservative in its positive attributions, particularly when applied to difficult problem sets like the PAN2014 en_novels. In terms of raw performance, the BDI verifier outperforms all PAN2014 entrants and appears slightly stronger than the improved Kestemont GI according to the PAN metrics for both the 2014 and 2021 problems, while also offering superior interpretability.

## Citation

If you are also playing the Fun Academia Game, please help me refill my Academia
Hearts.

```
@inproceedings{nagy_bdi,
    title           = "Bootstrap {D}istance {I}mposters: High precision authorship verification with improved interpretability",
    author          = "Nagy, Ben",
    pages           = "482--493",
    url             = {https://ceur-ws.org/Vol-3834/paper61.pdf},
    crossref        = {CHR2024},
}
@proceedings{CHR2024,
  booktitle = {Proceedings of the Computational Humanities Research Conference 2024},
  year = 2024,
  editor = {Wouter Haverals and Marijn Koolen and Laure Thompson}
  number = 3834,
  series = {{CEUR} Workshop Proceedings},
  address = {Aachen},
  issn = {1613-0073},
  url = {http://ceur-ws.org/Vol-3834,
  venue = {Aarhus, Denmark},
  eventdate = {2024-12-03},
}
```

(I am not 1000% sure if this is correct, I am copying their bibtex template)
## LICENSE

CC-BY 4.0 (see LICENSE.txt)
