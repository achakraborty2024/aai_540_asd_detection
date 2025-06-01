## Project Background
Autism Spectrum Disorder (ASD) affects communication and behavior. Early identification and intervention can significantly improve outcomes. This project aims to identify individuals who may be at higher risk for ASD based on commonly collected screening data (e.g., questionnaire responses, basic demographic information).

## Objective
The goal is to create a ML Ops tool that can do early detection for potential cases towards further clinical assessment, potentially speeding up the screening process and directing resources more effectively. This tool will predict the likelihood of an individual having Autism Spectrum Disorder (ASD) based on screening questionnaire data and demographic features, aiming for high sensitivity (recall) to minimize missed cases. This is a supervised binary classification problem (ASD vs. No ASD).

## Technical Background:
The model will use data from screenings to learn patterns in these features to distinguish between individuals diagnosed with ASD and those without.Technical challenges may involve preprocessing potentially imbalanced data, and ensuring fairness across different demographic groups by analyzing key metrics.

## Model Evaluation:
Evaluation will focus on classification performance metrics relevant to screening:

#### Primary Metrics: 
  - Recall (Sensitivity), AUC, PRC, Accuracy, Precision, F1-Score

#### Secondary Metrics: 
  - DIR, Relative Error, Force Plots. Correlation Plots.

#### Business/Clinical Relevance: 
  - Quantify the model's potential impact by simulating its use on a test set: calculate the percentage of true positive cases identified within the top X% of model predictions (e.g., top 20%), representing potential to accelerate workload for clinicians focusing on these high-risk individuals.
