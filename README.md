# Chest-X-Ray-Classification

The main inspiration behind creating this dataset is to identify COVID-19 affected patients efficiently.

## Dataset

The [dataset](https://www.kaggle.com/datasets/jtiptj/chest-xray-pneumoniacovid19tuberculosis) is organized into 3 folders (train, test, val) and contains subfolders for each image category (Normal/Pneumonia/Covid-19/Tuberculosis). A total of 7135 x-ray images are present.

* Normal
* Covid-19
* Pneumonia
* Tuberculosis

## Training

### Traditional way to train

A training template with traditional way to print the loss and accuracy plot

### WandB

A training template with track the training process with WandB

### Combine traitional way and W&B

Combine two tracking methods together

## Evaluation and Inference

Evaluate the model with confusion matrix. Then input the test set to inference the model.