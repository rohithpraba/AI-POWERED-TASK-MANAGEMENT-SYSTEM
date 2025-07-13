
# 🤖 AI-Powered Task Management System

This project builds an intelligent task management system using data science and machine learning techniques. The goal is to classify and prioritize tasks based on urgency, importance, and other behavioral signals — helping users stay productive with AI assistance.

---

## 📁 Project Structure

```
├── AI_TASK_MANAGEMENT_SYSTEM.ipynb  # Main notebook with model and logic
├── README.md                        # Project documentation
└── data/                            # (Optional) Directory for input datasets
```

---

## 📌 Objective

* Automate classification of tasks based on priority
* Perform exploratory data analysis (EDA)
* Engineer relevant features from task details
* Build and evaluate classification models to predict task categories
* Provide a foundation for deploying a smart task assistant

---

## 📦 Requirements

Make sure you have the following Python packages installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn gradio
```

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Place the dataset in the appropriate directory or modify the notebook path.
3. Open `AI_TASK_MANAGEMENT_SYSTEM.ipynb` in Jupyter Notebook or VSCode.
4. Run cells sequentially to explore EDA, modeling, and predictions.

---

## 📊 Methodology

* **Data Loading & Preprocessing**:
  * Handle missing values and correct data types
  * Apply label encoding and SMOTE for imbalance
* **EDA**:
  * Analyze task types, urgency, and time to complete
  * Visualize correlations and feature importance
* **Modeling**:

  * Logistic Regression
  * Random Forest
  * XGBoost
* **Evaluation**:

  * Accuracy, Precision, Recall, F1-Score
  * Confusion Matrix
  * ROC-AUC (if applicable)

---

## ✅ Results

* XGBoost was the top-performing model.
* The model successfully classifies tasks based on priority with solid performance.
* Feature importance reveals urgency and deadline proximity as major drivers.

---

## 📈 Business Use Case

* AI-powered systems can assist individuals or teams in managing overwhelming task lists.
* Priority suggestions help users focus on what matters most, improving productivity.
* Can be extended into a full task assistant app with real-time inputs.

---

## 🧠 Future Work

* Deploy using a Gradio or Streamlit web app
* Integrate LLMs for understanding natural language tasks
* Sync with task APIs (e.g., Google Tasks, Trello, Notion)
* Add user feedback loop for continuous learning

---

## 📬 Contact

For questions or suggestions, please contact rohithpraba03@gmail.com
