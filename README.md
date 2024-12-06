# Loan Eligibility Prediction

This project is designed to predict loan eligibility based on various applicant details using machine learning. By leveraging a dataset of past applicants and their outcomes, the model learns patterns to identify whether a loan applicant is likely to meet eligibility criteria.

## Features

- Predicts loan eligibility using applicant details such as income, credit history, education, etc.
- Supports various machine learning models for training and testing however here we have used Logistic Regression technique.
- It provides Provides an easy-to-use interface for testing predictions on new applicant data.

## Table of Contents

1. [Usage](#usage)
2. [Dataset](#dataset)
3. [Model Details](#model-details)
4. [Results](#results)
5. [Contributing](#contributing)


---

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-ajeet20/loan-eligibility-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd loan-eligibility-prediction
   ```


## Usage

1. Prepare your dataset and ensure it is in the required format (CSV).

2. Train the model by running:

   ```bash
   python train.py
   ```

3. Test the model by providing test data:

   ```bash
   python predict.py --input test_data.csv
   ```

4. View results in the console or saved output files.

## Dataset

The dataset should include the following columns (or similar):

- **ApplicantIncome**: The applicant's income
- **CoapplicantIncome**: The co-applicant's income
- **LoanAmount**: The amount of loan applied for
- **Loan_Amount_Term**: Term of loan in months
- **Credit_History**: Credit history (1 for good, 0 for bad)
- **Gender**: Gender of the applicant
- **Married**: Marital status
- **Education**: Educational background
- **Self_Employed**: Employment status
- **Property_Area**: Urban, Semi-Urban, or Rural
- **Loan_Status**: Target column (Y/N)



Example datasets can be found in the `https://github.com/Ajeetv20/Loan-Eligibility-Prediction/blob/main/Loan-train%20Logistic%20Regression.ipynb`& `https://github.com/Ajeetv20/Loan-Eligibility-Prediction/blob/main/Test-Train%20Logistic%20Regression%20.ipynb` directory.

## Model Details

- **Data Preprocessing**: Here we have fill the missing values as there the no. of missing values was not high, and lable encoder to encode the values.
- **Algorithms**: This model includes Algorithms like Logistic Regression, and SVM.
- **Evaluation Metrics**: Accuracy, Precision, Recall.

## Results

After training, model performance metrics are displayed and saved in the `https://github.com/Ajeetv20/Loan-Eligibility-Prediction/blob/main/Loan-train%20Logistic%20Regression.ipynb` directory. Adjust parameters to improve predictions based on the provided evaluation metrics.

## Contributing

Contributions are welcome! Follow these steps:

1. Fork this repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit:

   ```bash
   git commit -m "Add your message here"
   ```

4. Push to the branch:

   ```bash
   git push origin feature-name
   ```

5. Create a pull request.



