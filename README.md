# Melbourne Housing: Data Preprocessing & Imputation 
**Data Science | Python | Feature Engineering | Data Cleaning**

##  Project Overview
In real-world Data Science, datasets are rarely clean. This project focuses on the critical phase of **Data Preprocessing**, specifically addressing the challenge of missing values within the **Melbourne Housing Snapshot** dataset. The goal is to transform "raw, incomplete data" into a "model-ready dataset" through statistically sound imputation methods.

##  Key Technical Features
* **Exploratory Data Audit:** Identifying null value distributions across key features like `BuildingArea`, `YearBuilt`, and `CouncilArea`.
* **Numerical Imputation:** Implementing **Mean/Median** strategies to fill gaps in physical attributes (Landsize, Car spots) while preserving the original distribution.
* **Categorical Handling:** Systematic processing of `CouncilArea` and other non-numerical features to maintain data completeness.
* **Data Integrity Checks:** Post-processing validation to ensure zero null values remain before the dataset is passed to a Machine Learning model.
* **Structured Documentation:** Every step is accompanied by technical justifications for why specific imputation methods were chosen.

##  Technical Stack
* **Language:** Python 3.x
* **Libraries:** * `Pandas`: For complex dataframe manipulation and filtering.
    * `NumPy`: For handling `NaN` values and mathematical operations.
* **Dataset:** [Melbourne Housing Snapshot](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot) (Kaggle).
