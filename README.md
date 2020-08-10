# Dimensionality_Reduction_Overview

In this repository, I would like to present foundations of the dimensionality reduction topic.

"Why might the reduction of dimensionality be needed/helpful?" - to answer the question, I have started with introducing some basic ideas of dimensionality reduction, together with visual interpretation of the most common tool using for such task - the Principal Component Analysis (PCA) - the method based on the projection.

However, since there are plenty of datasets with 'shapes' definitely too complex (because of twists, curvature etc.), to being handled by the simply projection, one needs to use much more sophisticated methods. The first presented approach I have roughly described is a specific neural network called the autoencoder. I have mainly focused on presenting an area machine learning called manifold learning, where data science intersects the topology. Here, the manifold is a purely mathematical term, stands for the most basic object studied in the topology.

In the manifold learning, the way to reduce the number of dimensions for a complex dataset, leads us to find its local characteristics, while topological tools allow us to do so. Those characteristics are then mapped by specific functions onto the 2D, 3D or higher-dimensional space, and the global image of these mappings, gives us the lower-dimensional 'copy' of the original dataset.

There are many techniques using in the manifold learning, some are based on pure topology (together with some linear algebra), another ones derive from branches like algebra or differential topology. In the overview, I have presented some basic models concern in the manifold learning:
- Isomap
- Locally Linear Embedding (LLE) with modifications like Hessian Eigenmapping (HLLE), Local Tangent Space Alignment (LTSA), regularized LLE (RLLE)
- t-distributed Stochastic Neighbor Embedding (t-SNE)

Below please find some screens, hope you enjoy:


![App Screen](https://github.com/Yelon-ml/Dimensionality_Reduction_Overview/blob/master/screens/s4.PNG)
![App Screen](https://github.com/Yelon-ml/Dimensionality_Reduction_Overview/blob/master/screens/s3.PNG)
![App Screen](https://github.com/Yelon-ml/Dimensionality_Reduction_Overview/blob/master/screens/s1.PNG)
![App Screen](https://github.com/Yelon-ml/Dimensionality_Reduction_Overview/blob/master/screens/s2.PNG)
![App Screen](https://github.com/Yelon-ml/Dimensionality_Reduction_Overview/blob/master/screens/s5.PNG)
