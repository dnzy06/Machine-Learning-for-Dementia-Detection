
# Machine Learning for Dementia Detection

A project that implements various machine learning approaches to classify stages of dementia based on MRI scans.

4 notebooks are included in this repository:

* Data Exploration: provides visualizations of the MRI scans to understand trends.
* tSNE and UMAP: visualizes the structure of the datasets using t-Distributed Stochastic Neighbor Embedding (t-SNE) and Uniform Manifold Approximation and Projection (UMAP).
* Image Classification & SHAP: trains 6 ML algorithms (KNN, SVM, MLP, Naive Bayes, CNN, AlexNet) for both multiclass and binary classification and implemented SHapley Additive exPlanations (SHAP) to explain outputs. 
* Image Classification & SHAP - Alternate Dataset: uses an alternate dataset to validate results. 



## Run Locally

This project can be run locally using either jupyter notebook or Google Colab:

To run using jupyter notebook, execute the following command in a terminal or command window after after navigating to the project directory:

```bash
  jupyter notebook [notebook name].ipynb
```

Alternatively, Google Colab can be used to run notebooks as well. Simply download the the project to Google Drive and use Google Colab to access the notebooks. 



## Data

Two datasets were used in this project:


* [kaggle](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset) dataset - 6400 MRI images
* [OASIS](https://www.oasis-brains.org/#data) dataset - 437 MRI images


Both datasets contain the same four classes of dementia stages: non-demented, very mild demented, mild demented, and moderate demented.

