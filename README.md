Multiscale Strategies for Computing Optimal Transport
=========================
Samuel Gerber, Mauro Maggioni

Accepted for publication in the Journal of Machine Learning Research (JMLR)

Abstract
--------
This paper presents a multiscale approach to efficiently compute approximate
optimal transport plans between point sets. It is particularly well-suited for
point sets that are in high-dimensions, but are close to being intrinsically
low-dimensional. The approach is based on an adaptive multiscale decomposition
of the point sets. The multiscale decomposition yields a sequence of optimal
transport problems, that are solved in a top-to-bottom fashion from the
coarsest to the finest scale. We provide numerical evidence that this
multiscale approach scales approximately linearly, in time and memory, in the
number of nodes, instead of quadratically or worse for a direct solution.
Empirically, the multiscale approach results in less than one percent relative
error in the objective function. Furthermore, the multiscale plans constructed
are of interest by themselves as they may be used to introduce novel features
and notions of distances between point sets. An analysis of sets of brain MRI
based on optimal transport distances illustrates the effectiveness of the
proposed method on a real world data set. The application demonstrates that
multiscale optimal transport distances have the potential to improve on
state-of-the-art metrics currently used in computational anatomy.


