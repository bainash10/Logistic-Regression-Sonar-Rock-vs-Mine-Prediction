This machine learning project focuses on classifying sonar signals to determine whether an object is a **rock** or a **mine**. Using **logistic regression**, the model analyzes 60 features representing the strength of sonar signals reflected off different surfaces. The primary objective is to build a reliable binary classifier capable of distinguishing between the two object types based on these signal patterns.

## Project Objective

The aim of this project is to implement a logistic regression model that can accurately classify sonar returns as either rocks or mines. 

## What Was Done

- Loaded and examined the structure of the sonar dataset to understand the features and target labels.
- Split the data into training and testing sets for unbiased model evaluation.
- Trained a logistic regression model using the training data.
- Evaluated model performance using accuracy, precision, recall, and F1 score on both training and testing datasets.

## Evaluation Metrics

### Training Data:
- **Accuracy:** 0.84  
- **Precision:** 0.86  
- **Recall:** 0.78  
- **F1 Score:** 0.82  

### Testing Data:
- **Accuracy:** 0.86  
- **Precision:** 0.94  
- **Recall:** 0.75  
- **F1 Score:** 0.83  

## Final Outcome

The logistic regression model performed consistently well on both the training and testing sets, with balanced precision and recall scores. This indicates that the model generalizes effectively and can serve as a dependable solution for object detection in sonar-based applications.

**Developed by:** Nischal Baidar
