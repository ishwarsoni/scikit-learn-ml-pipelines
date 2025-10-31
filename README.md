# End-to-End ML Pipeline with Scikit-learn (Titanic Survival Prediction)

This repository demonstrates best practices in Machine Learning engineering by implementing a complete, end-to-end preprocessing and modeling workflow using Scikit-learn Pipelines and ColumnTransformer.

The goal is to predict survival on the Titanic, focusing on how to build robust, scalable ML code rather than maximizing model performance.

## ⚙️ Key Concepts Demonstrated

This project showcases the following essential ML engineering techniques:

1.  **Scikit-learn Pipelines:** Chains multiple processing steps (imputation, encoding, scaling, and model training) into a single object.
2.  **`ColumnTransformer`:** Allows different preprocessing steps to be applied to different subsets of columns (e.g., One-Hot Encoding for categorical features, Scaling for numerical features).
3.  **Data Leakage Prevention:** By fitting the entire pipeline on the training data, we ensure that the test set remains unseen during the preprocessing steps.
4.  **Code Consistency:** Provides a clean, single-call interface for both training and making predictions.

## 📂 Repository Structure

* `pipelines.ipynb`: The main Jupyter Notebook containing all the code for data loading, EDA, pipeline construction, training, and evaluation.
* `titanic.csv`: The dataset used for survival prediction.
* `requirements.txt`: Lists all necessary Python libraries to run the project.

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    cd scikit-learn-ml-pipelines
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Notebook:** Open the `pipelines.ipynb` file in Jupyter or VS Code to step through the code.

## 💻 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook