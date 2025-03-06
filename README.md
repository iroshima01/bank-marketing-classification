# bank-marketing-classification
## Logistic Regression and SVM for Bank Marketing Dataset

This project involves implementing **Logistic Regression from scratch** and training an **SVM model** to classify the Bank Marketing Dataset. The goal is to evaluate both models using performance metrics, visualize decision boundaries, and compare results.

---

## **1. Implementation**

### **1.1 Logistic Regression (Implemented from Scratch)**
- Develop a **Logistic Regression** model **without using sklearn or built-in libraries**.
- Implement **gradient descent** to optimize model parameters.
- Train the model on the **Bank Marketing Dataset**.

### **1.2 Support Vector Machine (SVM) Implementation**
- Train an **SVM model** using `sklearn`.
- Compare its performance with the manually implemented Logistic Regression model.

---

## **2. Evaluation and Metrics**
- Evaluate the performance of both models using:
  - **Accuracy**
  - **F1 Score**
  - **Recall**
  - **Precision**
- Compute and analyze the **confusion matrix** for both models.

---

## **3. Visualization**

### **3.1 Logistic Regression Decision Boundary**
- **Feature Selection:** Compute the **correlation** between all features and the target (`y`).
- **Dimensionality Reduction:** Select the **two most correlated features** and train the Logistic Regression model on them.
- **Decision Boundary:**
  - Visualize the class separation boundary in **2D space**.
  - Compare with previous Perceptron Assignment (PA1).
- **Full Feature Classification:**
  - Train Logistic Regression using **all features**.
  - Generate and analyze the **classification report and confusion matrix**.

### **3.2 SVM Decision Boundary**
#### **Step 1: Classification using 2 Features (Highest Correlation with Target)**
- Train the SVM model using the **two most correlated features**.
- **Visualize decision boundaries**.
- Report **classification results, confusion matrix, and classification report**.

#### **Step 2: Classification using 2 Features (Lowest Correlation with Target)**
- Train the SVM model using the **two least correlated features**.
- **Visualize decision boundaries**.
- Report **classification results, confusion matrix, and classification report**.

#### **Step 3: Optimizing SVM with GridSearchCV**
- Train the **SVM model using all features**.
- Use `GridSearchCV` to optimize hyperparameters.
- Report:
  - **Best classification results**
  - **Confusion matrix and classification report**

---
