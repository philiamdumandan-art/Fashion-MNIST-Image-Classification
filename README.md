# Fashion-MNIST-Image-Classification

## Google Colab Link: https://colab.research.google.com/drive/1tsst8d46SMxuhaZANdB5dhb4hXdYvKyw?usp=sharing

### 1. What is the Fashion MNIST Dataset?
The Fashion-MNIST dataset was created as a direct, more difficult drop-in substitute for the original handwritten digit MNIST dataset. It consists of 70,000 grayscale photos of ten different apparel categories. With 60,000 training photos and 10,000 test images, it was developed by Zalando Research and is frequently used for assessing machine learning systems.

### 2. Why do we normalize image pixel values before training?
It enhances the model's generalization and overall performance while assisting with faster and more stable training.

### 3. List the layers used in the neural network and their functions.
While specialized layers like Convolutional, Pooling, and Dropout are utilized for various designs, especially in deep learning, the fundamental, universal levels are Input, Hidden, and Output layers.

### 4. What does an epoch mean in model training?
one full algorithmic run through the entire training dataset.


### 5. Compare the predicted label and actual label for the first test image.
The model predicted label 9 for the first test image, which matches the true label. Since label 9 corresponds to an ankle boot, the model correctly classified the image, showing it has learned to recognize this clothing item.

### 6. What could be done to improve the model’s accuracy?
collecting additional training data, implementing data augmentation techniques, refining data (addressing missing values and outliers), utilizing cross-validation, and optimizing hyperparameters.
