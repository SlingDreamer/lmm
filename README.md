# Latent Meaning Models (LMMs)
The source code for our paper "Incorporating Latent Meanings of Morphological Compositions to Enhance Word Embeddings", and this paper will be published at ACL2018

## Abstract:

Traditional word embedding approaches learn semantic information at word level while ignoring the meaningful internal structures of words like morphemes. Furthermore, existing morphology-based models directly incorporate morphemes to train word embeddings, but still neglect the latent meanings of morphemes. In this paper, we explore to employ the latent meanings of morphological compositions of words to train and enhance word embeddings. Based on this purpose, we propose three Latent Meaning Models (LMMs), named LMM-A, LMM-S and LMM-M respectively, which adopt different strategies to incorporate the latent meanings of morphemes during the training process. Experiments on word similarity, syntactic analogy and text classification are conducted to validate the feasibility of our models. The results demonstrate that our models outperform the baselines on five word similarity datasets. On Wordsim-353 and RG-65 datasets, our models nearly achieve 5% and 7% gains over  the classic CBOW model, respectively. For the syntactic analogy and text classification tasks, our models also surpass all the baselines including a morphology-based model.

## Citation:

    @inproceedings{xu2018incorporating,
    title={Incorporating Latent Meanings of Morphological Compositions to Enhance Word Embeddings},
    author={Xu, Yang and Liu, Jiawei and Yang, Wei and Huang, Liusheng},
    booktitle={Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics},
    year={2018},
    }
