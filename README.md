# Cryptography and Machine Learning Project

## Overview

This project demonstrates the integration of cryptography techniques with machine learning for classifying encrypted texts based on their encryption modes (ECB, CBC, OFB). It involves generating random sentences, encrypting them using different AES modes, storing the data, and applying machine learning models to classify the encryption modes.

## Modules

The project is divided into three main modules:

1. **Data Generation and Encryption Module**: Generates random sentences and encrypts them using AES in ECB, CBC, and OFB modes.
2. **Data Storage Module**: Saves the generated and encrypted data to a CSV file.
3. **Machine Learning Pipeline Module**: Loads the data, preprocesses it, applies feature extraction, trains various classifiers, and evaluates their performance.

## Dependencies

- Python 3.x
- cryptography
- pandas
- scikit-learn

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/cryptography-and-machine-learning.git
cd cryptography-and-machine-learning
pip install -r requirements.txt
```

## Usage

Run the main execution script to generate data, encrypt it, store it, and train machine learning models:

```bash
python main.py
```

This script will output the performance metrics (accuracy, precision, recall, F1 score) for each classifier (Random Forest, Gradient Boosting, SVM-RBF, AdaBoost) along with the best parameters found through grid search.

## Contributing

Contributions are welcome Please feel free to submit pull requests or open issues for bugs, improvements, or new features.

## License

MIT License

Citations:
