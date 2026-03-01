# # Machine Learning Pipeline for Heart Disease Variant Analysis Using ClinVar Data
This repository contains a reproducible Jupyter Notebook pipeline for analyzing heart disease–related variants using ClinVar data. The pipeline implements three supervised machine learning models:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest

The goal is to compare model performance for predicting pathogenicity of heart disease–associated variants.
                                                 *******
## Dataset
The dataset is derived from ClinVar and contains variants linked to heart disease. Due to data sharing restrictions, raw data is not included. Users should obtain the data from ClinVar and place it in the `data/` folder. ** Importing Dataset: https://archive.ics.uci.edu/dataset/45/heart+disease **

                                                 *******
## Repository Structure

clinvar-heart-disease-ml/
├── analysis_pipeline.ipynb # Main ML notebook
├── README.md # This file
├── requirements.txt # Python dependencies
└── data/ # Folder for dataset


                                                 *******


## Methods / Pipeline**

1. Load and clean ClinVar heart disease data
2. Preprocess features
3. Train and evaluate models:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Random Forest
4. Compare model performance using accuracy and other classification metrics

 ## Results

Model performance metrics are displayed in the notebook, including accuracy, confusion matrix, and comparisons between models.

## Reproducibility
Random seeds are set in the notebook to ensure reproducibility of results.

## Citation
If you use this repository in your research, please cite it in your paper.  
GitHub link: https://github.com/Shorouk7/Clinvar-heart-disease-ml




<img width="950" height="658" alt="image" src="https://github.com/user-attachments/assets/b033df51-ea8f-422d-b62d-32637fc52e2c" />
<img width="567" height="432" alt="image" src="https://github.com/user-attachments/assets/a54da2ff-0ba7-4583-bce6-e657fa8f519f" />
<img width="567" height="432" alt="image" src="https://github.com/user-attachments/assets/8fb61232-50c8-40ef-8fd4-ac0bad0adfca" />
<img width="567" height="432" alt="image" src="https://github.com/user-attachments/assets/e8aa8948-9e79-45bf-a444-20e0ff59efb0" />
<img width="498" height="432" alt="image" src="https://github.com/user-attachments/assets/91fbd180-8290-4a92-9f23-a9eab0272f1c" />
<img width="498" height="432" alt="image" src="https://github.com/user-attachments/assets/784d65d0-9a4d-4175-aabc-4f905f3bcdd5" />
<img width="498" height="432" alt="image" src="https://github.com/user-attachments/assets/0d91ddf3-83c2-4b0b-910e-92fac31e88c0" />






