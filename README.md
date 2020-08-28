# Face-Emotion-Recognition
The objective is to develop a facial expression recognition algorithm using CNN network based on 7 key emotions - anger, disgust, fear, happiness, sadness, surprise and neutral. While working on the data, we also tried to explore data generation and image captioning techniques like Variational AutoEncoder (VAE) and Recurrent Neural Networks (RNN). Using VAE, we tried to generate additional low resolution images from the training data.

- Predicting an emotion of a 48*48 pixel face image from labels - anger, disgust, fear, happiness, sadness, surprise, and neutral
- Scaling the pixels from [0,255] to [0,1] and using Data Augmentation techniques to fit and align the training images
- Fusion network of VGG19 and ResNet18 models to get an accuracy of 60% on fer2013 dataset
