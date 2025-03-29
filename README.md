📌 Spam Email Classifier Project

🚀 Overview

This project focuses on building a Spam Email Classifier using machine learning algorithms. The primary model used is Multinomial Naïve Bayes (MNB), which achieved an impressive 98% accuracy and 99% precision. The project also includes a Streamlit web application for real-time email classification.

Additionally, various famous machine learning algorithms were tested to compare performance, including:

K-Nearest Neighbors (KNN)

Support Vector Classifier (SVC)

Naive Bayes (NB - MNB)

Decision Tree (DT)

Logistic Regression (LR)

Random Forest (RF) – Achieved 100% precision

AdaBoost (ABC)

Bagging Classifier (BgC)

Extra Trees Classifier (ETC)

Gradient Boosting Decision Trees (GBDT)

XGBoost (XGB)

Some models, like KNN, NB, and RF, achieved 100% precision, demonstrating excellent results in identifying spam emails.

📂 Repository Structure

📦 spam-email-classifier
├── datasets/ 

# Contains the email dataset used for training
├── notebooks/

# Jupyter notebooks for experiments and model evaluations
├── models/ 

# Saved trained models for reuse
├── streamlit_app/ 

# Streamlit application for real-time email classification
├── scripts/  

# Python scripts for training, evaluation, and deployment
├── requirements.txt

# List of required dependencies
└── README.md         # Project documentation

🛠 Technologies Used

Python 🐍

Scikit-learn 🤖

Pandas & NumPy 📊

Streamlit 🎨

Matplotlib & Seaborn 📈

📌 How to Use

1️⃣ Clone the Repository

git clone https://github.com/your-username/spam-email-classifier.git
cd spam-email-classifier

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run Jupyter Notebooks

Explore model training and evaluation using the notebooks:

jupyter notebook

4️⃣ Run the Streamlit App

streamlit run streamlit_app/app.py

📊 Model Performance

Algorithm

Accuracy

Precision

MNB (Multinomial Naïve Bayes)

98%

99%

KNN (K-Nearest Neighbors)

97%

100%

NB (Naïve Bayes)

98%

100%

RF (Random Forest)

99%

100%

🔮 Future Improvements

✅ Optimize hyperparameters for better generalization.

✅ Test deep learning models for spam classification.

✅ Deploy as a web application with Flask or FastAPI.

✅ Improve dataset quality by adding more real-world spam emails.

🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit a pull request.

⭐ Support & Feedback

If you find this project useful, please star ⭐ the repository on GitHub and share your feedback!

📌 Author: Your Name (@Saifullah785)📌 GitHub: 
