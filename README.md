# 💼 Employee Salary Prediction Web App

A machine learning-powered Streamlit web application that predicts employee salaries based on inputs like experience, education level, and job type. This project also features model comparison, batch prediction, and interactive visualizations.

---

## 🚀 Features

- Predict employee salaries using trained ML models
- Compares models (Linear Regression, Decision Tree, Random Forest, etc.)
- Batch prediction from CSV uploads
- Clean, user-friendly Streamlit UI
- Deployed locally using ngrok for remote access

---

## 🧠 Technologies Used

- **Python**
- **Pandas, NumPy, Scikit-learn**
- **Matplotlib, Seaborn, Altair**
- **Streamlit** (for UI)
- **Joblib** (for model saving/loading)
- **Ngrok** (for deployment)

---

## 🏗️ Project Structure

Employee-Salary-Predictor/
│
├── app.py # Streamlit frontend app
├── model_training.ipynb # Jupyter notebook to train and evaluate models
├── best_model.pkl # Saved ML for deployment
├── sample_batch.csv # Sample file for batch predictions
├── README.md # Project documentation


---

## 📦 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Employee-Salary-Predictor.git
cd Employee-Salary-Predictor

2. Install Required Libraries

Make sure you're in your virtual environment or Anaconda environment:

pip install -r requirements.txt

If requirements.txt is missing, install manually:

pip install streamlit pandas numpy scikit-learn matplotlib seaborn altair joblib

3. Launch the App Locally

streamlit run app.py

Or use a custom port:

streamlit run app.py --server.port 8080

4. Optional: Deploy with Ngrok

    Note: The file best_model.pkl must be present in the same directory as app.py.

📊 Model Training

To retrain or update the model:

    Open model_training.ipynb in Jupyter Notebook

    Train models on your dataset

    Save the best model as best_model.pkl

import joblib
joblib.dump(best_model, "best_model.pkl")

🧪 Sample Input for Batch Prediction

Use the included sample_batch.csv file to test the batch prediction functionality.

experience,education,job
3,Bachelor,Data Analyst
5,Master,Software Engineer
...

🎓 Internship Acknowledgment

This project was successfully completed under the IBM SkillsBuild AI Internship Program, conducted by Edunet Foundation through AICTE.

The internship enhanced my practical knowledge in AI/ML, project workflows, and real-world problem solving.

🙋‍♀️ Author
Vaishnavi Raut
Reach out for feedback, queries, or collaborations.

