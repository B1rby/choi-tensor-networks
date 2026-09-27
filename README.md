# A Tensor Formulation of the Choi–Jamiołkowski Isomorphism for Quantum and Hybrid Networks

**Joaquim Regis**  
IRIF, Université Paris Cité, CNRS · Department of Mathematics, University of York

**[Read the paper](paper.pdf)** · [LaTeX source](manuscript/main.tex) · [Citation](#citation)

> **Status: 19-page preprint.** I have chosen not to submit it to arXiv at this stage because I do not yet consider its original contributions sufficiently developed.

## Abstract

We develop a unified operator and tensor framework for the local factors of classical, quantum, and hybrid Bayesian networks. Finite probability distributions are represented as diagonal density operators, while conditional probability distributions give rise to positive conditional operators that, through the Choi–Jamiołkowski isomorphism, coincide with the Choi operators of the quantum channels induced by the corresponding stochastic maps. This identifies classical conditional probabilities as a special class of quantum channels and places classical and quantum nodes of a directed acyclic graph within a common positive-operator formalism. Representing these operators as tensors in fixed orthonormal bases, we show that channel action reduces to a contraction over the input indices, providing a unified computational language for network composition. Classical Bayesian-network factor multiplication, quantum channel composition, and the interaction of state preparation and measurement in hybrid networks all emerge as instances of the same tensor-contraction rules.

## Compile the manuscript

Use a LaTeX installation that includes REVTeX 4.2, TikZ, and the mathematical packages loaded by the source. With `latexmk` installed, run:

```sh
cd manuscript
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

The compiled document is written to `manuscript/main.pdf`. The PDF linked above is supplied separately for direct reading.

## Citation

```bibtex
@unpublished{regis2026choitensornetworks,
  author = {Regis, Joaquim},
  title = {A Tensor Formulation of the {Choi--Jamio{\l}kowski}
           Isomorphism for Quantum and Hybrid Networks},
  year = {2026},
  note = {Preprint}
}
```

A standalone entry is available in [CITATION.bib](CITATION.bib), and [CITATION.cff](CITATION.cff) supplies GitHub's citation metadata.

## Acknowledgments

This work was developed under Claudia Faggian’s supervision, with helpful discussions and feedback from Gabriele Tedeschi. Full acknowledgments are included in the manuscript.

## Contact

[rgs.joaquim@gmail.com](mailto:rgs.joaquim@gmail.com)
