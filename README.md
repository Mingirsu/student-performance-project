# 📊 Student Performance Prediction

This project analyzes and predicts student exam performance based on lifestyle and behavioral factors using machine learning.

## 📁 Dataset
A synthetic dataset of 1,000 students with over 15 features such as:
- Study hours, sleep, Netflix/social media usage
- Diet quality, mental health, attendance
- Final exam scores

## 🔍 Techniques Used
- Exploratory Data Analysis (EDA)
- KMeans Clustering
- Ridge Regression (with Optuna hyperparameter tuning)
- Feature Importance analysis

## 💡 Results
- Best model: Ridge Regression (alpha ≈ 0.01)
- RMSE ≈ 5.15 | R² ≈ 0.89
- Study hours and mental health were top predictors of performance

## 🚀 How to Run
# 1. Clone the repository (or download the ZIP)
git clone  https://github.com/Mingirsu/student-performance-project.git
cd student-performance-project

# 2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate        # On Linux/macOS
venv\Scripts\activate           # On Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch the notebook
jupyter notebook student_habits.ipynb
💡 Ensure you have Jupyter Notebook installed. If not:
pip install notebook
