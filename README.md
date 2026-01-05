# smote-wcgan-gp-tabular-augmentation
Research on hybrid tabular data augmentation using SMOTE and Wasserstein Conditional GAN with Gradient Penalty (WCGAN-GP), applied to employee attrition prediction. Includes a survey of augmentation methods and a technical experimental study.

---

## Experimental Results & Visualizations

This section presents the key visual outputs generated during model training, evaluation, and comparison.  
All figures support the quantitative findings reported in the technical paper.

---

### Model Architecture & Training

#### Model Training Workflow
<!-- Paste Model Training image below -->
![Model Training Workflow](images/model-training.png)

#### Generator Architecture
<!-- Paste Generator Code visualization below -->
![Generator Architecture](images/generator-code.png)

#### Discriminator / Critic Architecture
<!-- Paste Discriminator Code visualization below -->
![Discriminator Architecture](images/discriminator-code.png)

---

### Classification Performance (SVM)

#### SVM Classification Report
<!-- Paste SVM Classification Report below -->
![SVM Classification Report](images/classification-report-svm.png)

#### Confusion Matrix (SVM)
<!-- Paste Confusion Matrix image below -->
![Confusion Matrix - SVM](images/confusion-matrix-svm.png)

---

### ROC & AUC Analysis

#### SVM ROC Curve
<!-- Paste SVM AUC image below -->
![SVM AUC Curve](images/svm-auc.png)

#### Logistic Regression ROC Curve
<!-- Paste LR AUC image below -->
![Logistic Regression AUC Curve](images/lr-auc.png)

---

### Model Comparison

#### Accuracy Comparison Across Models
<!-- Paste Accuracy Bar Chart below -->
![Accuracy Bar Chart](images/accuracy-bar-chart.png)

#### AUC Comparison Across Models
<!-- Paste AUC Bar Chart below -->
![AUC Bar Chart](images/auc-bar-chart.png)

---

### Feature & Distribution Analysis

#### Correlation Heatmap
<!-- Paste Heatmap below -->
![Feature Correlation Heatmap](images/heatmap.png)

---

## Notes
- All metrics are reported **before and after data augmentation**
- Evaluation includes **Accuracy, AUC, Precision, Recall, and F1-score**
- Visualizations are generated from the experimental pipeline described in the technical paper

---
