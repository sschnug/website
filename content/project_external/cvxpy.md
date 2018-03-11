+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "cvxpy"

# Project summary to display on homepage.
summary = "A Python-embedded modeling language for convex optimization problems"

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["mathematical-optimization", "python"]

# Optional external URL for project (replaces project detail page).
external_link = "http://github.com/cvxgrp/cvxpy"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

### Summary
I contributed an interface for CoinOR's [Cbc MIP-solver](https://projects.coin-or.org/Cbc) (based on [cylp](https://github.com/coin-or/CyLP)) including examples, tests and continuous-integration scripts. This was merged into master and the upcoming 1.0 will have some changes (already merged).

Additionally, there is an unmerged [pull-request](https://github.com/cvxgrp/cvxpy/pull/438) to integrate an MIQP-solver based on CoinOR's [Bonmin](https://projects.coin-or.org/Bonmin) and my project [pyMIQP](https://github.com/sschnug/pyMIQP).
