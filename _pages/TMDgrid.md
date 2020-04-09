---
layout: archive
title: "TMDgrid"
permalink: /TMDgrid/
author_profile: true
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>


In this page we provide grids for:

- the TMD PDF $$f_1(x,k_\perp^2; Q^2)$$ for a quark in a proton and for TMD FF $$D_1(z, P_\perp^2; Q^2)$$ for a quark hadronizing into a $$\pi^+$$ hadron

- the Structure functions $$ F_T, F_{UUT}, F_{UTT}^{\sin(\phi_h-\phi_S)}$$ for Semi-Inclusive Deep Inelastic Scattering (SIDIS).


The grids are based on a global analysis of quark TMD PDFs and TMD FFs from SIDIS, Drell-Yan and Z boson production in TMD factorization with QCD evolution implemented at LO and NLL accuracy.
Information about the binning of the variables is contained in the header of the grids.
Further details can be found in the Reference.

We encourage users to take a look at this short manual where we provide the necessary conventions and definitions for the involved transverse momenta, the relevant TMDs and structure functions:
[TMD_conventions.pdf](https://github.com/JeffersonLab/TMDgrid/blob/master/TMD_conventions.pdf)


## Download

Download Structure functions $$F_T,  F_{UUT}, F_{UTT}^{\sin(\phi_h-\phi_S)}$$ grids:
- [Structure function part 1](https://github.com/JeffersonLab/TMDgrid/tree/master/Structure_Functions/SF_grid_part1.tar.gz)
- [Structure function part 2](https://github.com/JeffersonLab/TMDgrid/tree/master/Structure_Functions/SF_grid_part2.tar.gz)
This grid is split in two part for storage reasons, to join them after unpacking, run the following command in the folder where the .txt files are:
`cat SF_grid_part1.txt SF_grid_part2.txt > SF_grid.txt`

Download unpolarized TMD PDF $$f_1(x,k_\perp^2; Q^2)$$ grids
- [TMD PDF](https://github.com/JeffersonLab/TMDgrid/tree/master/TMD_distributions/grid_f1.tar.gz)

Download unpolarized TMD FF $$D_1(z,P_\perp^2; Q^2)$$ grids
- [TMD FF](https://github.com/JeffersonLab/TMDgrid/tree/master/TMD_distributions/grid_D1.tar.gz)

## References

- *Extraction of partonic transverse momentum distributions from semi-inclusive deep-inelastic scattering, Drell-Yan and Z-boson production*; Alessandro Bacchetta, Filippo Delcarro, Cristian Pisano (INFN, Pavia and Pavia U.), Marco Radici (INFN, Pavia), Andrea Signori (Jefferson Lab) - JHEP 06 (2017) 081 - [[arXiv:1703.10157](https://arxiv.org/abs/1703.10157)]

## Contacts

- Filippo Delcarro: delcarro@jlab.org
- Andrea Signori: asignori@jlab.org
