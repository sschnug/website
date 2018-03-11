+++
# Date this page was created.
date = "2016-04-27"

weight = 3

# Project title.
title = "pyVideoPartialCopyDetector"

# Project summary to display on homepage.
summary = "Proof-of-concept implementation to robustly detect partial-copies of videos."

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["machine-vision", "graph-algorithm", "python", "cython", "c++"]

# Optional external URL for project (replaces project detail page).
external_link = "http://github.com/sschnug/pyVideoPartialCopyDetector"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

### Summary
This is an experimental-code based on perceptual-hashing (partially done in *cython* to increase speed) and CoinOR's [Lemon](http://lemon.cs.elte.hu/trac/lemon) whose *Network-simplex* algorithm is used to solve *min-cost max-flow* algorithms for temporal-matching of frames.

The Lemon-part is dependent on my small *pybind11/C++*-based wrapper [pyLemonFlow](https://github.com/sschnug/pyLemonFlow).

Demo-output comparing two different versions of a movie-trailer (eng vs. ger animations; different intros):

[![Demo output](https://i.imgur.com/i2Dzqsa.jpg)](https://i.imgur.com/i2Dzqsa.jpg)

More information is available at the project-page.
