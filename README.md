# Fraud-Detection-ML-Project
# Online Payments Fraud Detection with Machine Learning

This project implements a machine learning model to detect fraudulent online payments. It uses a dataset containing historical transaction data from Kaggle to train and evaluate a Random Forest Classifier.

## Project Structure

* `main.py`: Contains the Python code for data loading, preprocessing, model training, and evaluation.
* `online_payments_fraud_dataset.csv`: The dataset used for training the model. (Optional, provide link if too large)
* `processed_fraud_data.csv`: Output of processed data.
* `predictions.csv`: Output of model predictions.
* `fraud_distribution.png`: Plot showing the distribution of fraudulent vs. non-fraudulent transactions.
* `transaction_type_fraud.png`: Plot showing fraud distribution by transaction type.
* `feature_importance.png`: Plot showing the importance of features in the trained model.
* `flowchart.png`: A visual representation of the project workflow. (Add if you have one)

## Dataset

[cite_start]The dataset is sourced from Kaggle and includes the following columns[cite: 6, 7]:
* [cite_start]`step`: Represents a unit of time (1 step = 1 hour)[cite: 8].
* [cite_start]`type`: Type of online transaction[cite: 9].
* [cite_start]`amount`: The amount of the transaction[cite: 10].
* [cite_start]`nameOrig`: Customer starting the transaction[cite: 11].
* [cite_start]`oldbalanceOrg`: Balance before the transaction for the originator[cite: 12].
* [cite_start]`newbalanceOrig`: Balance after the transaction for the originator[cite: 13].
* [cite_start]`nameDest`: Recipient of the transaction[cite: 14].
* [cite_start]`oldbalanceDest`: Initial balance of recipient before the transaction[cite: 15].
* [cite_start]`newbalanceDest`: New balance of recipient after the transaction[cite: 15].
* [cite_start]`isFraud`: Indicates a fraudulent transaction (1 if fraud, 0 if not)[cite: 16].
* `isFlaggedFraud`: Indicates if the transaction was flagged as fraud by the system.

## Setup and Running the Project

### Prerequisites

* Python 3.x
* Pip (Python package installer)

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/Online-Payments-Fraud-Detection.git](https://github.com/your-username/Online-Payments-Fraud-Detection.git)
    cd Online-Payments-Fraud-Detection
    ```
2.  Install the required Python packages:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

### Running the Code

Execute the main Python script:
```bash
python main.py
