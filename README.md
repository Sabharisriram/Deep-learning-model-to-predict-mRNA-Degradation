# mRNA Degradation Prediction Model

This repository contains a deep learning model designed to predict mRNA degradation using RNA sequence data. The model employs a 3X BiGRU architecture, processes sequence data from JSON files into tokenized 3D NumPy arrays, and generates predictions for mRNA degradation under different conditions.

## Key Features
- **Data Preprocessing**: Converts sequence data from JSON into tokenized 3D NumPy arrays for model training.
- **Model**: A 3X BiGRU architecture used for sequence prediction.
- **Training**: The model is trained using a custom loss function (MCRMSE) and Adam optimizer.
- **Prediction**: Generates predictions on mRNA degradation for various conditions.
- **Submission**: Outputs predictions formatted for Kaggle submission.

## Dependencies
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- scikit-learn

## Project Structure
- `data/`: Contains training and testing datasets.
- `Model/`: Contains the model architecture and saved weights.
- `notebooks/`: Contains Jupyter notebooks for data analysis and model evaluation.
- `submission/`: Contains the final Kaggle submission file.
- `train.py`: Script for training the model.
- `predict.py`: Script for making predictions on the test dataset.
- `README.md`: This file.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mrna-degradation-prediction.git
