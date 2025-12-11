# Breast-Cancer-Tumor-Classification
We aim to build a machine learning model that predicts whether a breast tumor is benign or malignant using publicly available breast cancer data from the Diagnostic Wisconsin Breast Cancer Database.
# Breast Cancer Malignancy Prediction

Short: Train models on the Diagnostic Wisconsin Breast Cancer dataset and interact with a small Streamlit app to make predictions and view visualizations.

## Setup

1. Clone repository.
2. Place `wdbc.xlsx` (uploaded Excel) into `data/` directory.
3. Create a venv and install requirements:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
