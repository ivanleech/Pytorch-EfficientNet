# Pytorch-EfficientNet
A classifier created by applying transfer learning using Pytorch and EfficientNet


<img src="./assets/birds.gif" alt="birds" width="500"/>


# Bird Species Classification with Kaggle Data

## Overview
This notebook explores bird species classification using a Kaggle dataset containing images of 525 bird species. The data has been imported into the notebook environment from Kaggle's data sources.

## Dataset
The dataset includes a diverse collection of bird images, providing an opportunity to develop a deep learning model for accurate species classification using Pytorch and EfficientNet.

## Notebook Contents
1. **Dataset:** loads images from dir. Performs resizing to 128 x 128. 
2. **Dataset Loader** Converts dataset into batches of 32 for more efficient training
3. **Load Pytorch Base Model:** Pull EfficientNet from timm. Apply transfer learning by removing last layer and connecting to 525 classes.
4. **Training:** Runs training by specifying num_epochs and  cross entropy loss function. Use adam as optimizer. 
5. **Evaluation:** Evaluate the model's performance on a validation set. Monitor the loss over train and validation.


## Acknowledgments
- Kaggle for providing the dataset and a convenient environment for data science and machine learning projects.
- Rob Mulla for the amazing ([Pytorch Tutorial](https://www.youtube.com/watch?v=tHL5STNJKag))
