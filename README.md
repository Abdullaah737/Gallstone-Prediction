# Gallstone Disease Prediction

This project aims to predict the likelihood of gallstone disease using machine learning models trained on clinical and body composition data.

## Project Structure

- **data/**: Contains the datasets (`dataset-uci.csv`, `dataset-uci.xlsx`) used for model training and evaluation.
- **notebooks/**: Jupyter notebook(s) for data exploration, preprocessing, and model development (`Gallstone model.ipynb`).
- **reports/**: Project report and documentation (`Gallstone_Disease_Prediction_Report.docx`).
- **src/**: Source code for data processing and modeling.

## Dataset

The dataset includes various clinical and body composition features such as:
- Age, Gender, Comorbidities
- Body Mass Index (BMI), Total Body Water (TBW), Fat Ratios
- Blood test results (Glucose, Cholesterol, etc.)
- Gallstone status (target variable)

## Getting Started

1. **Clone the repository**
2. **Install dependencies**  
   Recommended:  
   ```bash
   pip install pandas scikit-learn jupyter
   ```
3. **Run the notebook**  
   Open `notebooks/Gallstone model.ipynb` in Jupyter and follow the steps.

## Results

The model predicts gallstone disease status based on the provided features. See the [report](reports/Gallstone_Disease_Prediction_Report.docx) for detailed results and analysis.
