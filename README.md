# ImageClassificationOf_ASL_Dataset
Image Classification of an American Sign Language Dataset using Data Augmentation and CNN  

### Description  
In this model, we performed data preparation, model creation, and model training steps on the dataset: images of hands making letters in American Sign Language.  
Using only the concept of Convolution Neural Network, vastly improves the model's performance, as it is designed to recognize important features in the images. The validation accuracy is still lagging behind the training accuracy, which is a sign of overfitting: the model is getting confused by things it has not seen before when it tests against the validation dataset. In order to teach our model to be more robust when looking at new data, we're going to programmatically increase the size and variance in our dataset. This is known as data augmentation. The increase in size gives the model more images to learn from while training. The increase in variance helps the model ignore unimportant features and select only the features that are truly important in classification, allowing it to generalize better.  
So in this model, we have performed Convolutional Neural Network along with the concept of Data Augmentation. This improves the model's accuracy and performance.  

### Installtions  
1. Numpy
2. Tensorflow  
3. Keras  
4. Matplotlib.pyplot  

### Dataset  
Dataset - Images of hands making letters in American Sign Language is available on the Kaggle.  
The American Sign Language alphabet contains 26 letters.  
Two of those letters (j and z) require movement, so they are not included in the training dataset.  
![a](https://user-images.githubusercontent.com/57897678/121863052-10859b00-cd19-11eb-8c57-de32beb9fa34.png)  



