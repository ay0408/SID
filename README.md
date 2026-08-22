# $(\epsilon,\beta)$-Smooth Indistinguishable Distributions

We propose $(\epsilon,\beta)$-smooth indistinguishable distributions, a novel family of probability distributions for $\epsilon$-differentially private mechanisms. The idea enables the unified and more flexible constructions of global sensitivity- and smooth sensitivity-based mechanisms. 

This page provides the results showing that the proposed distributions can significantly reduce the (expected) noise amount compared to existing ones, including the Laplace distribution and (fundamental and well-discussed) $(\alpha,\beta)$-admissible distributions. 

In addition to the results presented in the paper, we also provide some results of the $d=3$ case. Due to intensive computational costs, we considered only the cases SID-I, II, III, and VI when $\epsilon=5$; nevertheless, the provided results indeed show the superiority of the smooth indistinguishable distributions. For practical purposes at this point, it might be advisable to focus solely on SID-I (and II) and pre-determine $r$ to a reasonably fixed value. (Naturally, finding the theoretically "optimal" distributions should remain an ongoing topic of research.)

## Regarding the $\beta$ Value

In general, the values of $\beta$ satisfying $S(x) = LS(x)$ are relatively large. By expanding the range of possible $\beta$ values, the possibility of using such $S$ in the mechanism increases.

In practice, the value of $\beta$ should be determined based on factors such as $\mathbb{E}\[S(x) \cdot Z\]$ and depends on the query function $f$; therefore, it must be considered in light of each specific analytical task. However, in any case, the experimental results suggest that using Smooth Indistinguishable Distributions can significantly reduce the expected noise amount compared to existing mechanisms.

## Important Future Challenges
・Theoretically investigating an "optimal" smooth indistinguishable distribution, for example, minimizes the expected noise amount.

・Refining the convergence conditions of the expected noise amount for the multi-dimensional case. (In the experiments, we considered minimizing it under $\epsilon' > \beta \cdot (d+1)$ where the convergence is guaranteed in the paper. However, it might converge even when using a slightly smaller $\epsilon'$.)  
In addition, we should also consider the convergence of the variance of the noise amount. (It is easy to see that it converges when $\epsilon' > \beta \cdot (d+2)$; however, we have not yet discussed for the case where $\epsilon' \leq \beta \cdot (d+2)$. Therefore, in fact, any results in the paper where $\epsilon' \leq \beta \cdot (d+2)$ should be regarded as merely a reference. (That said, the proposed distributions are still more recommendable than existing ones.))

・It cannot ruled out that there may be $(\alpha,\beta)$-admissible distributions that outperform $(\epsilon,\beta)$-smooth indistinguishable distributions but are not yet known or have not been discussed or studied in detail. Keeping this in mind, if such distributions are found, we intend to incorporate them (and even if none are found, we will continue to) seek a family of probability distributions that is preferred over the current one.

・Developing efficient computational methods for the multi-dimensional case, especially when $d >> 2$. 
← Can we develop them (even heuristically) based on the distributions for $d=1$ and $d = 2$ cases? (Note that in general, $d$-dimensional product of independent copies of a one-dimensional $(\epsilon,\beta)$-smooth indistinguishable distribution is not smooth indistinguishable.) / It might also be worthwhile to consider relaxing Definitions 7 and 8.

・Constructing advanced mechanisms, such as bounded and unbiased mechanisms.

## Note

For details of our methods and discussion, please see our paper entitled "Smooth Indistinguishable Distributions for Differentially Private Mechanisms".

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
