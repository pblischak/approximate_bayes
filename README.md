## Approximate Bayesian computation

This is the source code for a small example of doing ABC and ABC-SMC (Sequential Monte Carlo) to estimate the unknown mean and variance of a normal distribution from a data set with 30 observations. I wrote it as part of a class and thought I'd put it up in the hopes that someone else might find it useful. You can get the code by cloning this repository with `git clone`, or you can click on the `Download ZIP` button.

### Files:

 - `data.txt`: contains the 30 observed data points generated from a normal distribution with unknown mean and variance.
 - `normal-abc.Rmd`: Rmarkdown file with all of the code for running the analysis. There is code for plotting the posterior distributions of the parameters and for timing the different algorithms (ABC vs. ABC-SMC), as well.
 - `normal-abc.pdf`: the rendered output of the Rmarkdown file.
