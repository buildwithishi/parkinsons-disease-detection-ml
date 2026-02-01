# 🧠 Parkinson’s Disease Detection using Machine Learning

Parkinson’s Disease Detection is a **machine learning–based predictive system** that identifies whether a patient is affected by **Parkinson’s Disease** using biomedical voice measurement features. The project leverages a **Support Vector Machine (SVM)** classifier to deliver accurate and well-generalized predictions based on structured patient data.

---

## Overview

This project implements an end-to-end **supervised learning pipeline** for binary medical classification. Patient data is preprocessed, analyzed, and used to train an SVM model capable of distinguishing between Parkinson’s-positive and healthy individuals. The system demonstrates strong generalization by achieving comparable training and testing performance.

---

## Key Features

- Binary classification of Parkinson’s Disease (Positive / Negative)  
- Machine learning pipeline using Support Vector Machine (SVM)  
- Structured medical dataset processing and feature handling  
- Reliable generalization with minimal overfitting  
- Suitable for educational and research-oriented use cases  

---

## Dataset

- **Source:** Kaggle – Parkinson Disease Detection Dataset  
- **Link:** https://www.kaggle.com/datasets/debasisdotcom/parkinson-disease-detection?resource=download  
- **Description:** Biomedical voice measurements collected from patients, labeled with Parkinson’s Disease status  

---

## Tech Stack

- Python  
- scikit-learn for model training and evaluation  
- NumPy and Pandas for data processing  
- Google Colab for experimentation and execution  

---

## System Architecture

1. Dataset is loaded and explored for patterns and inconsistencies  
2. Data is cleaned and relevant features are selected  
3. Features are scaled and prepared for model training  
4. SVM classifier is trained on labeled patient data  
5. Model is evaluated on unseen test data  
6. System predicts Parkinson’s Disease status for new inputs  
<p align="center">
  <img src="https://github.com/user-attachments/assets/4ba198f8-eb01-4949-b71f-8cedefb1eb0e" width="400" />
</p>



---

## Usage

The model takes structured patient feature data as input and outputs a prediction indicating whether the patient is **Parkinson’s-positive** or **healthy**. This project is primarily intended for learning, experimentation, and demonstration of ML concepts.

---

## Example Use Cases

- Academic study of healthcare-related ML applications  
- Demonstration of supervised classification techniques  
- Early-stage disease prediction research (non-clinical)  
- Feature analysis and model evaluation practice  

---

## Results

- Achieved **similar training and testing accuracy**, indicating good model generalization  
- Demonstrated effectiveness of SVM for structured biomedical data  

---

## Future Enhancements

- Experiment with additional classifiers (Random Forest, XGBoost, Neural Networks)  
- Hyperparameter tuning using GridSearchCV  
- Add performance metrics (precision, recall, ROC-AUC)  
- Build a simple web interface for model inference  
- Extend to multi-class or severity-level prediction  

---

## Project Type

**Academic / Personal Project**  
Built to demonstrate practical understanding of **machine learning in healthcare**, **classification algorithms**, and **model evaluation techniques**.

---

## Author

**Ishika Singha**  
B.Tech CSE (AI & ML)

---

## Acknowledgements

- Kaggle  
- scikit-learn  
- Open-source machine learning community  
