# $(\epsilon,\beta)$-Smooth Indistinguishable Distributions

We propose $(\epsilon,\beta)$-smooth indistinguishable distributions, a novel family of probability distributions for $\epsilon$-differentially private mechanisms. The idea enables the unified and more flexible constructions of global sensitivity- and smooth sensitivity-based mechanisms. 

This page provides the results showing that the proposed distributions can significantly reduce the (expected) noise amount compared to existing ones, including the Laplace distribution and $(\alpha,\beta)$-admissible distributions. 

In addition to the results presented in the paper, we also provide some results of the $d=3$ case. Due to intensive computational costs, we considered only the cases SID-I, II, III, and VI when $\epsilon=5$; nevertheless, the provided results indeed show the superiority of the smooth indistinguishable distributions. For practical purposes at this point, it might be advisable to focus solely on SID-I and III and pre-determine $r$ to a reasonably fixed value. (Naturally, finding the theoretically "optimal" distributions should remain an ongoing topic of research.)

## Important Future Challenges
・Theoretically investigating an "optimal" smooth indistinguishable distribution, for example, minimizes the expected noise amount.

・Developing efficient computational methods for the multi-dimensional case, especially when $d >> 2$. 
← Can we develop them (even heuristically) based on the distributions for $d=1$ and $d = 2$ cases? (Note that in general, $d$-dimensional product of independent copies of a one-dimensional $(\epsilon,\beta)$-smooth indistinguishable distribution is not smooth indistinguishable.)

・Constructing advanced mechanisms, such as bounded and unbiased mechanisms.

## Note

For details of our methods and discussion, please see our paper entitled "Smooth Indistinguishable Distributions for Differentially Private Mechanisms".

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
