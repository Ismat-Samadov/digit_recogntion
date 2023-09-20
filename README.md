# Digit Recognition

## Description

This project is a digit recognition system developed for the Kaggle Digit Recognition competition. The goal of this project is to build a machine learning model that can accurately classify hand-written digits (0 through 9) based on pixel values. The project involves data preprocessing, model development, training, and evaluation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up and run this project, follow these steps:

1. Clone the repository to your local machine:

https://github.com/Ismat-Samadov/digit_recogntion.git
   

2. Navigate to the project directory:

   cd digit_recogntion

3. Install the required dependencies using pip:

pip install keras

## Usage

To use this project, you can follow these steps:

1. Prepare your training and test data in CSV format.

2. Run the main script to preprocess the data, train the model, and make predictions:

   Replace `data/train.csv` and `data/test.csv` with the paths to your training and test data files, and specify the desired output file name.

## Data

The project uses the Kaggle Digit Recognition dataset, which can be obtained from [Kaggle's Digit Recognition competition] https://www.kaggle.com/competitions/digit-recognizer .
The dataset consists of hand-written digit images in grayscale, with each image represented as a 28x28 pixel grid.

## Model

The neural network model used in this project consists of the following layers:

- Input Layer (784 neurons)
- Hidden Layer 1 (3000 neurons, ReLU activation)
- Hidden Layer 2 (2000 neurons, ReLU activation)
- Hidden Layer 3 (1000 neurons, ReLU activation)
- Hidden Layer 4 (500 neurons, ReLU activation)
- Hidden Layer 5 (250 neurons, ReLU activation)
- Hidden Layer 6 (64 neurons, ReLU activation)
- Output Layer (10 neurons, softmax activation)

The model is trained using the Adam optimizer and the sparse categorical cross-entropy loss function.

## Results

The project achieved the following results:

- loss: 0.0051 
- accuracy: 0.9994

Additionally, the project includes visualizations of training and validation loss and accuracy over epochs.

## Contributing

Contributions to this project are welcome. To contribute, please follow these guidelines:

- Open an issue to discuss proposed changes or bug fixes.
- Fork the repository and create a new branch for your feature.
- Make changes, add tests if applicable, and ensure the code is well-documented.
- Submit a pull request with your changes.

## License

---

## Acknowledgments

- The project is inspired by the Kaggle Digit Recognition competition.
- Thanks to the creators of the Kaggle Digit Recognition dataset for providing the data.
