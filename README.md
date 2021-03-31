# ss3sim_andersonetal

A repository to store the code used to write
[Anderson et al. (2014)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0092725).
The main text of the manuscript is available in `ss3sim-ms.md`.

## History of the manuscript

The manuscript began as the original vignette for ss3sim and was used as a way
to cite the available R package. Since then, the vignette has evolved to keep
up with changes to the package, but this repository acts as an archival method
for the original code and illustrates a way forward for how to
collaboratively write a manuscript using markdown.
As more and more journals are accepting alternative formats to word documents,
the code documented here can serve as an example or inspiration for future work.

## Citation

```
@article{10.1371/journal.pone.0092725,
author = {S.C. Anderson AND C.C. Monnahan AND K.F. Johnson AND K. Ono AND J.L. Valero},
journal = {PLOS ONE},
publisher = {Public Library of Science},
title = {ss3sim: An {R} Package for Fisheries Stock Assessment Simulation with {S}tock {S}ynthesis},
year = 2014,
month = {04},
volume = 9,
url = {https://doi.org/10.1371/journal.pone.0092725},
pages = {1-7},
abstract = {Simulation testing is an important approach to evaluating fishery stock assessment methods. In the last decade, the fisheries stock assessment modeling framework Stock Synthesis (SS3) has become widely used around the world. However, there lacks a generalized and scriptable framework for SS3 simulation testing. Here, we introduce ss3sim, an R package that facilitates reproducible, flexible, and rapid end-to-end simulation testing with SS3. ss3sim requires an existing SS3 model configuration along with plain-text control files describing alternative population dynamics, fishery properties, sampling scenarios, and assessment approaches. ss3sim then generates an underlying ‘truth’ from a specified operating model, samples from that truth, modifies and runs an estimation model, and synthesizes the results. The simulations can be run in parallel, reducing runtime, and the source code is free to be modified under an open-source MIT license. ss3sim is designed to explore structural differences between the underlying truth and assumptions of an estimation model, or between multiple estimation model configurations. For example, ss3sim can be used to answer questions about model misspecification, retrospective patterns, and the relative importance of different types of fisheries data. We demonstrate the software with an example, discuss how ss3sim complements other simulation software, and outline specific research questions that ss3sim could address.},
number = {4},
doi = {10.1371/journal.pone.0092725}
}
```
