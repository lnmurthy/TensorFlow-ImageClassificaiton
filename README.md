# MNIST Image Classification using TensorFlow and Keras

This project demonstrates how to build a simple neural network model using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

## Prerequisites

- Python 3.x
- TensorFlow
- Keras
- Matplotlib

## Getting Started

### Installation

Ensure you have Python installed on your system. Install the required libraries using pip:

```bash
pip install tensorflow keras matplotlib
```

### Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

2. Run the script:

```bash
python mnist_classification.py
```

## Description

The script performs the following steps:

1. **Loading the Dataset**: The MNIST dataset is loaded using TensorFlow's Keras API. The training and test data are then assigned to their respective variables.

2. **Data Preprocessing**: Pixel values are scaled down from the range 0-255 to 0-1 to ease computation.

3. **Visualizing Data**: The shape of the training and test data is printed, and the first image in the training set is displayed using Matplotlib.

4. **Defining the Neural Network**: A sequential model is created using TensorFlow's Sequential API. It consists of a Flatten layer, a Dense layer with ReLU activation, and an output Dense layer with softmax activation.

5. **Compiling the Model**: The model is compiled using the Adam optimizer and sparse categorical cross-entropy loss function.

6. **Training the Model**: The model is trained on the training data for 20 epochs.

7. **Model Evaluation**: The trained model is evaluated on the test data to determine its accuracy.

8. **Saving the Model**: The trained model is saved for future use.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by the desire to learn and implement neural networks for image classification.
- Credits to the MNIST dataset provided by Yann LeCun and Corinna Cortes.
- Special thanks to the TensorFlow and Keras communities for their excellent documentation and resources.
