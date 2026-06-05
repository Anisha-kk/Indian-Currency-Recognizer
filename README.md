# Indian-Currency-Recognizer
## Overview
This project trains a ML model to recognise Indian Currency notes. There are 6 denominations of Indian Currency notes as of now(2026). They are as follows:
1. Rs. 10
2. Rs. 20
3. Rs. 50
4. Rs. 100
5. Rs. 200
6. Rs. 500
7. Rs. 2000 notes, though not currently produced, is still under circulation. So images with 2000 rupee notes are also considered.
<br>Background images without currency were also used for training.
## Dataset
Source: https://www.kaggle.com/datasets/vishalmane109/indian-currency-note-images-dataset-2020/data?status=pending
## Training
Two approaches were used:
1. A CNN was build from scratch and trained. The accuracy of the model on test data  was ~66%
2. Transfer Learning - A pretrained ResNet50 model with a classifier head was used along with data augmentation for training. The accuracy of the model on test data increased to ~85%.<br>
## Result - Example
Input: <br>
<img width="390" height="280" alt="100_15" src="https://github.com/user-attachments/assets/4ce9e157-bfbe-4f84-82f6-324757e276af" />
<br> Output Prediction: 100

