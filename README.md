<img src="docs/images/readme.png" alt="Quantum ESM Logo"/>

<p align="center">
    <strong>Practical Implementation of a Quantum String Matching Algorithm</strong><br/>
    <a href="https://scholar.google.com/citations?user=4-fzfJEAAAAJ">Simone Faro</a>,
    <a href="https://scholar.google.com/citations?user=QJDxRrsAAAAJ">Francesco Pio Marino</a>, and
    <a href="https://scholar.google.com/citations?user=VNQ6auUAAAAJ">Antonio Scardace</a>
</p>

<div align="center">
    <a href="https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge" alt="Python"><img src="https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge" alt="Python"></a>
    <a href="https://dl.acm.org/doi/10.1145/3660318.3660327"><img src="https://img.shields.io/badge/Paper-pdf-green?style=for-the-badge&logo=adobeacrobatreader&logoWidth=20&logoColor=white&color=94DD15" alt="Paper PDF"></a>
    <a href="https://colab.research.google.com/github/antonioscardace/Practical-Quantum-ESM/blob/main/tutorial.ipynb" target="_blank"><img src="https://img.shields.io/badge/Open%20in-Colab-red?style=for-the-badge" alt="Open in Colab"></a>
    <a href="https://github.com/antonioscardace/Practical-Quantum-ESM/blob/master/LICENSE"><img src="https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge" alt="License"></a>
</div>
<br/>

This repository contains the official code for our paper on Exact String Matching.<br/>
In our paper, we present the implementation of a quantum ESM algorithm, which identifies occurrences of a specified pattern $x$ of length $m$, within a text $y$ of length $n$ $\geq$ $m$, where both sequences are composed of characters taken from an alphabet $\Sigma$ of size $\sigma$. Our article presents an initial practical implementation of a quantum circuit tailored to address the ESM problem, with a particular focus on **binary strings**.

A classical **naïve** approach exhibits a worst-case time complexity of $\mathcal{O}(n+m)$, contrasting with the capability of quantum computation to achieve a $\tilde{O}(\sqrt{n})$ complexity using **Grover's search**.

We use the **Qiskit** open-source toolkit developed by **IBM**. While current real-world hardware often struggles to produce valid results due to **decoherence** and **quantum errors**, this study presents experimental results from a circuit **simulation** on classical hardware, validating the proposed implementation's efficacy.

## Citation

Please, reference this publication if you find this code useful:

```BibTeX
@inproceedings{10.1145/3660318.3660327,
    author = {Marino, Francesco Pio and Faro, Simone and Scardace, Antonio},
    title = {Practical Implementation of a Quantum String Matching Algorithm},
    year = {2024},
    publisher = {Association for Computing Machinery},
    url = {https://doi.org/10.1145/3660318.3660327}
}
```
