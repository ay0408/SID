# $(\epsilon,\beta)$-Smooth Indistinguishable Distributions

We propose $(\epsilon,\beta)$-smooth indistinguishable distributions, a novel family of probability distributions for $\epsilon$-differentially private mechanisms. The idea enables the unified and more flexible constructions of global sensitivity- and smooth sensitivity-based mechanisms. 

This page provides the results showing that the proposed distributions can significantly reduce the (expected) noise amount compared to existing ones, including the Laplace distribution and $(\alpha,\beta)$-admissible distributions.

## Important Future Challenges
・Theoretically investigating an "optimal" smooth indistinguishable distribution, for example, minimizes the expected noise amount.

・Developing efficient computational methods for the multi-dimensional case, especially when $d >> 2$. (In the experiments, due to computational time constraints, we considered only the cases SID-I, II, III, and VI when $d=3$.)  
  ← At worst, for practical purposes, we could simply use the $d$-dimensional product of independent copies of the distribution for $d=1$ case; even then, it would still reduce noise significantly compared to existing methods.

・Constructing advanced mechanisms, such as bounded and unbiased mechanisms.

## Note

For details of our methods and discussion, please see our paper entitled "Smooth Indistinguishable Distributions for Differentially Private Mechanisms".

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
