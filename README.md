# Loan-Eligibility-Prediction-ML
# Loan Eligibility Prediction System

![Project Image](project_image.png)

> A machine learning project to predict loan eligibility for Dream Housing Finance company.

---

## Table of Contents

- [About](#about)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## About

The Loan Eligibility Prediction System is a machine learning project developed to automate the loan approval process for Dream Housing Finance company. The project utilizes customer data such as gender, marital status, education, income, credit history, and property area to predict loan eligibility. The main goal of the project is to determine which machine learning model achieves the highest accuracy in predicting loan eligibility, thus enabling the company to make more informed and efficient decisions regarding loan approvals.

---

## Dataset

The dataset used for this project contains information about customers applying for home loans, including demographic details, financial information, and loan approval status. It consists of the following columns:

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target)

The dataset is sourced from Kaggle: [Loan Prediction Dataset](https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset)

---

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/Loan-Eligibility-Prediction-ML.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage

1. Navigate to the project directory:
    ```bash
    cd Loan-Eligibility-Prediction-ML
    ```
2. Run the main script to train and evaluate the models:
    ```bash
    python main.py
    ```

---

## Models

The project utilizes the following machine learning models for loan eligibility prediction:


- Decision Tree
- Random Forest
- Support Vector Machine

---

## Results

The performance of each model is evaluated based on accuracy. Here are the accuracy scores achieved by each model:

- Decision Tree: 0.6944
- Random Forest: 0.75
- Support Vector Machine: 0.75

---

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- This project was inspired by the loan eligibility prediction problem faced by financial institutions.
- Dataset source: [Kaggle - Loan Prediction Dataset](https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset)


