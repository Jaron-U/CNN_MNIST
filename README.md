### Implatement a CNN model to classify the MNIST dataset

The MNIST dataset is a dataset of handwritten digits. It has 60,000 training samples, and 10,000 test samples. Each image is 28x28 pixels, and each pixel is a grayscale value between 0 and 255. The labels are integers between 0 and 9.

Using the ResNet architecture. The model is trained on the MNIST dataset and achieves an accuracy of 98.4% on the test set.
With the following hyperparameters:
- Learning rate: 0.001
- Batch size: 32
- Number of epochs: 20
- Optimizer: Adam
- Loss function: Cross Entropy Loss
- CNN parameters:
  'n_layers': 7, 'cnn_channels': 32, 'linear_hidden': 500, 'kernel_size': (4, 4), 'drop_rate': 0.2


