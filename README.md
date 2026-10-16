# Supplementary Mathematica notebook for arXiv:2411.08615

This repository contains the Mathematica notebook accompanying

> Nakwoo Kim and Hoseob Shin, *Holographic free energy and integrated correlators of $\mathcal{N}=1^*$ theory,
> [arXiv:2411.08615](https://arxiv.org/abs/2411.08615).

The notebook `I4TSG_and_F1122SG.nb` contains the exact evaluation of the two supergravity-limit
integrated correlators whose values are quoted in the paper. It starts from the mode functions
$A_{n_1,n_2}(r)$ and $C_{n_1,n_2}(r)$ given in eqs. (3.8)–(3.10) and (A.2)–(A.5) of the paper, and
carries out the double sums over $(n_1,n_2)$ and the final $r$-integration:

| Quantity | Result | Paper |
|---|---|---|
| $I_4[\mathcal{T}^{\rm SG}]$ | $3-6\zeta(3)$ | eq. (3.7) |
| $-\frac{1}{c}\mathcal{F}_{1122}^{\rm SG}$ | $\frac{12}{5}-\frac{32\pi^4}{525}$ | eq. (3.28) |

Both results are obtained exactly. No numerical fitting is used, and no regulator is needed at any stage.
The notebook also contains rough numerical checks of the integrands.

## Requirements

- Mathematica 15.0 or later (tested on 15.0.1). No external packages are needed.

## How to use

- Open the notebook and run **Evaluation ▸ Evaluate Notebook** in a fresh kernel.
  The full evaluation takes about 5 minutes on a laptop.
- All outputs are saved in the notebook. Without Mathematica, the notebook and its results can be
  viewed with the free [Wolfram Player](https://www.wolfram.com/player/).
