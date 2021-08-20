# Adsorption Site Clustering in Molecular Simulation
This repository contains Python code to use clustering methods to characterize adsorption site space for molecular simulations. Code is available as a[Google Colab](https://colab.research.google.com/) notebook to make installation of software dependencies and code usage easier. Our code makes use of a [Behler-Parrinello](https://doi.org/10.1063/1.3553717) fingerprint module written in C++ from the [SIMPLE-NN package](https://github.com/MDIL-SNU/SIMPLE-NN), with most ```utils``` scripts being from or modified from [Simple-NN-BP-FP](https://github.com/yilinyang1/Simple-NN-BP-FP). 

## Adsorption Site Clustering with UMAP and TSNE (Google Colab Notebook)
<div align="center">
<img src="https://github.com/ojimenezn/site-clustering/blob/master/images/clustering.png" alt="logo"></img>
</div>
This notebook contains code that automatically generates and processes a dataset of atomic environment fingerprints (features) and equilibrium adsorption energies with [EMT](https://doi.org/10.1119/1.12734)(labels), which are then used as input in clustering algorithms ([UMAP](https://umap-learn.readthedocs.io/en/latest/), [T-SNE](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html)) to identify stable adsorption space regions.
