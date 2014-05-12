---
layout: page
title: Data / Code
categories: []
tags: []
status: publish
type: page
published: true
permalink : /research/data-code/
redirect_from: "/research/data.html"
redirect_from: "/pricklysoft.org/

---
### Software ###

My software projects are on [GitHub][schwilk-github].

### Online data and source code for published papers  ###

#### Schwilk et al, 2013 *PLoS One* ####

- [BarkContour.R][BarkContour]: R script to read digitized bark contours and calculate bark thickness distributions.
- [Link to publication][Schwilk-etal-2013]

#### Morlon et al, 2011, *Ecology Letters* ####

- <a href="https://github.com/dschwilk/dwstree">dwstree project at github</a>: Source python code for phylogenetic analysis including generalized version of the BLADJ node age assignment algorithm. The main script of interest should be rarefaction.py which provides the sensitivity analyses and makes use of the branch length assignment in branch_lengths.py. Rarefaction code is written to perform trivial parallelization on multi-node computers. The phylomatic algorithm with ability to maintain the full phylogeny with non species-level tips is found in treematic.py. Further documentation is in source code docstrings.

[Link to publication][Morlon-etal-2011]

#### Cornwell, W.K, D.W. Schwilk and D.D. Ackerly. 2006. A trait-based test for habitat filtering: convex hull volume. *Ecology* 87: 1465--1471. ####

[traithull][traithull] Provides an interface to the Qhull program that allows ecologists to easily calculate the convex hull volume (CHV) metric of functional diversity and do tests against null models. For a description of the method see: Cornwell, W.K, D.W. Schwilk and D.D. Ackerly. 2006. A trait-based test for habitat filtering: convex hull volume. Ecology 87: 1465--1471.

![Convex hull]({{ site.baseurl }}/images/3dscat.gif)
![Convex hull]({{ site.baseurl }}/images/3dhull.gif)


#### Schwilk, D. W. and D. D. Ackerly. 2005. Limiting similarity and functional diversity along environmental gradients. <i>Ecology Letters</i> 8:272-281. ####

The source C++ code for the niche and limiting similarity simulation (kniche), and the for the numerical model (aniche) as well as python scripts used to generate parameter inputs are all available: [ms-data-EcologyLetters-2005][kniche-aniche]

#### Schwilk, D. W. and B. Kerr. 2002. An alternative explanation for the evolution of flammability. <i>Oikos</i> 99: 431-442. ####

The C++ code for the genetic "niche-hiking" simulation: [ms-data-Oikos-2002][niche-hike]

#### Schwilk, D. W., and D. D. Ackerly. 2001. Flammability and serotiny as strategies: correlated evolution in pines. <i>Oikos</i> 94: 326-336. ####

- Online appendix with supertree phylogenies created and used in above paper:[ms-data-Oikos-2001][Oikos-2001]

[schwilk-github]: https://github.com/dschwilk
[BarkContour]: https://gist.github.com/dschwilk/fa36e849cb5db561982c
[Schwilk-etal-2013]: http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0079285
[traithull]: https://github.com/dschwilk/traithull
[Morlon-etal-2011]: http://onlinelibrary.wiley.com/doi/10.1111/j.1461-0248.2010.01563.x/abstract
[kniche-aniche]: https://github.com/dschwilk/ms-data-EcologyLetters-2005
[niche-hike]: https://github.com/dschwilk/ms-data-Oikos-2002
[Oikos-2001]: https://github.com/dschwilk/ms-data-Oikos-2001
