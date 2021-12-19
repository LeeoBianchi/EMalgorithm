# EMalgorithm

A python implementation of the EM Algorithm for the gaussian mixture model.

- Starting from a set of data distributed according to the gaussian mixture: 𝑓(𝑦𝑖) = 𝑝 ⋅ 𝜙(𝑦𝑖; 0,1^2) + (1 − 𝑝) ⋅ 𝜙(𝑦𝑖; 0, 𝜏^2 + 1^2) the script computes a Bayesian estimation of the parameters through the likelihood function.
- Both a bootstrap and an Information-Matrix-based estimate of the parameters' variances is implemented.
- The code also returns a contour plot of the likelihood function, for a graphical estimation of the parameters values and variances. 
