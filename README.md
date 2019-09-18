# Pioneers-pp: Bayesian statistics and ABC talk

The repo contains the examples and computer exercise that are associated with the *An Introduction to Bayesian Statistics and Approximate Bayesian Computing* Meetup event (https://www.meetup.com/Pioneers-of-Probabilistic-Programming/events/264336086/).

## File structure

- presentation.ipynb: notebook with the presentation.
- examples.ipynb: notebook with the code for the examples in the presentation.
- computer exercise.ipynb: the computer exercise (implementing ABC rejection sampling for the g-and-k distribution).
- computer exercise solutions.ipynb: solutions for computer exercise.
- cars.csv: the speed and stopping distance for 1920s cars dataset (see https://stat.ethz.ch/R-manual/R-patched/library/datasets/html/cars.html).
- /fig: figures for the presentation and computer exercise.


## Software

We will use ```Julia 1.0.3``` (https://julialang.org/) for the examples and exercise.

The easiest way to run the code for the examples and the exercise is to use JuliaBox (https://www.juliabox.com/). To run the code that we use with JuliaBox then:

1. Go to https://www.juliabox.com/ and create a free account.
2. Clone (or download) this repo to your local computer.
3. In the JuliaBox start scree, click on the ```jupyter``` tab and upload following files to your ```jupyter``` environment: ```computer exercise.ipynd```, ```computer exercise solutions.ipynd```, ```examples.ipynd```, and ```cars.csv```.
4. You can now run the examples and work on the computer exercise.

To get started with ```Julia``` there are some tutorials provided in JuliaBox.

An alternative is to run everything on your local computer, which might be preferable if you already have installed ```Julia```.

## Resources and further reading

#### Bayesian statistics:

Carpenter, Bob, et al. "Stan: A probabilistic programming language." Journal of statistical software 76.1 (2017. - Stan is a probabilistic programming framework for building Bayesian models. 

Bernardo, José M.. BAYESIAN STATISTICS https://www.uv.es/bernardo/BayesStat.pdf - A nice and easy to read introduction paper, however, I would skip the objective Bayesian part.

Gabry, Jonah, et al. "Visualization in Bayesian workflow." Journal of the Royal Statistical Society: Series A (Statistics in Society) 182.2 (2019): 389-402. - A good paper on how run a Bayesian analysis, including prior and posterior checks.

Gelman, Andrew, Daniel Simpson, and Michael Betancourt. "The prior can often only be understood in the context of the likelihood." Entropy 19.10 (2017): 555. - A *very* good paper on how to interpretation the prior and how the prior and posterior and combined in a Bayesian analysis.

Robert, Christian P.. The Bayesian Choice. - A quite theory-heavy book on Bayesian statistics. 

Yildirim, Ilker. "Bayesian Inference: Metropolis-Hastings Sampling." Dept. of Brain and Cognitive Sciences, Univ. of Rochester, Rochester, NY (2012) - A easy-to-read note on the Metropolis-Hastings algorithm 


#### ABC:

Drovandie, Christopher C. "Approximate Bayesian Computation." In wiley StatsRef: Statistics References Online. John Wiley & Sons Lt,Ltd. pp 1-9, 2017. - A nice and easy-to-read introduction paper. 

Marin, Jean-Michel, et al. "Approximate Bayesian computational methods." Statistics and Computing 22.6 (2012): 1167-1180. - A good (but slightly old review paper).

Sisson, Scott A., and Yanan Fan. "Likelihood-free markov chain monte carlo." arXiv preprint arXiv:1001.2058 (2010). - A paper on ABC-MCMC. 

Sisson, Scott A., Yanan Fan, and Mark Beaumont. Handbook of approximate Bayesian computation. Chapman and Hall/CRC, 2018. - The handbook of ABC, a book on ABC that covers many topics.

https://xianblog.wordpress.com/2019/07/28/introductory-overview-lecture-the-abc-of-abc/ - The slides from Christian P. Robert'sgit JMS lectur.
