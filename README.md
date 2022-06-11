# Multiomics Integration

Collection of different materials regarding multiomics integration, used as a personal knowledge base for my Master's Thesis. 

![Alt text](/images/wallpaper.jpg?raw=true "Title")

## Factor Analysis

[Factor analysis](/documents/Factor_Analysis.pdf) is a dimensionality reduction technique that aims to find the `m` latent factors that drive the observed `p` dimensional data. The [factor analyzer package](https://github.com/EducationalTestingService/factor_analyzer) is a very convenient tool for Python users. [Here](/notebooks/factor_analysis_pca.ipynb) we provide an illustration using a simple algorithm and the above package. 

## Papers

### [GLUE](https://www.nature.com/articles/s41587-022-01284-4)

(Graph) variational autoencoders to obtain a common low-dimensional embedding from cells in different omics. The key ideas are: encoder/ decoder to allow reconstruction, prior information from a knowledge graph to ensure that similar cells are mapped to similar embedding, and an additional decoder trained adversarially so that different omics have a common semantic. [Here](/documents/GLUE.pdf) a formal derivation of the loss function. 
