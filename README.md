EXPLAINABLE AI FOR DIABETIC RETINOPATHY SEVERITY DETECTION


Overview

Diabetic Retinopathy is a major visual complication in diabetic patients, which can lead to irreversible loss of vision if not treated properly. This project aimed at developing an automatic system capable of analyzing fundus images of the retina, grading the severity of diabetic retinopathy, and providing visual explanations to justify the model decisions.

Apart from prediction accuracy, the aim of this work is interpretability, an important factor in clinical and medical decision-support systems.

Problem Statement

Manual screening of the retina is a time-consuming process and requires ophthalmologists who have undergone training. This has resulted in delays in diagnosis, especially in large-scale programs.
This project covers the use of deep learning for:

Grading the severity of Diabetic Retinopathy

Highlighting the important retinal regions that influence the prediction

Dataset

The experiments are conducted on retinal fundus images sourced from the APTOS 2019 Blindness Detection dataset, which categorizes images into five severity levels:

No DR

Mild DR

Moderate DR

Severe DR

Proliferative DR

Basic preprocessing and data organization were performed to ensure consistency and reliability during training and evaluation.

Methodology

The system follows a structured pipeline:

Data Exploration & Preprocessing

Inspection of class distribution

Image normalization and resizing

Handling class imbalance using weighted loss

Model Training

A convolutional neural network architecture was used for feature extraction and classification

Multi-class classification was performed across five DR severity levels

Evaluation

Performance evaluated using accuracy and macro F1-score

Validation used to monitor generalization behavior

Explainability

Visual explanation techniques (Grad-CAM) were applied

Heatmaps highlight retinal regions contributing to the model’s decision

Results

The model demonstrates reasonable performance in distinguishing between different DR severity levels.
More importantly, the explainability component provides transparent visual insights, helping to bridge the gap between automated predictions and clinical trust.



Disclaimer

This project is intended for educational and research purposes only and is not a replacement for professional medical diagnosis.

Author

Muhammed Sinan
