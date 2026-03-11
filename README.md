# Financial Health Prediction Using Machine Learning

## 1. Problem Statement
Across Southern Africa, small and medium-sized enterprises (SMEs) are vital to employment, innovation, and economic growth, yet many remain financially fragile and excluded from formal financial systems. Limited access to credit, unstable cash flow, and exposure to shocks such as illness or climate events make them vulnerable. Traditional measures like revenue or profit do not capture an SME’s true financial well-being. To support SMEs more effectively, there is a need for a holistic measure that reflects resilience, savings habits, and access to finance.

This challenge introduces a data-driven Financial Health Index (FHI) for SMEs - a composite measure that classifies businesses into Low, Medium, or High financial health across four key dimensions: savings and assets, debt and repayment ability, resilience to shocks, and access to credit and financial services. Derived from survey and business data, the FHI offers a more complete picture of financial stability and inclusion.

Participants will build machine learning models to predict the FHI using socio-economic and business data such as traded commodities, export and import activity, demographics, firm size, and location. This data is sourced from four Southern African countries - Eswatini, Lesotho, Zimbabwe, and Malawi. But the relevance of such an index extends to businesses in developing economies all over the world.

By quantifying SME financial health, the challenge supports data-driven policies and inclusive financing strategies. Financial institutions can better assess credit risk, while development partners and governments can identify vulnerable businesses and target support where it is needed most.

Ultimately, the Financial Health Index redefines how SME wellbeing is measured, beyond profits to resilience and opportunity. By predicting how financially healthy a business is today, participants will help shape the tools and insights that enable small enterprises to thrive tomorrow.

## 2. Competition / Dataset Source
[Data.org Financial Health Prediction Challenge](https://zindi.africa/competitions/dataorg-financial-health-prediction-challenge)
## 3. Project Structure
data/
├── Train.csv
├── Test.csv

notebooks/
├── mnnmn.ipynb

outputs/
├── submission.csv

README.md
requirements.tx

## 4. Dataset Description
The dataset includes multiple financial features that describe operational and financial conditions.  
The **training dataset** contains both features and the target variable, while the **test dataset** contains features used to generate predictions.

## 5. Data Preprocessing
Data preprocessing steps include handling missing values, cleaning inconsistent records, and preparing the dataset for model training.

## 6. Feature Engineering
Additional features may be created to improve model performance, including transformations, ratios, or derived indicators from the existing financial variables.

## 7. Model Training
Several machine learning models can be trained and compared to determine the most effective approach for predicting the target variable which is RandomForestClassifier.

## 8. Evaluation Metric
Model performance is evaluated using appropriate metrics suitable for the prediction task.

## 9. Results
The trained model generates predictions for the target variable based on the provided test dataset.

## 10. Installation
To install the required dependencies:

```bash
pip install -r requirements.txt
