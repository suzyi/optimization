# optimization
Intro to numerical optimization method: papers recommendation and code implementation.
The following contents can be found in [keras-optimizers](https://keras.io/optimizers/#sgd)
## 1 - Theory
### SGD
+ paper - ""
### RMSprop
+ [Slides](http://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf) by Geoffrey Hinton.
### Nestrov
### Adagrad
+ [Paper-2011](http://www.jmlr.org/papers/volume12/duchi11a/duchi11a.pdf) published on Journal of Machine Learning Research, cited by 3178 (It's August 5, 2018.).
### Adadelta
+ [Paper-2012](https://arxiv.org/abs/1212.5701) on Arxiv, cited by 1960 (It's August 5, 2018.).
### Adam
+ [Adam-2014](https://arxiv.org/abs/1412.6980) and [its convergence-2018](https://openreview.net/forum?id=ryQu7f-RZ), have been cited by 11125 and 31, respectively.
### Adamax
### Nadam
## 2 - code and programming
+ How to numerically compute derivatives?
## 3 - Optimization framework
### CVXOPT
+ [CVXOPT](http://cvxopt.org/) is a free software package for convex optimization based on the Python programming language, developed by Martin Andersen, Joachim Dahl, and Lieven Vandenberghe.
+ [variables](http://cvxopt.org/userguide/modeling.html#variables)- It seems like variables can only be vector variable, from official guide.
### CVXPY
+ [CVXPY](http://www.cvxpy.org/) is a Python-embedded modeling language for convex optimization problems, Steven Diamond, Eric Chu, Akshay Agrawal and Stephen Boyd.
+ [Github for cvxpy](https://github.com/cvxgrp/cvxpy)
+ [Variables](https://www.cvxpy.org/tutorial/intro/index.html) can be scalars, vectors, or matrices, meaning they are 0, 1, or 2 dimensional.
+ [Library of examples](http://www.cvxpy.org/examples/index.html)
+ must follow [DCP rules](http://cvxr.com/cvx/doc/dcp.html)
+ [Geometric programming](https://github.com/cvxgrp/cvxpy/issues/32). We'll add log_sum_exp soon and then you'll be able to write GP's in their convex formulation. But there won't be a GP mode for the foreseeable future (answered in 2014).
### CVX
+ [CVX](http://cvxr.com/cvx/) is a Matlab-based modeling system for convex optimization, developed by Michael Grant and Stephen Boyd.
+ [Variables](http://cvxr.com/cvx/doc/basics.html) can be real or complex scalars, vectors, matrices, or n-dimensional arrays.
+ [Geometric programmings](http://cvxr.com/cvx/doc/gp.html) are special mathematical programs that can be converted to convex form using a change of variables. The convex form of GPs can be expressed as DCPs, but CVX also provides a special mode that allows a GP to be specified in its native form. CVX will automatically perform the necessary conversion, compute a numerical solution, and translate the results back to the original problem.
