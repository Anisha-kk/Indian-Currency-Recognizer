# Indian-Currency-Recognizer
## Overview
This project trains a ML model to recognise Indian Currency notes. There are 6 denominations of Indian Currency notes as of now(2026). They are as follows:

Rs. 10
Rs. 20
Rs. 50
Rs. 100
Rs. 200
Rs. 500
Rs. 2000 notes, though not currently produced, is still under circulation. So images with 2000 rupee notes are also considered.
## Dataset
Source: https://www.kaggle.com/datasets/vishalmane109/indian-currency-note-images-dataset-2020/data?status=pending
## Result
Two approaches were used:
1. A CNN was build from scratch and trained. The accuracy of the model on test data  was ~66%
2. Transfer Learning - A pretrained ResNet50 model with a classifier head was used along with data augmentation for training. The accuracy of the model on test data increased to ~85%.
