# Simple ANN Model using MNIST Dataset

This repository contains a simple Artificial Neural Network (ANN) model built using the MNIST dataset. The MNIST dataset is a well-known dataset consisting of 70,000 images of handwritten digits, split into 60,000 training images and 10,000 test images.

## Overview

The purpose of this project is to demonstrate a basic implementation of an ANN for image classification tasks. The model is designed to recognize handwritten digits from 0 to 9. This project serves as a starting point for those interested in exploring neural networks and deep learning.

## Features

- Simple and easy-to-understand implementation of an ANN.
- Uses the MNIST dataset for training and testing.
- Achieves a reasonable accuracy for handwritten digit recognition.
- Modular and easy-to-extend code structure.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/simple-ann-mnist.git
    cd simple-ann-mnist
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook ANN_Implementation.ipynb
    ```

2. Run the cells in the notebook to train and evaluate the model.

## Project Structure

simple-ann-mnist/
│
├── data/
│ └── mnist/ # Contains the MNIST dataset (if needed)
│
├── models/
│ └── ann_model.py # ANN model definition (if applicable)
│
├── utils/
│ └── data_loader.py # Data loading and preprocessing utilities (if applicable)
│
├── ANN_Implementation.ipynb # Jupyter Notebook with the ANN implementation
├── requirements.txt # Python dependencies
└── README.md # Project description


## Results

The model achieves an accuracy of approximately X% on the test set after Y epochs of training. Below are some sample predictions:

| Input Image | Predicted Label | Actual Label |
|-------------|------------------|--------------|
| ![sample1](path_to_image1) | 7                | 7            |
| ![sample2](path_to_image2) | 2                | 2            |
| ![sample3](path_to_image3) | 1                | 1            |

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

