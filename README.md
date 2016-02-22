## Approximate Bayesian computation

This is the source code for a small example of doing ABC and ABC-SMC (sequential Monte Carlo) to estimate the mean and variance of a normal distribution from 30 observations. I wrote it as part of a class and thought I'd put it up in the hopes that someone else might find it useful. The associated blog post can be found <a href="http://pblischak.github.io/abc/" target="_blank"><strong>here</strong></a>.

### Files:

 - `data.txt`: contains the 30 observed data points generated from a normal distribution.
 - `normal-abc.Rmd`: Rmarkdown file with all of the code for running the analysis. There is code for plotting the posterior distributions of the parameters and for timing the different algorithms (ABC vs. ABC-SMC) as well.
 - `normal-abc.html` and `normal-abc.pdf`: the rendered output of the Rmarkdown file.
