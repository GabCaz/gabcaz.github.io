---
title: "Classes and Methods for Fixed Income Securities"
last_modified_at: 2020-08-26T16:20:02-05:00
categories:
  - Blog
tags:
  - finance
  - Python
---

Following my coursework in Fixed Incomes and Asset-Backed Securities, I regrouped most commonly used methods in this repository. `utils.py` allows to perform common conversions between different conventions (rates quoting, day counts, etc.). `trees.py` contains classes to perform tree operations on securities (fit a tree to bond prices, price securities using the tree, etc.). `securities.py` is aimed at regrouping classes corresponding to fixed-income securities, to be fed into (and used with) other classes and methods available in this repository (e.g. trees.py, Monte Carlo, etc.). `prepayment.py` contains some models of prepayment. Some other more anecdotal operations are possible (e.g. doing Bond Math).

You can find the corresponding `GitHub` repository [here][fixed_income].

[fixed_income]: https://github.com/GabCaz/Fixed-Income
