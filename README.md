# Continual_Learning_with_Semantic_Clustering
Public repository for the master's thesis work on "Semantic Clustering Supporting Forward Transfer in Continual Learning".

The Notebooks folder contains two Jupyter notebooks:
- "DER_baseline" contains the code for training on the DER base model
- "DER_and_Clustering" contains the implementation of the DER + SCAN model, the solution proposed in this work.

The Results folder contains some plots and screenshots about the accuracy results obtained with these models.
The data folder contains the .pkl files used for training the DER+SCAN model using data with cluster labels.
The saved_models folder contains some empty directories emoty than can be used for storing trained models on DER or DER+SCAN.

Credits for DER model:
```
@inproceedings{buzzega2020dark,
 author = {Buzzega, Pietro and Boschini, Matteo and Porrello, Angelo and Abati, Davide and Calderara, Simone},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {H. Larochelle and M. Ranzato and R. Hadsell and M. F. Balcan and H. Lin},
 pages = {15920--15930},
 publisher = {Curran Associates, Inc.},
 title = {Dark Experience for General Continual Learning: a Strong, Simple Baseline},
 volume = {33},
 year = {2020}
}
```
GitHub repository: https://github.com/aimagelab/mammoth

Credits for SCAN algorithm: 

```
author: Khalid Salama
creation date: 2021/02/28
description: Semantic Clustering by Adopting Nearest neighbors (SCAN) algorithm.
}
```
SCAN paper: https://arxiv.org/pdf/2005.12320.pdf

GitHub repository and code: https://github.com/keras-team/keras-io/blob/master/examples/vision/semantic_image_clustering.py 

