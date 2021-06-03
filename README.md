# Mask-Detector

This project is to build an image classifier to predict whether a person is wearing a mask or not.

Few details about the model/methodology:

1. Datasets used: Kaggle dataset https://www.kaggle.com/omkargurav/face-mask-dataset with ~12k images 
2. resnet18 architecture with pre-trained weights is used to train the model with fine tuning done for the above datasets
3. python libraries used: fastai
4. Model training code is present in file: mask-detector-model-code.ipynb. Code to deploy the model into an online app using binder is present in mask_detector_app.ipynb
