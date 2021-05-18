# Cats_and_Dog_Classifier_CNN
For this project, I made a cats and dog classifier using Convolution Neural Network.
Specifically I used:
1. ```Conv2D``` Layer - Kernel size of 3x3 and ```relu``` as activation function. In total 3 such layers were used.
2. ```MaxPooling2D``` - Max-pooling is performed over a 2 × 2 pixel window. In total 3 such layers were used.
3. ```Dropout``` Layer - A dropout of 20% is applied with a larger dropout rate of 50% applied after the fully connected layer in the classifier part of the model.

After this I used ```Flatten```  and ```Dense``` layer to classify the input in two available classes (Cats and Dogs).
For training and validation part I used: https://www.kaggle.com/chetankv/dogs-cats-images. 
And for testing part a random dataset containing cats and dogs images in no specific order.
