# Potato Disease Classification Using Convolutional Neural Networks
---
## Objective:

##### This project aims to classify the images in the given dataset as Potato Early blight, Potato Late blight and Potato healthy using convolutional neural networks(CNN).

## Setup for Python:

1. Install Python ([Setup instructions](https://wiki.python.org/moin/BeginnersGuide/Download))

2. Install Python packages
  
## Training The Model:
1. Download the data from [kaggle](https://www.kaggle.com/datasets/arjuntejaswi/plant-village).
2. Only keep folders related to Potatoes.
3. Open Google Colab in Browser.
4. Mount Your Google Drive.
5. Open "/content/drive/MyDrive/Colab Notebooks/ Disease Classification " in Google Colab.
6. Run all the Cells one by one.
7. Save The Generated Model.

## Results:
Results after training 2152 images Potato Leaves.

* number of epochs = 10
* training data / validation data split = 80/20
* MODEL:
  - CONV 3x3 filter layers with batch norm - 32 x 64 x 96 x 96 x 64
  - Dense layers with drop out of 0.2 and 0.3 - 256 x 128 x 2

loss: 0.1685
accuracy: 0.9410
val_loss: 0.2451
val_accuracy: 0.8958
