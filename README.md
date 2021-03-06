# PIP-experiments

## Tool for word embedding dimensionality selection
We have cleaned all experimental code to provide a unified tool in the following repo

https://github.com/aaaasssddf/word-embedding-dimensionality-selection

## Experiments in this repo
This is the source code for all experiments of the paper, "Understand Functionality and Dimensionality of Vector Embeddings: the Distributional Hypothesis, the Pairwise Inner Product Loss and Its Bias-Variance Trade-off". The paper is publicly available at

https://arxiv.org/abs/1803.00502

The NIPS paper can be found here

https://nips.cc/Conferences/2018/Schedule?showEvent=12567
```
@inproceedings{yin2018dimensionality,
 title={On the Dimensionality of Word Embedding},
 author={Yin, Zi and Shen, Yuanyuan},
 booktitle={Advances in Neural Information Processing Systems},
 year={2018}
}
```
and
```
@article{yin2018pairwise,  
  title={Understand Functionality and Dimensionality of Vector Embeddings: the Distributional Hypothesis, the Pairwise Inner Product Loss and Its Bias-Variance Trade-off},  
  author={Yin, Zi},  
  journal={arXiv preprint arXiv:1803.00502},  
  year={2018}  
}
```

All experiments in the paper are included, in particular:
1. Matrix perturbation theoretical PIP loss upper bound;
2. Robustness to over-parametrization with respect to the exponent parameter;
3. Forward stability experiments
4. Optimal dimensionality for LSA/LSI and empirical optimal dimensionalities
5. Optimal dimensionality for Word2Vec/GloVe and empirical optimal dimensionalities  

The `optimal_dimensionality` directory contains sample codes for dimensionality selection for word2vec (PMI) and glove (log-count).
