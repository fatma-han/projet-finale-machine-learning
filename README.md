# 🍊 Orange Quality Prediction

## 🧠 Description

This project is a machine learning application that predicts the **quality of oranges** based on physical and/or chemical attributes provided in a `.csv` dataset. It uses **multiple supervised learning algorithms** (MLP, KNN, and Decision Tree) and evaluates their performance using **confusion matrices**, **precision** and **F1-score**.

The project aims to compare the effectiveness of different classifiers and help determine which algorithm is best suited for fruit quality prediction based on tabular data.

---

## 📊 Dataset

- **File name:**  `orange quality data.csv`
- **Format:** CSV 
- **Attributes:** Numerical features representing the characteristics of oranges 
- **Target variable:** Quality class 

---

## 🧰 Technologies Used

- **Language:** Python 3.10+
- **Environment:** Jupyter Notebook 
- **Libraries:**
  - `pandas` – data manipulation
  - `numpy` – numerical operations
  - `matplotlib`, `seaborn` – visualization
  - `sklearn` – machine learning (MLPClassifier, KNeighborsClassifier, DecisionTreeClassifier)
  - `scikit-learn.metrics` – for evaluation (confusion matrix, precision, recall, F1)

---

## 🤖 Machine Learning Models Used

| Model              | Description                                     |
|-------------------|-------------------------------------------------|
| **MLP**            | Multilayer Perceptron Neural Network            |
| **KNN**            | K-Nearest Neighbors                             |
| **Decision Tree**  | Tree-based classifier with explainable splits   |

---

## 📈 Evaluation Metrics

Each model was evaluated using:

- **Confusion Matrix**
- **Precision**
- **F1-Score**
- **Accuracy**
