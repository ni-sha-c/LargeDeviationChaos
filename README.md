Application of Large Deviation Theory on Adjoint Sensitivities
===============================================================

Gartner-Ellis theorem is an extension of Cramer's theorem
for the non-iid case. The adjoint are non-iid Markov chains
and hence, using Cramer's theorem:

$$ \mathbb{P} (\frac{1}{N} \sum_{i=1}^{N} y_i \geq \gamma) 
\stackrel{\cdot}{=} E_C(\gamma),$$ 

where $E_C$ is the Chernoff exponent defined using:

$$E_C(\gamma) := D(p(\cdot; x)||q).$$
In the above, $q$ is the __true__ generating distribution for the adjoints
and the model $p(y; x)$ is such that, $\mathbb{E}_{p(y;x)}[y]=\gamma$.
