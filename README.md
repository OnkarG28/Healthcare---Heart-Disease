# Healthcare - Heart Disease Prediction

This project aims to predict heart disease using machine learning models. The dataset used includes patient information such as age, sex, chest pain type, and various medical metrics.

## Project Structure

- **datasets/**: Contains the dataset used for the analysis and the SQL script to create and populate the MySQL database.
- **models/**: Contains the saved machine learning model (Random Forest) with an AUC of 1.
- **notebooks/**: Contains the Jupyter Notebook with the data analysis, model training, and evaluation.
- **scripts/**: Contains Python scripts for analysis (if applicable).

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Healthcare-Heart-Disease.git
    cd Healthcare-Heart-Disease
    ```

2. Set up a Python environment:
    ```bash
    pip install -r requirements.txt
    ```

3. Load the data into MySQL using the script in `datasets/heart_disease_data.sql`.

4. Run the Jupyter Notebook in the `notebooks` directory to replicate the analysis and model training.

## Datasets

The dataset used is included in the `datasets/` directory as `heart_disease_data.csv`.

## Model

The best-performing model is a Random Forest classifier with an AUC of 1, saved in the `models/` directory as `random_forest_model.joblib`.

## MySQL Queries

The MySQL script `heart_disease_data.sql` can be found in the `datasets/` directory. This script creates the necessary table and loads the dataset into MySQL.

## Analysis

The analysis, including Exploratory Data Analysis (EDA), model training, and evaluation, is documented in the Jupyter Notebook `heart_disease_analysis.ipynb`.

## License

This project is licensed under the MIT License.

## Author

- Onkar Gaikwad - [[GitHub Profile]- https://github.com/OnkarG28]

## Acknowledgments

- Thanks to the open-source community for the tools used in this project.
