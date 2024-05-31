# jaulacon2024 Anomaly Detection

## TS Libraries
| Library  | Description                                                                                               | Installation            | Documentation                                              |
|----------|-----------------------------------------------------------------------------------------------------------|-------------------------|------------------------------------------------------------|
| tslearn  | A machine learning library for time series data, built on top of scikit-learn. It provides tools for time series classification, clustering, and regression. | `pip install tslearn`   | [tslearn Documentation](https://tslearn.readthedocs.io/en/stable/) |
| sktime   | A unified framework for machine learning with time series data. It provides time series classification, regression, clustering, and forecasting. | `pip install sktime`    | [sktime Documentation](https://www.sktime.org/en/stable/)  |
| seglearn | A library for time series and sequence data, which includes transformers and classification models compatible with scikit-learn. | `pip install seglearn`  | [seglearn Documentation](https://dmbee.github.io/seglearn/) |
| tsfresh  | Extracts relevant features from time series data to assist with classification tasks. It's often used in combination with other machine learning libraries like scikit-learn. | `pip install tsfresh`   | [tsfresh Documentation](https://tsfresh.readthedocs.io/en/latest/) |
| Kats     | A toolkit by Facebook for analyzing time series data. It includes modules for forecasting, detection, and classification. | `pip install kats`      | [Kats Documentation](https://facebookresearch.github.io/Kats/) |
| PyCaret  | An open-source, low-code machine learning library that simplifies the process of training and deploying models, including those for time series classification. | `pip install pycaret`   | [PyCaret Documentation](https://pycaret.org/)              |
| tsai     | A state-of-the-art deep learning library for time series and sequential data, built on top of fastai and PyTorch. | `pip install tsai`      | [tsai Documentation](https://timeseriesai.github.io/tsai/) |



## Credit fraud datasets

| Dataset Name                          | Description                                                                 | Instances   | Attributes | Classes | Type          |
|---------------------------------------|-----------------------------------------------------------------------------|-------------|------------|---------|---------------|
| Credit Card Fraud Detection Dataset   | Contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. | 284,807     | 30         | 2       | Financial     |
| IEEE-CIS Fraud Detection Dataset      | Designed to identify fraudulent online transactions. The dataset contains transactional data with features that are obfuscated. | 1,096,575   | 394        | 2       | Financial     |
| Fraudulent Financial Statements Data  | This dataset includes data on financial statements with labels for fraudulent or non-fraudulent cases. | 3,357       | 95         | 2       | Financial     |
| Synthetic Financial Datasets for Fraud Detection | Contains synthetic data generated to simulate real-world fraud scenarios, useful for testing anomaly detection algorithms. | Variable    | Variable   | 2       | Financial     |
| Lending Club Loan Data                | Dataset from Lending Club containing loan data with information on loans that were paid off and those that defaulted. | 2,260,701   | 145        | 2       | Financial     |
| PaySim Mobile Money Simulation        | Synthetic dataset simulating mobile money transactions to identify fraudulent activities. | 6,362,620   | 11         | 2       | Financial     |




## Anomaly detection datasets

| Dataset Name                    | Description                                                               | Instances | Attributes | Classes | Type      |
|---------------------------------|---------------------------------------------------------------------------|-----------|------------|---------|-----------|
| CardiacArrhythmia               | ECG data, useful for detecting cardiac anomalies.                         | 43673     | 1500       | 3       | ECG       |
| CinCECGTorso                    | ECG data from the torso, useful for detecting cardiac anomalies.          | 40        | 1639       | 4       | ECG       |
| ECG200                          | Simple ECG dataset for binary classification.                             | 200       | 96         | 2       | ECG       |
| ECG5000                         | Large ECG dataset with multiple classes.                                  | 5000      | 140        | 5       | ECG       |
| ECGFiveDays                     | Short ECG recordings, useful for time series analysis.                    | 884       | 136        | 2       | ECG       |
| FordA                           | Sensor data from Ford, suitable for anomaly detection in vehicles.        | 4921      | 500        | 2       | SENSOR    |
| FordB                           | Another sensor dataset from Ford, related to vehicle anomalies.           | 4446      | 500        | 2       | SENSOR    |
| ItalyPowerDemand                | Power demand data, useful for detecting anomalies in power consumption.   | 1096      | 24         | 2       | SENSOR    |
| MoteStrain                      | Sensor data measuring strain, useful for structural health monitoring.    | 1272      | 84         | 2       | SENSOR    |
| SonyAIBORobotSurface1           | Sensor data from a robot, suitable for anomaly detection in robotics.     | 621       | 70         | 2       | SENSOR    |
| SonyAIBORobotSurface2           | Additional sensor data from a robot, for anomaly detection.               | 980       | 65         | 2       | SENSOR    |
| StarLightCurves                 | Light curves data, suitable for detecting anomalies in astronomical data. | 9236      | 1024       | 3       | SENSOR    |
| Wafer                           | Sensor data from wafer manufacturing, useful for anomaly detection.       | 7164      | 152        | 2       | SENSOR    |


References: https://timeseriesclassification.com/dataset.php


## Usage
1. Clone the repository.
2. Install python and jupyter lab.
3. Follow the notebook instructions.
