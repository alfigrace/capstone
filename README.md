# C22-PS020 - Capstone Project (Paranmo)
Welcome to Machine Learning repository of Paranmo Application (From Bangkit Capstone Project Team C22-PS020)!

See the link of C22-PS020: Team Repository

This repository is managed by the Machine Learning members:

- M7414F2984 Alfi Nazilah
- M2227F2098 Vita Nurhayati

## The Process
In developing this application, there are some processes that we had done:

- Import libraries needed
- Download the dataset from kaggle and we modify a little bit
- Mount the dataset from google drive
- Load data using DataLoader and split dataset to train, test, and validation dataset 
- Display some image examples from dataset
- Adding augmentation
- Create Transfer Learning Model (MobileNetV2) and Train the model with 32 batch size
- Evaluate the first model  use the test dataset and image prediction
- Adding some augmentation and retrain the model with 16 batch size
- Evaluate second model use the test dataset and image prediction
- Post training quantization to reduce model size and inference latency
- Convert to Tensorflow Lite format so the Machine Learning model can be deployed in Android App

Link: [Machine Learning Model](https://github.com/alfigrace/capstone/blob/machine-learning/BestModelParanmo.ipynb)
Link Dataset:
[Dataset](https://www.kaggle.com/datasets/anefiamutiaraatha/dataset-tanaman-herbal)
[Dataset](https://drive.google.com/drive/folders/1sKbjP0QpJkjEVmW8y695nc3_nrZ-YF44)
