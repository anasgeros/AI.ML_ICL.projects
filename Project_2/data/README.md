## INTRODUCTION
This project involves teaching a computer to recognize and categorize images into 10 different categories, such as airplanes, cars, birds, and more. Using a dataset known as CIFAR-10, which consists of thousands of small images, the goal is to develop a model that can accurately identify these images. This helps in understanding how machines can interpret visual data similarly to how humans do.

## DATA
The data used in this project is the CIFAR-10 dataset, which contains 60,000 32x32 color images evenly distributed across 10 classes. Each class has 6,000 images. This dataset is widely used for machine learning research and was collected by the Canadian Institute for Advanced Research (CIFAR). [Learning Multiple Layers of Features from Tiny Images, Alex Krizhevsky et al 2009.]

## MODEL 
The model employed for this project is a Convolutional Neural Network (CNN), specifically designed for handling image data. CNNs are effective for image classification tasks because they can automatically detect important features without any human intervention. This model was chosen due to its success in similar tasks and its ability to handle the complexity and volume of the CIFAR-10 dataset.

## HYPERPARAMETER OPTIMISATION
Hyperparameters in this project include learning rate, number of layers, batch size and data augmentation. These were optimized to find the best settings for the model. This approach helps in exploring a wide range of possibilities and refining the model based on performance metrics like accuracy.

## RESULTS
The model achieved a classification accuracy of over 88% on the validation set, indicating a high level of effectiveness in recognizing and categorizing the images from the CIFAR-10 dataset. This result demonstrates the capability of convolutional neural networks to interpret visual data and highlights the potential applications in automated image recognition systems.

![Screenshot](img.png)
