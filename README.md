**Project Title: CIFAR-100 Image Classification with Convolutional Neural Networks (CNNs) using TensorFlow**

**Description:**

This repository contains code for building a Convolutional Neural Network (CNN) model to classify images in the CIFAR-100 dataset. The CIFAR-100 dataset consists of 100 classes, each containing 600 images, making it a challenging image classification task.

The achievable benchmark accuracy for this dataset is set to 39.43%, as it is a subset of the main CIFAR-100 dataset.

**Dependencies:**

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

**Dataset:**

The CIFAR-100 dataset consists of 50,000 training images and 10,000 test images, each with a size of 32x32 pixels. Images are divided into 100 classes, with each class containing 600 images. The dataset is commonly used for benchmarking image classification algorithms.

**Code Structure:**

- `train.py`: Python script for training the CNN model on the CIFAR-100 dataset.
- `test.py`: Python script for evaluating the trained model on the test set.
- `model.py`: Python script containing the CNN model architecture definition.
- `utils.py`: Python script containing utility functions for data preprocessing and visualization.
- `requirements.txt`: Text file listing all required dependencies for the project.

**Results:**

- The benchmark accuracy for the CIFAR-100 dataset is set to 39.43%.
- After training and testing the CNN model, the achieved accuracy is reported in the console output.
- I was able to achieve 33.31% accuracy, which corresponds to correctly identifying 84% of the objects.

**References:**

- CIFAR-100 Dataset: https://www.cs.toronto.edu/~kriz/cifar.html
- TensorFlow Documentation: https://www.tensorflow.org/
- TensorFlow GitHub Repository: https://github.com/tensorflow/tensorflow

**Contributing:**

Contributions to the project are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

**License:**

This project is licensed under the MIT License. See the `LICENSE` file for details.

**Author:**
Upenyu Hlangabeza


**Acknowledgments:**

- Special thanks to the creators of the CIFAR-100 dataset for providing a valuable resource for image classification research.
- Thanks to the TensorFlow team for developing an excellent deep learning framework.
