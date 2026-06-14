# student_performance_model
A Machine Learning project that uses a Decision Tree Classifier to predict student academic outcomes based on their attendance, continuous assessment (CA), and final university exam (UE) marks. Built with Python, Pandas, and Scikit-Learn.

## 📊 Dataset & Features
The model trains on a student dataset (`students.csv`) using the following features:
* **`attendance`**: Class attendance records.
* **`ca`**: Continuous Assessment scores (test/quiz marks during the semester).
* **`ue`**: University Examination marks (final exam scores).

**Target Variable:**
* **`outcome`**: The final academic result (e.g., Pass/Fail ).

## 🛠️ Tech Stack
* **Python 3**
* **Pandas** (Data loading and manipulation)
* **Scikit-Learn** (Model training, data splitting, and accuracy evaluation)

## 🚀 How It Works
1. Loads and processes the student data.
2. Splits the dataset into **80% training** and **20% testing** sets.
3. Trains a `DecisionTreeClassifier` to find patterns in student grades and attendance.
4. Evaluates the model accuracy against the test dataset.
5. Predicts outcomes for new, unseen student data.
