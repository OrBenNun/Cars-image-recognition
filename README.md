# Cars-image-recognition
![alt text]()


The present project involves preprocessing a dataset of 16,000 car images into 196 distinct classes. To mitigate overfitting issues, we applied several data augmentation techniques, including Resize, RandomRotation, ColorJitter, RandomResizedCrop, RandomHorizontalFlip, and Normalize. Following this, we implemented three advanced techniques to achieve high classification accuracy: Transfer Learning, Image Retrieval, and End-To-End CNN.

For Transfer Learning, we employed ResNet, DenseNet, and VGG models to classify the images. As for Image Retrieval, we used ResNet, VGG, and a transfer learning model as a base, along with KNN and majority voting to determine the results of our models. Lastly, we designed our own architecture for each experiment and built an End-To-End CNN from scratch, utilizing various techniques, such as 3-5 convolutional layers, max pooling, fully connected layers, Relu and Sigmoid activation functions, as well as dropouts.
