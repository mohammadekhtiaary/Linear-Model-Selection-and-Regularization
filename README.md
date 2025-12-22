# Linear Model Selection and Regularization

This project implements **linear model selection and regularization techniques** in Python, focusing on improving model generalization and controlling overfitting.

The script demonstrates how different regularization methods affect model performance and coefficient behavior, using a structured machine learning workflow.

---

## Objectives

- Implement linear regression models
- Apply **regularization techniques**:
  - Ridge Regression (L2)
  - Lasso Regression (L1)
  - Elastic Net
- Perform model selection
- Compare models based on performance metrics
- Analyze the impact of regularization on coefficients

- ---

## Methodology

### 1. Data Preparation
- Load dataset into memory
- Separate features (`X`) and target variable (`y`)
- Split data into training and testing sets

### 2. Baseline Linear Regression
- Train a standard Linear Regression model
- Evaluate baseline performance

### 3. Regularization Techniques

The script applies and compares:

- **Ridge Regression (L2)**  
  Reduces coefficient magnitude to prevent overfitting.

- **Lasso Regression (L1)**  
  Performs feature selection by shrinking some coefficients to zero.

- **Elastic Net**  
  Combines L1 and L2 penalties for balanced regularization.

### 4. Model Selection
- Tune regularization strength (e.g., `alpha`)
- Compare models using evaluation metrics
- Select the best-performing model

---

## Evaluation Metrics

Depending on the task, evaluation may include:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² score

---

## Technologies Used

- Python 3
- numpy
- pandas
- scikit-learn
- matplotlib (optional for visualization)

---

## How to Run

1. Clone the repository:
```bash
git clone <repository-url>
cd Linear-Model-Selection-and-Regularization
