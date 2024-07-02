# LSTM_XAI_Bankruptcy
This project integrates Long Short-Term Memory (LSTM) networks with Shapley Additive Explanations (SHAP) to enhance the detection of bankruptcy using financial statement data from US companies spanning 1970 to 2021.
This project involves building and comparing different models for bankruptcy prediction. The models included in this project are:
- **LSTM (Long Short-Term Memory)**
- **LDA (Linear Discriminant Analysis)**
- **LR (Logistic Regression)**
- **RF (Random Forest)**
- Additionally, SHAP (SHapley Additive exPlanations) analysis is conducted to interpret the LSTM model.

## Repository Contents

1. **LSTM_Bankruptcy_Final.ipynb**: This notebook contains the code for training and testing the LSTM model.
2. **LSTM Bankruptcy Model Compare_Final.ipynb**: This notebook includes the code for training and testing LDA, LR, and RF models.
3. **LSTM_SHAP_Bankruptcy_Final.ipynb**: This notebook contains the SHAP analysis of the LSTM model.
4. **alldata36.xlsx**: The dataset used for training and testing the models.
5. **LSTM_Model_72_Q36.h5**: The trained LSTM model saved in H5 format.
   
## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries: pandas, numpy, scikit-learn, keras, shap, tensorflow==1.14.0

## Getting the Data

The example dataset used for this project can be downloaded from the following Google Drive link (10% of original dataset) and we rename original name of our feature with X1, X2,X.....:

- [Download Dataset]https://drive.google.com/file/d/1CYNhKvNkQYZ55GPYuLZ4y_lLxTNafi3s/view?usp=sharing

### Usage

1. **LSTM Model Training and Testing**:
    Open the `LSTM_Bankruptcy_Final.ipynb` notebook in Jupyter and run the cells to train and test the LSTM model.
   
2. **Comparing Different Models**:
    Open the `LSTM Bankruptcy Model Compare_Final.ipynb` notebook in Jupyter and run the cells to train and test LDA, LR, and RF models.

3. **SHAP Analysis**:
    Open the `LSTM_SHAP_Bankruptcy_Final.ipynb` notebook in Jupyter and run the cells to perform SHAP analysis on the LSTM model.

### Results

- **LSTM_Bankruptcy_Final.ipynb**: Provides the results and performance metrics of the LSTM model.
- **LSTM Bankruptcy Model Compare_Final.ipynb**: Includes the comparison of performance metrics for LDA, LR, and RF models.
- **LSTM_SHAP_Bankruptcy_Final.ipynb**: Shows the SHAP values and interpretation of the LSTM model predictions.


