# Credit Card Fraud Detection Project

This project aims to detect fraudulent credit card transactions using machine learning models. The dataset consists of over 1 million transactions, each with multiple features such as transaction amount, location, merchant details, and more. The primary objective is to identify fraudulent transactions (target variable: `is_fraud`) while ensuring the accuracy and efficiency of the model.

## Project Overview

### Dataset
The dataset contains the following columns:
- `trans_date_trans_time`: Timestamp of the transaction.
- `cc_num`: Credit card number.
- `merchant`: Merchant name.
- `category`: Transaction category.
- `amt`: Transaction amount.
- `first`, `last`: Customer's first and last name.
- `gender`: Customer's gender.
- `street`, `city`, `state`: Address details.
- `zip`: ZIP code.
- `lat`, `long`: Latitude and longitude of the transaction.
- `city_pop`: Population of the transaction's city.
- `job`: Customer's job.
- `dob`: Customer's date of birth.
- `trans_num`: Transaction number.
- `unix_time`: Transaction time in UNIX format.
- `merch_lat`, `merch_long`: Latitude and longitude of the merchant.
- `is_fraud`: Target variable (1 for fraud, 0 for non-fraud).

### Workflow
1. **Data Preprocessing**:
   - Handled missing values using appropriate strategies (e.g., mean, median, mode).
   - Encoded categorical variables using Label Encoding and One-Hot Encoding.
   - Standardized numerical features to ensure uniformity.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized correlations using a heatmap.
   - Analyzed distributions of transaction amounts and city populations.
   - Explored relationships between features and the target variable using pair plots and count plots.

3. **Feature Engineering**:
   - Extracted additional features such as transaction hour and day.
   - Removed irrelevant or redundant columns.

4. **Model Building**:
   - Implemented Logistic Regression and Random Forest Classifier for fraud detection.
   - Evaluated models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

5. **Visualization**:
   - Highlighted feature importance using bar plots.
   - Plotted ROC-AUC curves to assess model performance.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd credit-card-fraud-detection
   ```

3. **Install Dependencies**:
   Ensure you have Python installed (version 3.7 or higher).
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

## Results
- Achieved an accuracy of over 99% using Random Forest Classifier.
- Visualizations provided insights into patterns associated with fraudulent transactions.
- Enhanced interpretability by analyzing feature importance and correlation.

## Future Work
- Integrate additional data sources for improved accuracy.
- Experiment with deep learning models for further enhancement.
- Deploy the model as a real-time fraud detection system.

## Data
The data used in this project can be found [here](https://drive.google.com/drive/folders/1mEqyaX8K5dzxs5AbfsdLYqw8pM2FTk3O?usp=drive_link).

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## Contact
For questions or suggestions, please reach out to nadeemasha9598@gmail.com

