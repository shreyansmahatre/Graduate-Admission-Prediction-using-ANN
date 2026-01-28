# Graduate-Admission-Prediction-using-ANN

🎓 GRE Admission Prediction Using Machine Learning
📌 Project Overview

This project predicts the probability of admission of a student into a graduate program based on academic and profile-related factors such as GRE score, TOEFL score, CGPA, university rating, SOP, LOR, and research experience.

The objective is to build a machine learning regression model that can estimate a student’s chance of admission using historical data.

📂 Dataset Description

The dataset contains records of students applying for graduate studies.

🔑 Features:

GRE Score (out of 340)

TOEFL Score (out of 120)

University Rating (1 to 5)

Statement of Purpose (SOP) score (1 to 5)

Letter of Recommendation (LOR) score (1 to 5)

CGPA (out of 10)

Research (0 = No, 1 = Yes)

🎯 Target Variable:

Chance of Admit (range: 0 to 1)

⚙️ Technologies Used

Python

Jupyter Notebook

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

🏗️ Project Workflow

Import Required Libraries

Load the Dataset

Exploratory Data Analysis (EDA)

Data distribution

Correlation analysis

Data Preprocessing

Feature selection

Train-test split

Scaling (if applied)

Model Building

Linear Regression / Multiple Regression (or other ML models)

Model Training

Model Evaluation

R² Score

Mean Squared Error (MSE)

Prediction

Predict admission probability for new data

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone <your-github-repo-link>

2️⃣ Install Dependencies
pip install numpy pandas matplotlib seaborn scikit-learn

3️⃣ Open the Notebook
jupyter notebook Gre.ipynb

4️⃣ Run All Cells

Execute the notebook step-by-step to train and evaluate the model.

📊 Results

The model successfully predicts the chance of admission with good accuracy.

Strong correlation observed between:

GRE Score

CGPA

University Rating

Visualization helps understand feature importance.

🧪 Example Use Case
Input:
GRE Score: 320
TOEFL Score: 110
CGPA: 8.5
Research: Yes

Output:
Chance of Admit: 0.78

🎯 Use Cases

Helps students estimate their admission chances

Useful for educational counseling platforms

Beginner-friendly regression ML project

Great for data science portfolios

🔮 Future Enhancements

Try advanced models (Random Forest, XGBoost)

Hyperparameter tuning

Deploy as a web app (Flask / Streamlit)

Add feature importance visualization
