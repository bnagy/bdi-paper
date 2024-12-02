## E_TOOBIG

To re-run this evaluation, you would first need to download the PAN20 "small" (800MB, zipped) training set. https://zenodo.org/records/3724096

Once you unzip it, that should give you the `jasonl` files, and you will have to run the `corpus_prep` notebook to get `fit_train.csv` etc etc. At that point you can run the `concurrent_eval` notebook, but you will have to uncomment all the slow parts.