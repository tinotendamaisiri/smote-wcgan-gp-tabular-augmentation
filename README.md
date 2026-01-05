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
<img width="406" height="287" alt="image" src="https://github.com/user-attachments/assets/eee1138d-d49b-4770-b658-4e04d27c4340" />


#### Generator Architecture
<!-- Paste Generator Code visualization below -->
<img width="433" height="470" alt="image" src="https://github.com/user-attachments/assets/ad0c430d-8e90-4cf6-82cc-7e73b6b03cb5" />


---

### Classification Performance (SVM)
<img width="321" height="100" alt="Classification report SVM" src="https://github.com/user-attachments/assets/8d423ae7-3553-4465-97e3-7d450872eeba" />

#### Confusion Matrix (SVM)
<img width="8000" height="8000" alt="heatmap" src="https://github.com/user-attachments/assets/334f82a6-bc4d-4533-8b37-58dc506acdfb" />

---

### ROC & AUC Analysis
<img width="431" height="305" alt="SVM AUC" src="https://github.com/user-attachments/assets/cf17ac98-0e88-4a22-b550-f397bfe2bd8f" />


#### Logistic Regression ROC Curve
<!-- Paste LR AUC image below -->
![Logistic Regression AUC Curve](images/lr-auc.png)

---

### Model Comparison
<img width="526" height="323" alt="Accuracy Bar Charts" src="https://github.com/user-attachments/assets/c7a4610a-3972-4037-b5b2-0f043fa65343" />


---

## Notes
- All metrics are reported **before and after data augmentation**
- Evaluation includes **Accuracy, AUC, Precision, Recall, and F1-score**
- Visualizations are generated from the experimental pipeline described in the technical paper

---
