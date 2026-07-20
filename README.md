Live Demo : https://college-recommendation-system.streamlit.app/

🎓 College Recommendation System

A Machine Learning-based web application that helps students choose the right colleges during counseling by providing personalized recommendations based on rank, category, gender, and branch preferences.

📌 Overview

Choosing a college during counseling is a complex and confusing process for students due to the large amount of cutoff data and multiple decision factors.
This project simplifies the process by using Machine Learning (XGBoost) to analyze historical cutoff data and generate accurate, data-driven recommendations.

🎯 Problem Statement

Students rely on manual cutoff analysis
No prediction of future trends
Difficult to compare colleges
High chances of wrong decisions
Lack of personalized recommendations

💡 Solution

This system:

Takes student inputs (rank, category, gender, branch)

Uses historical data to predict cutoff ranks

Recommends colleges based on prediction

Categorizes chances into:

🟢 High

🟡 Medium

🔴 Low

🚀 Features

🔍 Personalized college recommendations

📊 Cutoff prediction using ML model

🎯 Chance-based classification (High/Medium/Low)

⚡ Fast and interactive UI (Streamlit)

📈 Trend-based decision support

📂 Supports large datasets

🧠 Machine Learning Model

Algorithm Used: XGBoost Regressor

Why XGBoost?

High accuracy
Handles structured data effectively
Efficient for large datasets

🛠️ Tech Stack

Frontend:
Streamlit
Backend:
Python

Libraries:
Pandas
NumPy
Scikit-learn
XGBoost

📊 Dataset

Source: Previous years counseling cutoff data
Duration: 5 years
Size: ~10,000+ records

Features:

College Code
Branch Code
Category
Gender
Closing Rank

⚙️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/college-recommendation-system.git cd college-recommendation-system

2️⃣ Create Virtual Environment (Optional but Recommended)

python -m venv venv venv\Scripts\activate # Windows source venv/bin/activate # Mac/Linux

3️⃣ Install Requirements

pip install -r requirements.txt

4️⃣ Run the Application

streamlit run app.py

🖥️ Usage

Enter your:

Rank
Category
Gender
Preferred Branch
Click Recommend Colleges

View:

Recommended colleges
Predicted cutoff
Chance level
📈 Project Workflow

Data Collection

Data Cleaning & Preprocessing
Feature Selection
Model Training (XGBoost)
Prediction
Recommendation Generation
UI Display

🔄 System Architecture

User Input → Data Processing → ML Model → Prediction → Recommendation Output

📊 Results

High prediction accuracy
Low error (MAE)
Fast response time
Improved decision-making

🚀 Future Scope

Real-time data integration
Mobile application
AI chatbot support
College comparison module
Student reviews and ratings
Advanced ML models

🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit a pull request.

📚 References

XGBoost Documentation
Pandas & NumPy Documentation
Machine Learning Research Papers
Counseling Cutoff Data Sources

👩‍💻 Author

Vyshnavi Sapuru

⭐ Support

If you like this project, give it a ⭐ on GitHub!
