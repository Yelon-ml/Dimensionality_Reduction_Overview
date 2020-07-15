# Dimensionality_Reduction_Overview

In this repository, I would like to present foundations of the dimensionality reduction topic.

"Why might the reduction of dimensionality be needed/helpful?" - to answer the question, I have started with introducing some basic ideas of dimensionality reduction, together with visual interpretation of the most common tool using for such task - the Principal Component Analysis (PCA) - the method based on the projection.

However, since there are plenty of datasets with 'shapes' definitely too complex (because of twists, curvature etc.), to being handled by the simply projection, I would like to present an area called manifold learning, where Data Science intersects the topology.

For such complex datasets the way to reduce the number of dimensions, leads us to find the local characteristics of the dataset, while topological tools allow us to do so. Those characteristics are then mapped by specific functions onto the 2D, 3D or higher-dimensional space, and the global image of these mappings, gives us the lower-dimensional 'copy' of the original dataset.

There are many techniques using in the manifold learning, some are based on pure topology (together with some linear algebra), another ones derive from branches like algebra or differential topology. In my overview, once the foundations and basic PCA concepts are clear, I have presented some basic models concern in the manifold learning like:
- Isomap
- Locally Linear Embedding (LLE) with modifications like Hessian Eigenmapping (HLLE), Local Tangent Space Alignment (LTSA), regularized LLE (RLLE)
- t-distributed Stochastic Neighbor Embedding (t-SNE)

Hope you enjoy.
