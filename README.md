# Ontology Pretraining code

This repository contains the source code used for the experimental session of the ["Generalizing over Long Tail Concepts for Medical Term Normalization"](https://aclanthology.org/2022.emnlp-main.588/) paper.

This code could produce some errors. The updated version will be released soon.

## Datasets

The datasets used for the experimental session are in the 
`data` folder, expert for `PROP` that cannot be publicly released.

In the `train.csv` and `test.csv` files the important columns refer to:

* `ae`: the *ADE* in the original sample text
* `term`: the preferred term *PT*
* `term_llt_or_pt`: the original LLT/PT

We don't have permission to share [MedDRA](https://www.meddra.org)
(or parts of it), so to perform the **ontology pretraining** (OP)
you have to [download it](https://www.meddra.org/subscription/process)
by yourself.

## Models execution

In each folder in `models` you can find a `train_test.sh` script to run an example.


## Cite

```
@inproceedings{portelli-etal-2022-generalizing,
    title = "Generalizing over Long Tail Concepts for Medical Term Normalization",
    author = "Portelli, Beatrice  and
      Scaboro, Simone  and
      Santus, Enrico  and
      Sedghamiz, Hooman  and
      Chersoni, Emmanuele  and
      Serra, Giuseppe",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.emnlp-main.588",
    pages = "8580--8591"
}
```
