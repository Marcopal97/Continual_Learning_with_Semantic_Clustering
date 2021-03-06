# Continual_Learning_with_Semantic_Clustering
Public repository for the master's thesis work on "Semantic Clustering Supporting Forward Transfer in Continual Learning".

The Notebooks folder contains two Jupyter notebooks:
- "DER_baseline" contains the code for training on the DER base model
- "DER_and_Clustering" contains the implementation of the DER + SCAN model, the solution proposed in this work.

The Results folder contains some plots and screenshots about the accuracy results obtained with these models.

The data folder contains the .pkl files used for training the DER+SCAN model using data with cluster labels.

The saved_models folder contains some empty directories than can be used for storing trained models on DER or DER+SCAN.

Some clustering results obtained on the MNIST and Cifar-10 datasets using 10 clusters, and the average accuracies achieved using the DER + SCAN model in both multi-branch and single-branch modalities, are shown below.

![MNIST_clustering_10_Task_1](https://user-images.githubusercontent.com/48278123/155314811-460a9f23-f0aa-440b-b584-f45778e594ef.png)

![MNIST_clustering_10_Task_2](https://user-images.githubusercontent.com/48278123/155314821-1b91039d-f5bb-43e2-a0a6-f9578350104d.png)

![Clustering_200_task0_10_clusters](https://user-images.githubusercontent.com/48278123/149526415-d059a9ff-8742-40ad-bff1-73f64a7c5e9e.png)

![Clustering_200_task1_10_clusters](https://user-images.githubusercontent.com/48278123/149526434-730e90ce-4a22-46d5-ab93-88f62a965b6a.png)

![MNIST_mean_accuracy_class_il](https://user-images.githubusercontent.com/48278123/149526552-e02e2d71-a013-4630-84bd-76e1f01dc326.png)
![MNIST_mean_accuracy_task_il](https://user-images.githubusercontent.com/48278123/149526584-ce6aea3a-ebe2-4c77-926b-db2d06e3bfaf.png)

![CIFAR_mean_accuracy_class_il](https://user-images.githubusercontent.com/48278123/149526644-f95e8191-ffd5-47c7-82bb-afdf63815155.png)
![CIFAR_mean_accuracy_task_il](https://user-images.githubusercontent.com/48278123/149526653-a0da566c-99ec-4bc8-92fa-3a53143e6312.png)

![CIL_mean_accuracy_single_branch_MNIST](https://user-images.githubusercontent.com/48278123/155314968-7e1ab7f0-0912-40a6-b6a2-3959a0c73c1a.png)
![CIL_mean_accuracy_single_branch_CIFAR](https://user-images.githubusercontent.com/48278123/155314984-75241570-fda3-4d92-9380-a7568dbea513.png)

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

