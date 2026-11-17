# Hackathon-Town-C

🛡️ Hackathon-Town-C (Group N)

Predictive Modeling & Economic Cost-Benefit Analysis for Public Health: COVID-19 Vaccination Uptake

📌 Project Overview

Hackathon-Town-C is a data-driven machine learning and economic optimization project designed to analyze public health survey data, predict COVID-19 vaccination behavior, and evaluate the financial impact of vaccination versus hospitalization costs under specific municipal rules.

🔑 Key Objectives

Exploratory Data Analysis (EDA): Uncover behavioral drivers, demographic trends, and missing data patterns affecting vaccine hesitancy and uptake.

Predictive Modeling: Build and tune robust classification pipelines using training and testing datasets to predict individual vaccination decisions (covid_vaccine).

Economic Cost Optimization: Apply health-economic constants to evaluate intervention strategies and minimize societal/healthcare costs.

⚙️ Hackathon Constants & Financial Parameters

In alignment with the Town C Rules, the following baseline parameters are configured in the pipeline:

Vaccine Dose Cost (COST_VAX): $1,500

Hospitalisation Cost (COST_HOSP): $41,000

📊 Exploratory Data Analysis & Visualization Grid

The project features an automated 2x2 diagnostic visualization grid that evaluates:

Target Distribution (covid_vaccine): Visualizes class balance with exact percentage annotations for uptake vs. non-uptake.

Numerical Correlation Heatmap: Identifies multicollinearity and linear relationships across numerical features (e.g., concern levels, knowledge scores, perceived risk/effectiveness).

Vaccine Uptake by Age Group: Examines demographic disparities in vaccination proportions across different age brackets.

Missing Data Heatmap: Audits missingness across the entire training feature space to guide imputation strategies.

📂 Dataset Information

Training Dataset (dataset_C_training.csv):

Shape: 4,756 rows × 31 columns

Includes features on COVID-19 concern, knowledge, behavioral measures (masks, handwashing, avoidance), opinions on vaccine efficacy/risk, employment sectors, and the target label (covid_vaccine).

Testing Dataset (dataset_C_testing.csv):

Shape: 4,749 rows × 30 columns

Unlabeled holdout set used for final predictions and evaluation.

🚀 Getting Started & Installation

1. Clone the Repository
Bash
git clone https://github.com/UH-HACKATHON-TEAMN/Hackathon-Town-C.git
cd Hackathon-Town-C
2. Install Dependencies
Ensure you have Python 3.8+ installed, then install the required data science libraries:

Bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost

3. Run the Notebook / Pipeline
Open the provided Jupyter Notebook in Google Colab or your local Jupyter environment.

Ensure dataset_C_training.csv and dataset_C_testing.csv are placed in your working directory.

Run Cell 1 to load constants and datasets, followed by Cell 2 to generate the EDA and visualization grid.

📁 Repository Structure

Hackathon-Town-C/
│
├── dataset_C_training.csv       # Training dataset with target labels
├── dataset_C_testing.csv        # Testing dataset for predictions
├── notebook.ipynb               # Main execution notebook (EDA, Preprocessing, Modeling)
└── README.md                    # Project documentation

👥 Contributors & Team

Team: UH Hackathon Team N

