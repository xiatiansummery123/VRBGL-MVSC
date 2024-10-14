# VRBGL-MVSC
Our article, titled "Virtual Regularized Bipartite Graph Learning for Multi-View Subspace Clustering", presents a novel multi-view subspace clustering method:VRBGL-MVSC.

Input: Original data X(v), number of anchors, clusters, samples, and views m, k, n, V, and a trade-off argument β.
Output: Z

The main steps of our model are outlined below.

Randomly initialize W(v), A, Z; 
initialize G(v) under the G(v)1 = 1, G(v) ≥ 0 constraints; 
initialize a(v) =1/V.
Generation of virtual matrix F by K-means algorithm.
Repeat
  Update W(v);
  Update A;
  Update Z;
  Update G(v);
  Update a(v);
Until convergence
