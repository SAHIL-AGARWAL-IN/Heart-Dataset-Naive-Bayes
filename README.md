# ❤️ Heart Disease Prediction using Gaussian Naive Bayes

This project demonstrates how to build a **Classification model** using Python and scikit-learn to predict whether a person has **heart disease** based on medical attributes such as age, cholesterol level, chest pain type, maximum heart rate, and more.

It is a beginner-friendly machine learning project focused on understanding:

- Data preprocessing  
- Feature–target separation  
- Train-test splitting  
- Gaussian Naive Bayes algorithm  
- Model evaluation metrics  
- Avoiding common classification mistakes  

---

## 📂 Dataset

The dataset used is **heart.csv**, which contains the following columns:

- `age` – Age of the patient  
- `sex` – Gender (0 = Female, 1 = Male)  
- `cp` – Chest pain type  
- `trestbps` – Resting blood pressure  
- `chol` – Cholesterol level  
- `fbs` – Fasting blood sugar  
- `restecg` – Resting ECG results  
- `thalach` – Maximum heart rate achieved  
- `exang` – Exercise-induced angina  
- `oldpeak` – ST depression  
- `slope` – Slope of peak exercise ST segment  
- `ca` – Number of major vessels  
- `thal` – Thalassemia type  
- `target` – Heart disease presence (0 = No Disease, 1 = Disease)  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- scikit-learn  
- Jupyter Notebook  

---

## 🚀 Project Workflow

1. Import libraries  
2. Load the dataset  
3. Explore and understand data  
4. Separate features and target variable  
5. Split data into training and testing sets  
6. Train Gaussian Naive Bayes model  
7. Make predictions  
8. Evaluate model performance  

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd heart-disease-prediction
```

### 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Then open `Untitled.ipynb` and run the cells step-by-step.

---


## 📌 Important Concept: Handling Missing Values

Gaussian Naive Bayes is a probabilistic classification algorithm based on Bayes’ Theorem.

Key characteristics:

-Assumes features are independent
-Assumes features follow a normal (Gaussian) distribution
-Works well with continuous numerical data
-Fast and efficient for small-to-medium datasets

This makes it a strong baseline model for medical classification problems.

---

## 📊 Model Evaluation

The model performance was evaluated using:

-Accuracy Score
-Precision Score
-Recall Score
-Confusion Matrix
-Classification Report

Example:

```python
print("Accuracy:", accuracy_score(y_test, y_pred))
```

---

## 🎯 Learning Outcomes

Through this project, I learned:
-Implementing classification models
-Understanding Naive Bayes assumptions
-Proper feature–target separation
-Avoiding data leakage
-Evaluating classification performance
-Writing structured and clean ML workflows
