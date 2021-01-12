# Flower-Recognition-Model-CNN
A custom CNN model developed using python for recognising five famous flower classes

**Project Description:**

This project aims to detect the classification of various flowers. The dataset was acquired from Kaggle. In this dataset, there are 5 classes of flowers (Daisy, Dandelion, Rose, Sunflower, and Tulip), and for each class, there are about 800 images. The recognition was done by selecting and training a sequential model using the aforementioned dataset.

**Discussion:**

The accuracy of the model is not that precise because we took input images as 1-channel GRAYSCALE and lost all the color information. For flower recognition accuracy, color information is one of the biggest factors along with the shape. The accuracy can be further optimized by taking 3-channel RGB inputs.

**Future Direction**

- Bigger dataset should be used to improve the prediction accuracy.
- Training and prediction should be done with consideration for the color channels.
- Object detection with bounding boxes maybe implemented to detect multiple classes from one image.
- Realtime recognition maybe implemented to detect the classes from video sources.
