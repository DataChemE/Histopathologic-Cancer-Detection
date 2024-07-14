# Histopathologic-Cancer-Detection

This is a project for the Kaggle competition "Histopathologic Cancer Detection" (https://www.kaggle.com/c/histopathologic-cancer-detection). The goal of this competition is to identify metastatic tissue in histopathologic scans of lymph node sections. The dataset consists of 220000 training images and 57000 test images, each of size 96x96 pixels. The images are labeled as 0 (no cancer) or 1 (cancer).

Our model implemented a simplified version of the VGGnet architecture for the first model and the Resnet architecture for the second model. The models were trained on the training images and the labels provided in the `train_labels.csv` file. The models were then used to make predictions on the test images and the predictions were submitted to Kaggle for evaluation.

The project is organized as follows:

- cancer_detection_final.ipynb: this is the main notebook where we will develop our models and make predictions

- train: this contains the training images 

- test: this contains the test images for kaggle submission

- train_labels.csv: this contains the labels for the training images

- sample_submission.csv: this is a sample submission file for kaggle, we will use this structure to submit our predictions



