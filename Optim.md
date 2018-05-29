# Optimisation

## Bayesian Opt

### Some of the key questions

* _how does it scale_? seems to usually be constrained to max 20 dims (see e.g. archambeau's slides)
* _how is it parametrised_? choice and tuning of acquisition
* _how to pick the GP_? does it need a _mean function_ (and if so how to set it)?

### Links

* 2017 paper, [fast bayesian optimization of machine learning hyperparameters on large datasets](http://proceedings.mlr.press/v54/klein17a/klein17a.pdf) (klein, falkner, bartels, **hennig**, **hutter**)
* 2017 slides, [bayesian optimisation](http://www.ds3-datascience-polytechnique.fr/wp-content/uploads/2017/09/2017_09_01_1500-1600_Cedric_Archambeau_Bayesian_Optimization.pdf) (**archambeau**) _practical considerations, suggests dims<20, very similar to gonzalez's slides discusses tree-structured dependencies_
* 2017 slides, [introduction to bayesian optimization](http://gpss.cc/gpmc17/slides/LancasterMasterclass_1.pdf) (gonzalez) _useful tour of bopt_
* 2017 paper, [bayesian optimization with tree-structured dependencies](http://proceedings.mlr.press/v70/jenatton17a/jenatton17a.pdf) (**jenatton**, **archambeau**, gonzalez, **seeger**) _introduce a surrogate model combining independent GP with a linear model encoding a tree-based dependency structure_
* 2016 paper, [taking the human out of the loop: a review of bayesian optimization](https://www.cs.ox.ac.uk/people/nando.defreitas/publications/BayesOptLoop.pdf) (shahriari, swersky, wang, **adams**, **de freitas**) _this is quite a useful review covering the history as well as the details, what's needed etc_
* 2014 slides, [a tutorial on bayesian optimization for machine learning](https://www.iro.umontreal.ca/~bengioy/cifar/NCAP2014-summerschool/slides/Ryan_adams_140814_bayesopt_ncap.pdf) (**adams**), _a deck of slides that goes with the 2012 paper by snoek et al, discusses practicalities well_
* 2012 paper (classic), [practical bayesian optimization of machine learning algorithms](https://papers.nips.cc/paper/4522-practical-bayesian-optimization-of-machine-learning-algorithms.pdf) (**snoek**, **larochelle**, **adams**) 
