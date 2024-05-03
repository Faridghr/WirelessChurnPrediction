# WirelessChurnPrediction
This project aims to predict wireless account churn and identify key features driving churn. It is a collaborative effort between data scientists to develop a machine learning model that can help maintain and grow the revenue generating base by taking proactive measures to retain customers.

## The Problems Given to You:
You are collaborating with a fellow Data Scientist on a business-critical wireless account retention project. The project is concerned with modelling contract terminations (i.e., churn) to help maintain and grow the revenue generating base. The goals for the model are to predict wireless churn and take action, such as special offers, to keep accounts.

## Materials Provided:
- **Datasets**: [Link to datasets](dataset)
- **Brief Overview**: Your colleague has provided a brief overview on the project’s objectives.

## Notes on the Materials Provided:
The datasets provided are anonymized product, billing, and demographic data for a set of wireless accounts. The data contains one account identifier (Customer_ID).

Three datasets were extracted from our team’s cloud database:

- `wls_churn_master_target_t1.csv`
- `wls_customer_demographics_t1.csv`
- `wls_billing.csv`

These datasets were initially prepared into features by our team’s feature creation pipeline. The master table (wls_churn_master_target_t1.csv) contains the target field (churn). All other tables can be joined to the master table before modeling.

Your colleague has provided NO data dictionary, but recommends conducting some exploratory data analysis and selecting useful features with filters (e.g., using metrics like correlation/chi-square). Lastly, your colleague points out that there is no separate test dataset, and that you will need to split the sample data into training and test data.

## Project Objectives:
The aim of this project is to predict if a wireless account will churn or not. The business would like you to train and assess machine learning models using the provided sample data. As a secondary objective, the business would also like to understand which features are driving churn.

## Assessment Questions:
1. Review the datasets provided by your colleague. What feedback would you give to your colleague to help them improve any future modelling work?
2. Using the data provided, construct an MVP ML code solution (i.e., the model with the best performance, and the data processing/engineering steps required to build it). 
3. Prioritize the most important solution elements. Explain the reasoning behind decisions to implement or not implement.
Which features are driving churn?
4. Include your Jupyter Notebook with comprehensive analysis in markdown format.

## Project Structure
- **dataset/**: Contains dataset used for the project.
- **src/**: Contains Python scripts for data preprocessing, model training, and evaluation.
- **report/**: Stores [Report](report) files.

## Dependencies
- Python
- NumPy
- Pandas
- Scikit-learn
- xgboost
- Matplotlib
- Seaborn

## Usage
1. Clone the repository: `git clone https://github.com/Faridghr/FraudDetectivePy.git`
2. Navigate to the project directory: `cd FraudDetectivePy`
3. Install dependencies: `pip install -r requirements.txt`
4. Download the dataset and extract it to the `dataset` folder.
5. Run the main script to preprocess data, train models, and evaluate performance: `src/FraudDetectivePy.ipynb`