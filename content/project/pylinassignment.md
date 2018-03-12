+++
# Date this page was created.
date = "2018-03-11"

weight = 3

# Project title.
title = "pylinassignment"

# Project summary to display on homepage.
summary = "Proof-of-concept (rectangular) linear-assignment solver wrapping Coin-OR Lemon's Network-Simplex"

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["combinatorial-optimization", "c++", "python"]

# Optional external URL for project (replaces project detail page).
external_link = "http://github.com/sschnug/pylinassignment"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

### Summary
This is a proof-of-concept (rectangular) linear-assignment problem solver based on [Coin-OR's Lemon](http://lemon.cs.elte.hu/trac/lemon)
and it's *Network-Simplex* algorithm.

The basic idea is to formulate the (rectangular) linear-assignment problem as minimum-cost-flow problem (through bipartite matching) and use high-quality software available (although theoretically the latter problem is harder than the original problem).

More information is available at the project-page.
