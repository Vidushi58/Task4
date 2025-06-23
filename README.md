🤖 Spam Detection using Machine Learning
📌 Internship Task 4 — CodTech
This project involves implementing a basic machine learning model to classify SMS messages as spam or not spam using the Naive Bayes algorithm. The solution demonstrates a complete pipeline from data loading and preprocessing to training, evaluation, and visualization.

📁 Project Overview
Task: Classify SMS messages as Spam or Ham using scikit-learn.
Dataset: SMS Spam Collection
Model: Multinomial Naive Bayes (suitable for text classification).

🔧 Technologies Used
Python
pandas, numpy – for data handling
matplotlib, seaborn – for visualization
scikit-learn – for model building and evaluation

🧾 Requirements
Install the required Python libraries:
pip install pandas numpy matplotlib seaborn scikit-learn

▶️ How to Run
Save the code in a Jupyter Notebook or Python file.

Output will include:
1. Sample data preview
2. Confusion Matrix
3. Classification Report

📊 Model Workflow
Data Loading
Loads the dataset from a remote .tsv file containing SMS messages.
Preprocessing
Labels are mapped: "ham" → 0, "spam" → 1
Messages are vectorized using CountVectorizer.
Model Training
A Multinomial Naive Bayes model is trained on the vectorized data.
Evaluation
Confusion Matrix

📦 SAMPLE OUTPUT:
![Image](https://github.com/user-attachments/assets/0adb2da1-a467-499e-b860-567a2c3b25b8)

CONFUSION MATRIX:
![Image](https://github.com/user-attachments/assets/60341ddd-48af-4cdd-82e8-d07e8c0c7988)

