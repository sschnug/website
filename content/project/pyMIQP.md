+++
# Date this page was created.
date = "2016-04-27"

weight = 1

# Project title.
title = "pyMIQP"

# Project summary to display on homepage.
summary = "MIQP-solver based on CoinOR's Bonmin for Python"

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["mathematical-optimization", "python", "c++"]

# Optional external URL for project (replaces project detail page).
external_link = "http://github.com/sschnug/pyMIQP"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

### Summary
This is a Mixed Integer Quadratic Programming solver for python exploiting sparsity.

The core-concept is to implement an efficient bridge from the canonical *Convex Quadratic Programming* optimization problem to the more general *MINLP* formulation used by [Bonmin](https://projects.coin-or.org/Bonmin).

More information is available at the project-page.

### Interface
There is a [pull-request](https://github.com/cvxgrp/cvxpy/pull/438) including a complete interface to be used with [cvxpy's 1.0 branch](https://github.com/cvxgrp/cvxpy/tree/1.0). This code also includes tests.
