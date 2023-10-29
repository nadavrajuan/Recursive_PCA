# RecursivePCA: A Multi-layer PCA Transformer
A Python class leveraging Scikit-learn to implement a sequence of PCA transformations, reducing data dimensionality layer-by-layer. Starting with the original data dimension, each successive PCA layer compresses the data further, allowing for progressive dimensionality reduction. Useful for visualizing data transformations at each step and exploring the efficacy of consecutive PCA layers in data compression.

# Generative Capabilities
https://github.com/nadavrajuan/Recursive_PCA/assets/1019717/1a5ec7ad-840c-4c2f-a557-7d3298de60de

An essential feature of the PCA Chain is its ability to reconstruct data from
reduced dimensions. To demonstrate this, an interactive XY graph was de-
signed, presenting the data in the PCA Chain’s final two-dimensional space.
This visualization not only allows for the clustering of each digit class but
also offers a generative model component. Users can select any point in this
2D space, and the PCA Chain can attempt to regenerate the corresponding
digit image through its ‘inverse_transform()‘ function
