# Diabetes-Prediction
🩺 Diabetes Prediction Using Machine Learning
This project predicts whether a person is diabetic or not using machine learning with the PIMA Indian Diabetes Dataset.

📁 About the Project
It uses a Support Vector Machine (SVM) model.

Data is preprocessed and scaled using StandardScaler.

The model is trained and tested for accuracy.

You can also enter new data and get a prediction.

📌 Tools Used
Python

Pandas

NumPy

Scikit-learn (SVM, train_test_split, accuracy_score, StandardScaler)

Jupyter Notebook / Google Colab

📊 Dataset Info
Dataset: PIMA Indian Diabetes

Features: Glucose, Blood Pressure, BMI, Age, etc.

Target: 1 = Diabetic, 0 = Not Diabetic

🧪 How it Works
Load and explore the dataset.

Split data into training and testing sets.

Scale the data for better accuracy.

Train the model using SVM.

Test the model and get accuracy.

Take user input and make prediction.

🎯 Accuracy
Training Accuracy: ~78%

Testing Accuracy: ~77%

▶️ Run the Project
Install the required libraries:

bash
Copy
Edit
pip install numpy pandas scikit-learn
Open the .ipynb file in Jupyter or Google Colab.

Run each cell step-by-step.

Try your own input:

python
Copy
Edit
input_data = [5, 116, 74, 0, 0, 25.6, 0.201, 30]
📌 Sample Output
text
Copy
Edit
The person is diabetic ✅
