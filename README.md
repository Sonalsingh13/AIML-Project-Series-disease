# Disease Prediction System using Machine Learning

The Disease Prediction System using Machine Learning aims to predict the likelihood of a person having a particular disease based on health-related features. This system leverages machine learning algorithms to analyze historical health data, aiding in early disease detection and proactive healthcare management.

## Objectives

1. **Data Collection**: Gather a diverse dataset with features like age, gender, BMI, blood pressure, cholesterol levels, and family medical history.
2. **Data Preprocessing**: Clean, preprocess, and scale the data.
3. **Feature Selection**: Identify the most influential features.
4. **Model Development**: Implement and compare various machine learning algorithms.
5. **Cross-Validation**: Assess models to mitigate overfitting.
6. **Hyperparameter Tuning**: Optimize model performance.
7. **Optional**: Model interpretability, user interface, integration with EHR, and documentation.

## Dataset

The project uses the Kaggle Heart Disease dataset. Ensure you have `heart.csv` in the `data` directory.

## Project Structure

.
├── data
│ └── heart.csv
├── disease_prediction.py
├── README.md
└── requirements.txt


## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/disease-prediction-system.git
    cd disease-prediction-system
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure the dataset is in the `data` directory.
2. Run the script:
    ```bash
    python disease_prediction.py
    ```

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Results

The script outputs the accuracy, confusion matrix, and classification report for each model, along with cross-validation results.
