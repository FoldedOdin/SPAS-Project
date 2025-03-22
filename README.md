# SPAS-Project
📌 Student Performance Analysis System (SPAS)    
SPAS is a web-based system that tracks student performance, predicts future exam scores using Machine Learning, and provides real-time faculty alerts.

🚀 Tech Stack
Backend: Flask (Python), SQLAlchemy (Database ORM)
Frontend: React.js (HTML, CSS, JavaScript)
Database: SQLite (Development), PostgreSQL/MySQL (Production)
Machine Learning: Python (Scikit-Learn, Pandas, NumPy) 

📂 Features

✅ Role-Based Dashboards (Student & Faculty)

✅ Authentication System (Login with ID/Email, Unique ID Generation)

✅ Student Dashboard – View marks, attendance, and predictions

✅ Faculty Dashboard – Add marks, attendance, send alerts, and view performance analytics

✅ Machine Learning Model – Predicts student exam performance

✅ Admin Module – Manage semesters, assign faculty, system announcements

✅ Notifications & Alerts – Auto-alerts for attendance below 75%

✅ Report Generation – Export performance reports as PDF

✅ Profile Management – Upload profile pictures, update details

🔧 Installation & Execution

1️⃣ Clone the Repository

git clone https://github.com/FoldedOdin/SPAS-Project.git

cd SPAS-Project

2️⃣ Backend Setup (Flask + SQLAlchemy)

cd backend

python -m venv venv

source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

python app.py  # Starts Flask server

3️⃣ Frontend Setup (React.js)

cd frontend

npm install

npm start  # Runs the React app

4️⃣ ML Model Training (If Needed)

cd ml_model

python train_model.py 

