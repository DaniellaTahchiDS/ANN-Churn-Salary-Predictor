# Machine Learning Project

A collection of machine learning experiments and models for various prediction tasks including churn modeling, salary regression, and general classification problems.

## Project Structure

```
├── app.py                          # Main application/deployment script
├── Churn_Modelling.csv            # Dataset for customer churn prediction
├── experiments.ipynb              # Jupyter notebook for ML experiments
├── hyperparametertuningann.ipynb  # ANN hyperparameter tuning experiments
├── prediction.ipynb               # Model prediction demonstrations
├── salaryregression.ipynb         # Salary prediction regression model
├── model.h5                       # Saved neural network model
├── requirements.txt               # Python dependencies
└── Preprocessing files:
    ├── label_encoder_gender.pkl   # Gender label encoder
    ├── onehot_encoder_geo.pkl     # Geography one-hot encoder
    └── scaler.pkl                 # Feature scaler
```

## Features

- **Churn Modeling**: Predict customer churn using artificial neural networks
- **Salary Regression**: Estimate salaries based on various features
- **Hyperparameter Tuning**: Optimize ANN models for better performance
- **Preprocessing Pipeline**: Complete preprocessing with encoders and scalers
- **Model Deployment**: Ready-to-use application script

## Getting Started

### Prerequisites

Install required dependencies:
```bash
pip install -r requirements.txt
```

### Running the Application

```bash
python app.py
```

### Exploring Experiments

Open and run the Jupyter notebooks:
- `experiments.ipynb` - General ML experiments
- `hyperparametertuningann.ipynb` - ANN optimization
- `prediction.ipynb` - Model predictions
- `salaryregression.ipynb` - Salary prediction analysis

## Model Details

The project uses Artificial Neural Networks (ANNs) with:
- Saved model weights in `model.h5`
- Preprocessed data using label encoders and scalers
- Optimized hyperparameters for improved accuracy

## Data

The main dataset (`Churn_Modelling.csv`) contains customer information for predicting churn behavior.

---

*Last updated: 3 months ago*
