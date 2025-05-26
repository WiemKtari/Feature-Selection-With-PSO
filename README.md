# Feature-Selection-With-PSO

**Breast Cancer Classification with Feature Selection using Particle Swarm Optimization (PSO)** 

This project aims to improve classification performance and model efficiency by applying Particle Swarm Optimization (PSO) for feature selection on the Breast Cancer dataset. We compare the performance of a machine learning model (e.g., Random Forest) trained with all features versus selected features.

**The main objectives of the project are:**

1. Load and preprocess the Breast Cancer dataset.

2. Train a baseline (RandomForest) model using all features.

3. Apply PSO to identify the most relevant subset of features.

4. Retrain the model using the selected features.

5. Optimize hyperparameters (via Grid Search) on the PSO-selected feature set.

6. Evaluate model using accuracy, precision, recall, F1-score, and confusion matrix for each case.

7. Compare training times before and after feature selection.

**Technologies Used**
-Python: Scikit-learn, Pandas, NumPy, PySwarms (for PSO)

**Dataset**
The project uses the Breast Cancer dataset (e.g., Breast.csv), which contains medical diagnostic measurements and a binary target indicating whether the tumor is malignant or benign.

**Optimization Details**

-Feature selection is performed using  PSO.

-The fitness function balances between model accuracy and the number of features.

-Selected features are saved and reused for evaluation and comparison.

**Evaluation Metrics**

Each model is evaluated based on the following metrics:

-Accuracy

-Precision

-Recall

-F1 Score

-Confusion Matrix

-Training Time (before and after PSO)
