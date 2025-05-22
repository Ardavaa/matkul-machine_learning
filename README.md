# Machine Learning Course Assignments

This repository contains a series of assignments for a machine learning course, covering various concepts and algorithms. The assignments demonstrate practical applications of data cleaning, classification, and predictive modeling techniques.

## Repository Structure

The repository is organized into folders, each corresponding to a specific assignment or project stage:

## Assignments

Each folder contains a Jupyter Notebook (`.ipynb`) with the Python code, relevant data files, and often a report document (`.docx` or `.pdf`) detailing the assignment.

*   **`1_data_cleaning/`**: This assignment focuses on data cleaning and preprocessing. It involves loading the `CAD alizadeh.xls` dataset, handling missing values, encoding categorical features, and normalizing numerical features to prepare the data for machine learning tasks.
*   **`2_naive_bayes/`**: This assignment likely implements or applies the Naive Bayes classification algorithm. It probably uses the cleaned dataset from the first assignment to predict outcomes based on the features in the CAD dataset.
*   **`3_random_forest/`**: This assignment likely explores the Random Forest algorithm, an ensemble learning method. It would use the prepared dataset to build a predictive model, potentially for classification or regression tasks related to the CAD data.
*   **`4_neural_networks/`**: This assignment delves into Neural Networks. It involves constructing and training a neural network model using the dataset, aiming to achieve a high accuracy in its predictions.

## Dataset

The primary dataset used across these assignments is **`CAD alizadeh.xls`**. This dataset appears to contain medical data related to Coronary Artery Disease (CAD), with various patient attributes that are used for analysis and model training.

## How to Use/Run

Each assignment is primarily contained within a Jupyter Notebook (`.ipynb`). To run these notebooks:

1.  Ensure you have Python installed on your system.
2.  Install Jupyter Notebook or JupyterLab:
    ```bash
    pip install notebook
    # or
    pip install jupyterlab
    ```
3.  Install the necessary Python libraries. Common dependencies include:
    ```bash
    pip install pandas scikit-learn
    ```
    Individual notebooks might have other specific library requirements mentioned within them.
4.  Navigate to the assignment folder in your terminal and launch Jupyter:
    ```bash
    cd path/to/assignment_folder
    jupyter notebook
    # or
    jupyter lab
    ```
5.  Open the `.ipynb` file from the Jupyter interface to view and run the code.
