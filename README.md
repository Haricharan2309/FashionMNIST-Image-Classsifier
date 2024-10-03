# FashionMNIST Classification

This project trains three different models to classify images from the FashionMNIST dataset. The models are:

**1. FashionMNISTModelV0**
* A simple linear model with a flatten layer.
* Achieves an accuracy of 83.43% on the test set.

**2. FashionMNISTModelV1**
* A model with both linear and non-linear layers (ReLU activation).
* Achieves an accuracy of 75.02% on the test set.

**3. FashionMNISTModelV2**
* A convolutional neural network (CNN) inspired by the TinyVGG architecture.
* Achieves the highest accuracy of 88.07% on the test set.

## Dependencies

The following libraries are required to run the code:

* PyTorch
* torchvision
* matplotlib
* requests
* tqdm
* torchmetrics
* mlxtend
* pandas
## Usage

To train the models, simply run the Jupyter notebook `Untitled2.ipynb`. The notebook will download the FashionMNIST dataset, train the models, and evaluate their performance on the test set.

The code also includes functions for:

* Visualizing the training and testing progress.
* Evaluating the trained models on the test dataset.
* Making predictions on new images.
* Plotting a confusion matrix to visualize the model's performance.

## Results

The results of the three models are summarized in the following table:

| Model Name          | Test Loss | Test Accuracy | Training Time (seconds) |
|---------------------|-----------|---------------|-------------------------|
| FashionMNISTModelV0 | 0.4766    | 83.43%        | 33.04                   |
| FashionMNISTModelV1 | 0.6850    | 75.02%        | 34.24                   |
| FashionMNISTModelV2 | 0.3272    | 88.07%        | 160.27                  |

As you can see, the CNN model (FashionMNISTModelV2) achieves the best performance, followed by the simple linear model (FashionMNISTModelV0). The model with non-linearity (FashionMNISTModelV1) does not perform as well as the other two models.

This README file provides a brief overview of the project and its contents. For more detailed information, please refer to the Jupyter notebook and the source code.
