---
layout: page
title: Data / Code
categories: []
tags: []
status: publish
type: page
published: true
permalink : /research/data-code/

---
### Software ###

My software projects are on <a href="https://github.com/dschwilk">GitHub</a>.

### Online data and source code for published papers  ###

#### Schwilk et al, 2013 *PLoS One* ####

- <a href="https://gist.github.com/dschwilk/fa36e849cb5db561982c">BarkContour.R</a>. R script to read digitized bark contours and calculate bark thickness distributions.
- <a href="http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0079285">Link to publication.</a>

#### Morlon et al, 2011, *Ecology Letters* ####

- <a href="https://github.com/dschwilk/dwstree">dwstree project at github</a>: Source python code for phylogenetic analysis including generalized version of the BLADJ node age assignment algorithm. The main script of interest should be rarefaction.py which provides the sensitivity analyses and makes use of the branch length assignment in branch_lengths.py. Rarefaction code is written to perform trivial parallelization on multi-node computers. The phylomatic algorithm with ability to maintain the full phylogeny with non species-level tips is found in treematic.py. Further documentation is in source code docstrings.

- <a hlink="http://onlinelibrary.wiley.com/doi/10.1111/j.1461-0248.2010.01563.x/abstract">Link to publication.</a>


#### Cornwell, W.K, D.W. Schwilk and D.D. Ackerly. 2006. A trait-based test for habitat filtering: convex hull volume. *Ecology* 87: 1465--1471. ####

- <a href="https://github.com/dschwilk/traithull">traithull at github</a> Provides an interface to the Qhull program that allows ecologists to easily calculate the convex hull volume (CHV) metric of functional diversity and do tests against null models. For a description of the method see: Cornwell, W.K, D.W. Schwilk and D.D. Ackerly. 2006. A trait-based test for habitat filtering: convex hull volume. Ecology 87: 1465--1471.

![Convex hull]({{ site.baseurl }}/images/3dscat.gif)
![Convex hull]({{ site.baseurl }}/images/3dhull.gif)


#### Schwilk, D. W. and D. D. Ackerly. 2005. Limiting similarity and functional diversity along environmental gradients. <i>Ecology Letters</i> 8:272-281. ####

- <a href="http://www.schwilk.org/resources/data/kniche-4.5.tar.gz"> kniche-4.5.tar.gz</a> online code: Source C++ code for niche simulation
- <a href="http://www.schwilk.org/resources/data/aniche-0.3.tar.gz">aniche-0.3.tar.gz</a> C++ code for numerical model and python scripts to produce input parameter streams.


#### Schwilk, D. W. and B. Kerr. 2002. An alternative explanation for the evolution of flammability. <i>Oikos</i> 99: 431-442. ####

- <a href="http://www.schwilk.org/resources/data/niche_hike.zip">Niche_hike.zip</a> online code: C++ code for simulation
- <a href="http://www.schwilk.org/resources/data/niche_hike_app.zip">niche_hike_app.zip</a> -- A windows application (WIN95/NT/2k) based on the source above. This allows you to try out various parameters and watch the population evolve.


#### Schwilk, D. W., and D. D. Ackerly. 2001. Flammability and serotiny as strategies: correlated evolution in pines. <i>Oikos</i> 94: 326-336. ####

- <a href="http://www.schwilk.org/resources/data/000324_5000_trees.nx">OIKOS MS 99-675 - 000324_5000_trees.nx</a> online appendix: Nexus file containing 5000 alternative <i>Pinus</i> phylogenies.
- <a href="http://www.schwilk.org/resources/data/000324_strict.nx">OIKOS MS 99-675 - 000324_strict.nx</a> online appendix: Nexus file containing strict consensus of above phylogenies.
