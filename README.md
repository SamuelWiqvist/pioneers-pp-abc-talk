# Pioneers-pp: Bayesian statistics and ABC talk

The repo containes the examples and computer exercise that are associated with the "An Introduction to Bayesian Statistics and Approximate Bayesian Computing" meet-up event (https://www.meetup.com/Pioneers-of-Probabilistic-Programming/events/264336086/).

## Files 

- presentation.ipynb: nodebook with the presentation.
- examples.ipynb: notebook with the code for the examples in the presentation.
- computer exercise.ipynb: the computer exercies (inference for the Ricker model).
- computer exercise solutions.ipynb: solutions for the computer exercise.
- cars.csv: the speed and stopping distance for 1920s cars dataset (see https://stat.ethz.ch/R-manual/R-patched/library/datasets/html/cars.html).
- /fig: figures for the presentation and computer exercise.


## Software

We will use ```Julia 1.0.3``` (https://julialang.org/) for the examples and exerceise.

The easiest way to run the code for the examples and the exercise is to use JuliaBox (https://www.juliabox.com/). To run the code that we use with JuliaBox then:

1. Go to https://www.juliabox.com/ and create a free account.
2. Clone (or download) this repo to your local computer.
3. In the JuliaBox start scree, click on the ```jupyter``` tab and upload following files to your ```jupyter``` enviorment: ```computer exercise.ipynd```, ```computer exercise solutions.ipynd```, ```examples.ipynd```, and ```cars.csv```.
4. You can now run the examples and work on the computer exercise.

To get started with ```Julia``` there are some tutorials provided in JuliaBox.

An alternative is to run everython on your local computer, which migth be preferable if you already have installed ```Julia```.

## References and further reading

#### Some references on Bayesian statistics:

Carpenter, Bob, et al. "Stan: A probabilistic programming language." Journal of statistical software 76.1 (2017. - Stan is a probabilitic programming framwork for building Bayesian models. 

Bernardo, José M.. BAYESIAN STATISTICS https://www.uv.es/bernardo/BayesStat.pdf - A nice and easy to read introduction paper, however, I would skip the objective Bayesian part.

Gabry, Jonah, et al. "Visualization in Bayesian workflow." Journal of the Royal Statistical Society: Series A (Statistics in Society) 182.2 (2019): 389-402. - A good paper on how run an Bayesian analyses, including prior and posterior checks.

Gelman, Andrew, Daniel Simpson, and Michael Betancourt. "The prior can often only be understood in the context of the likelihood." Entropy 19.10 (2017): 555. - A *very* good paper on how to interperate the prior and how the prior and posterior and combined in a Bayesian analyses.

Robert, Christian P.. The Bayesian Choice. - A quite theory-heavy book on Bayesian statistics. 

Yildirim, Ilker. "Bayesian Inference: Metropolis-Hastings Sampling." Dept. of Brain and Cognitive Sciences, Univ. of Rochester, Rochester, NY (2012) - A easy to read note on the Metroplis-Hastings algorithm 


#### Some references on ABC:


Fearnhead,  P.  and  Prangle,  D. *Constructing  summary statistics for approximate bayesian computation:  semi-automatic approximate Bayesian computation*. Journal of the Royal Statistical Society: Series B, 74(3):419–474, 2012.


Jiang, B., Wu, T.-y., Zheng, C., and Wong, W. H. *Learning summary statistic for approximate Bayesian computation via deep neural network*. Statistica Sinica, pp. 1595–1618, 2017.


Prangle, D. *Summary statistics in approximate Bayesian computation*. arXiv:1512.05633, 2015.

Wiqvist, S., Mattei P-A., Picchini U., and Frellsen J. *Partially Exchangeable Networks and Architectures for Learning Summary Statistics in Approximate Bayesian Computation*, arXiv:1901.10230, 2019. 