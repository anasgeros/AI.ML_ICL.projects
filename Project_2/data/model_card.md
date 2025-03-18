# Model Card
CIFAR-10 dataset (Canadian Institute For Advanced Research Dataset)

## Model Description

**Input:** 6000 32x32 images extracted from the web

**Output:** Classified images: a label (consisting of a category and specific identification) are attributed to each image.
**Model Architecture:** CNN 
(VGG-19 performed best:
16 convolutional layers
5 pooling layers (max)
1 flattening layer
3 dense layers
38,947,914 parameter); 

## Performance

Precision - 88%; Recall - 88%; F1-Score - 88%; Accuracy - 88%
![Screenshot](img.png)

## Limitations

Used quite a lot of computing resources (complex model). Can probably stilll improve.
## Trade-offs

Before model tuning accuracy was below 60%. Needed a lot of tweaking, meaning there's maybe a better algorithm to start with.
