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
  - CONV 3x3 filter layers with batch norm - 32 x 64 x 64 x 64 x 64 x 64 
  - loss: 0.1685
  - accuracy: 0.9410
  - val_loss: 0.2451
  - val_accuracy: 0.8958
* The model was tested on the images. The performance of the model was very good and was able to predict the Disease with 94% accuracy.

Plots for model accuracy and loss are following:

**X axis -- Accuracy**<br>
**Y axis -- Epoch**

![image](https://github.com/user-attachments/assets/3915b225-bc1f-461c-85c9-f7e593823852)

Classifying the images:

![image](https://github.com/user-attachments/assets/fbe58a6f-2cbd-457f-9b03-f79a7d2a8b50)<br>
![image](https://github.com/user-attachments/assets/de150ea8-2585-462e-bccb-cf4fab6e97f8)<br>
![image](https://github.com/user-attachments/assets/51f385c8-a994-45ff-893d-21e910b62d87)<br>
![image](https://github.com/user-attachments/assets/de3dbeb4-b511-4e13-9a0e-03f271c948bb)<br>
![image](https://github.com/user-attachments/assets/f54647ec-e3bb-463a-b047-6da76e9797e3)<br>
![image](https://github.com/user-attachments/assets/a08b0f50-0bcd-4b28-b5d6-3a3ed4bf7297)<br>





