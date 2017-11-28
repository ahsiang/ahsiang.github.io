---
layout: page
title: Research
order: 2
---
The unifying theme in my research is the **importance of morphology and the fossil record in understanding macroevolutionary dynamics and the history of life.** Although the majority of phylogenetic trees are inferred from genetic (and, increasingly, genomic) data, morphology remains especially important for addressing questions about evolutionary history, as fossils offer primarily (in most cases, exclusively) morphological data, and remain our only source of direct evidence of the true evolutionary history of life on Earth. The following four core modules of my research program illustrate my approach to **understanding macroevolutionary patterns and processes by applying and developing cutting-edge computational methods**:

<br />

###I. Phylogenetic incongruence: Morphology vs. genes
<img class="portrait_left" src="http://www.allisonhsiang.com/images/parametric-bootstrapping.jpg" width="300"/>
Phylogenies serve as a foundation for understanding evolutionary history and macroevolutionary processes and dynamics. As such, it is vital that the phylogenetic inference methods we use are as robust as possible. Because it is impossible to directly observe deep evolutionary history, congruence between phylogenies inferred using independent datasets is the only measure by which we can assess the "truth" of a given phylogenetic hypothesis. However, in practice, phylogenetic incongruence is pervasive, particularly between topologies inferred from genetic vs. phenotypic data.

I study phylogenetic incongruence by investigating possible sources of error and bias in phylogenomic inference using Bayesian and Maximum Likelihood frameworks, using the primary test case of the position of turtles within Amniota. Using simulations, statistical tests, data filtering, and gene/species tree comparisons, I explore sources of misleading signal and systematic biases, model misspecification, and the consequences of deep coalescence when inferring phylogenies in deep time.

<br />

###II.  Automated high-throughput morphological data extraction
<img class="portrait_right" src="http://www.allisonhsiang.com/images/automatic-3d-data-extraction.jpg" width="400"/>
One of the major hindrances to the collection of large-scale morphological ("phenomic") datasets is the sheer amount of time and hand labor required to identify and score morphological characters across a large number of taxa. To tackle this issue, I work on developing methods for automatically extracting morphological information from high-throughput images of both extant and fossil organisms. This includes <a href="https://www.github.com/HullLab/AutoMorph" target="_blank"><em>AutoMorph</em></a>, an open source software package for automatically extracting 2D and 3D data from focus-stacked images.

Software like <em>AutoMorph</em> allows for the collection of community-scale morphological data, which can then be used to understand interactions among macroevolutionary and macroecological processes, population-level variability, evolutionary dynamics across biogeographic space, etc.

<br />

###III. Probabilistic models of morphological evolution
<img class="portrait_left" src="http://www.allisonhsiang.com/images/correlated-characters.jpg" width="400"/>
Although many statistical models for molecular evolution within a phylogenetic framework exist, development of analogous models of morphological evolution has lagged behind. This is largely due to the complexity of morphological evolution; for instance, form and structure can be affected by difficult-to-constrain confounding phenomena such as homoplasy or physical forces. Furthermore, unique difficulties exist for morphological character coding, both practical (<em>e.g.</em>, 0's and 1's are not comparable across characters the way that A's, G's, C's, and T's are across sites) and theoretical (<em>e.g.</em>, hypotheses of primary homology remain, to some degree, subjective).

The lack of sophisticated statistical models describing morphological evolution hinders the use of morphology in modern phylogenetic inference and comparative method frameworks. To address this, I work on developing new probabilistic models of morphological evolution, including models to capture correlation structure in large phenomic datasets in order to automatically cluster characters into coevolving modules.

<br />

###IV. Machine learning for automatic organism identification
<img class="portrait_right" src="http://www.allisonhsiang.com/images/supervised-machine-learning-cartoon.jpg" width="500"/>
Machine learning and computer vision are essential new technologies that have yet to be brought fully to bear on questions in evolutionary biology. In light of the development of ever more sophisticated and accurate models for intelligent object and context recognition, there is great potential in applying these methods to the automatic identification of organisms in images.

I am working with both supervised and unsupervised machine learning methods (including deep learning and convolutional neural networks) in order to perform tasks such as automated coarse classification of marine microfossils and species-level identification of planktonic foraminifera. This includes spearheading a large label-collection initiative in collaboration with <a href="https://people.earth.yale.edu/profile/pincelli-hull/about" target="_blank">Pincelli Hull</a> (Yale University) for planktonic foraminifera on the <a href="https://www.zooniverse.org" target="_blank">Zooniverse</a> citizen science platform.