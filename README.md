# Bayes Resources
Plethora of knowledge (papers, books, videos etc) in my journey to learn bayesian methods in machine learning

## Books
+ [ Machine Learning A Probabilistic Perspective](https://doc.lagout.org/science/Artificial%20Intelligence/Machine%20learning/Machine%20Learning_%20A%20Probabilistic%20Perspective%20%5BMurphy%202012-08-24%5D.pdf) (A good start to learn probabilistic machine learning, the first two introductory chapters are pretty good for starter) - Kevin P. Murphy 

+ [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/) - Richard McElreath | [course](https://github.com/rmcelreath/statrethinking_winter2019) | [numpyro implementation](https://fehiepsi.github.io/rethinking-numpyro/) | (seems good read later)

+ [Surrogates](https://bobby.gramacy.com/surrogates/surrogates.pdf) - Robert B. Gramacy 

+ [Bayesian Optimization Book](https://bayesoptbook.com/) - Roman Garnett



## Tutorials and Course Notes
+ [Course Notes for Bayesian Models for Machine Learning](http://www.columbia.edu/~jwp2128/Teaching/BML_lecture_notes.pdf) (A must read note, the formula derivations are nice) - Columbia University Fall 2016

+ [Variational Inference: A Review for Statisticians](https://arxiv.org/pdf/1601.00670.pdf) - Blei et al

+ [An Introduction to Variational Methodsfor Graphical Models](https://people.eecs.berkeley.edu/~jordan/papers/variational-intro.pdf) - Jordan et al

+ [Advanced methods of variational inference - Deep Bayes 2018](https://www.youtube.com/watch?v=mCBnid-1slI) - Max Welling

+ [Matrix Cook Book](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf) (many usefull facts on linear algebra and beyond)

+ [Deep Probabilistic Modelling with with Gaussian Processes](http://inverseprobability.com/talks/notes/deep-probabilistic-modelling-with-gaussian-processes.html) - Neil D. Lawrence

+ [Bayesian workflow](https://dpsimpson.github.io/pages/talks/Bayesian_Workflow.pdf) - Gelman et,al.
+ [Neil Lawrence's Talks](http://inverseprobability.com/talks/) - Neil D. Lawrence

## Bayesian Deep Learning

+ [Bayesian Learning for Neural Networks](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.446.9306&rep=rep1&type=pdf) - Neal, Radford M.

### Monte Carlo Dropout Related
+ [Uncertainty in Deep Learning (PhD Thesis)](http://mlg.eng.cam.ac.uk/yarin/blog_2248.html) - Yarin Gal

+ [Dropout as a Bayesian Approximation:Representing Model Uncertainty in Deep Learning](https://arxiv.org/pdf/1506.02142.pdf) - Yarin Gal

note that this method is little controversial following [Ian Osband](https://iosband.github.io/) note on NIPS 2016 workshop. 
more details on [r/machinelearning](https://www.reddit.com/r/MachineLearning/comments/7bm4b2/d_what_is_the_current_state_of_dropout_as/) 

### Other Methods 

## Gaussian Process and Bayesian Optimization

### Gaussian Process
+ [Gaussian Processes for Machine Learning](http://www.gaussianprocess.org/gpml/) - Carl Edward Rasmussen. short intro : [link](https://www.cs.ubc.ca/~hutter/EARG.shtml/earg/papers05/rasmussen_gps_in_ml.pdf). video lecture : [link](http://videolectures.net/mlss03_rasmussen_gp/)

+ [Sparse GP using pseudo Input](http://www.gatsby.ucl.ac.uk/~snelson/SPGP_up.pdf) - Snelson & Ghahramani

+ [Scalable Gaussian process inference using variational methods](http://mlg.eng.cam.ac.uk/matthews/thesis.pdf) - Matthews Thesis. (good resources to learn variational GP)

+ [A Practical Guide to Gaussian Processes](https://drafts.distill.pub/gp/) - Deisenroth, Luo, Van der Wilk

+ [A Visual Exploration of Gaussian Processes](https://distill.pub/2019/visual-exploration-gaussian-processes/) - Görtler et al


### Bayesian Optimization
+ [A Tutorial on Bayesian OptimizationPeter](https://arxiv.org/pdf/1807.02811.pdf) - I. Frazier

+ [Taking the Human Out of the Loop:A Review of Bayesian Optimization](https://www.cs.ox.ac.uk/people/nando.defreitas/publications/BayesOptLoop.pdf) Nando Defreitas . more comprehensive than above

## Bandit Algorithm

+ [The Multi-Armed Bandit Problem and Its Solutions](https://lilianweng.github.io/lil-log/2018/01/23/the-multi-armed-bandit-problem-and-its-solutions.html) -Lilian Weng

## Online Courses

+ [Bayesian Method for Machine Learning - National Research University Higher School of Economics](https://www.coursera.org/learn/bayesian-methods-in-machine-learning) (Comprehensive, compact and intuitive course on bayesian method for machine learning, this is good start for getting basic intuition on bayesian methods)

## Summer School

+ [Deep|Bayes 2019](https://deepbayes.ru/) material and code: [github](https://github.com/bayesgroup/deepbayes-2019) video: [youtube](https://www.youtube.com/playlist?list=PLe5rNUydzV9QHe8VDStpU0o8Yp63OecdW)

## Blogs
+ [betanalpha.github.io](https://betanalpha.github.io/writing/) - Michael Betancourt's blog
+ [Notes on machine learning](https://peterroelants.github.io/) - Peter Roelants's blog (have good notes on GP, Multivariate Gaussian and Multi-Armed bandit)
+ [Knowledge Gradient Visualized](https://tiao.io/post/an-illustrated-guide-to-the-knowledge-gradient-acquisition-function/) - Louis Tiao (Nice visualization to understand KG)

## Notes etc
+ [Optimal Transport and Wassertein Distance](http://www.stat.cmu.edu/~larry/=sml/Opt.pdf) - Larry Wasserman 
+ [Understanding ELBO](http://legacydirs.umiacs.umd.edu/~xyang35/files/understanding-variational-lower.pdf) - Xitong Yang
+ [More on Multivariate Gaussians](http://cs229.stanford.edu/section/more_on_gaussians.pdf) - Chuong B. Do
+ [Gaussian Densities](https://www.seas.upenn.edu/~sys502/extra_materials/MULTIVARIATE_NORMAL.pdf) - Tony E. Smith
+ [Gumble Distribution](https://github.com/mrahtz/humble-gumbel/blob/master/gumbel.ipynb) - mrahtz 
+ [Expected Improvement Derivation](http://ash-aldujaili.github.io/blog/2018/02/01/ei/) - Al-Dujaili
+ [Math for Machine Learning](http://users.umiacs.umd.edu/~hal/courses/2013S_ML/math4ml.pdf) - Hal Daumé III
### QnA
+ [How to choose prior](https://stats.stackexchange.com/questions/78606/how-to-choose-prior-in-bayesian-parameter-estimation)
+ [Standardizing data for GP Regression](https://stats.stackexchange.com/questions/178245/should-we-standardize-the-data-while-doing-gaussian-process-regression)
