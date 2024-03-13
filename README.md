# Quantum Exact String Matching

The provided Jupyter Notebook tutorial contains a practical implementation of an initial Quantum Exact String Matching algorithm in Qiskit, proposed in our [paper]() for the [QUASAR'24 Workshop](https://sites.google.com/view/quasar24).

[![License](https://img.shields.io/github/license/antonioscardace/Practical-Quantum-ESM.svg)](https://github.com/antonioscardace/Practical-Quantum-ESM/blob/master/LICENSE)
[![Open Issues](https://img.shields.io/github/issues/antonioscardace/Practical-Quantum-ESM.svg)](https://github.com/antonioscardace/Practical-Quantum-ESM/issues)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/antonioscardace/Practical-Quantum-ESM/blob/main/tutorial.ipynb)

## Overview

In our paper, we provide the implementation of a quantum ESM algorithm. Its essence lies in identifying an occurrence of a specified pattern $x$ of length $m$, within a text $y$ of length $n$ $\geq$ $m$, where both sequences are composed of characters taken from an alphabet $\Sigma$ of size $\sigma$. Our article presents an initial practical implementation of a quantum circuit tailored to address the ESM problem, particularly focusing on **binary strings**.

A classical **naïve** approach exhibits a worst-case time complexity of $\mathcal{O}(m(n-m + 1))$, contrasting with the capability of quantum computation to achieve a $\tilde{O}(\sqrt{n})$ complexity using **Grover's search**.

We use the **Qiskit** open-source toolkit developed by **IBM**. While current real-world hardware often struggles to produce valid results due to **decoherence** and **quantum errors**, this study presents experimental results from a circuit **simulation** on classical hardware, validating the proposed implementation's efficacy.

## Reference

Please, reference this publication if you find this code useful:

```
@inproceedings{...,
    author = {...},
    booktitle = {...},
    year = {...},
    title = {...}
}
```

## Authors

- [Simone Faro](https://scholar.google.com/citations?user=4-fzfJEAAAAJ&hl=en)
- [Francesco Pio Marino](https://scholar.google.com/citations?user=QJDxRrsAAAAJ&hl=en)
- [Antonio Scardace](https://scholar.google.com/citations?user=VNQ6auUAAAAJ&hl=en)
