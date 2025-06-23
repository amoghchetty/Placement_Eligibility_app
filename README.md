# Placement_Eligibility_app
 Placement Eligibility App
This project is about creating an interactive data dashboard built using Streamlit and SQLite3, designed to filter students based on placement eligibility criteria and generate actionable insights using SQL queries.

📖 Project Overview
This app simulates student placement records using Faker and visualizes their readiness for placement based on various skill sets. It allows users to:

🔍 Filter students dynamically based on programming skills, soft skills, and placement status

📋 View real-time filtered results through an interactive Streamlit web interface

📊 Extract 10+ meaningful insights using SQL queries (no graphs used here)

🗂 Store and query data using a normalized SQLite3 database

🚀 Features
✅ Eligibility Filtering Dashboard
Set filters for:

Student Name

City

Enrollment Year

Placement Status

Company Name

Dynamically view all matching students in a scrollable table with merged data from multiple tables.

🧠 Insights and Analysis
10 pre-built SQL insights include:

Total number of students

Average student age

City-wise student count

Gender distribution

Batch-wise average age

Top 5 students placed by package

Programming language popularity

Avg. problems solved per batch

Summary of soft skills scores

Placement status distribution

⚙️ Technologies Used
Component	Tool
Data Generation	Faker (Python)
Backend Database	SQLite3
Frontend Interface	Streamlit
Data Handling	Pandas
(Optional) Visuals	Plotly or Altair (if enabled)

▶️ How to Run the Code
1. Clone the Repository:
bash
Copy
Edit
git clone https://github.com/your-username/placement-eligibility-app.git
cd placement-eligibility-app
2. Install Required Packages:
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Streamlit App:
bash
Copy
Edit
streamlit run app.py
4. Open in Browser
text
Copy
Edit
http://localhost:8501
🗃️ Database Schema
The database students.db contains the following normalized tables:

Students: Demographic, academic, and contact information

Programming: Coding performance (language, problems solved, assessments)

SoftSkills: Communication, leadership, critical thinking, teamwork, etc.

Placements: Placement status, company, package, interview rounds

All tables are linked via the student_id field.

