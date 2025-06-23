# Placement_Eligibility_app
Campus Placement Dashboard
A dynamic and interactive Streamlit web application that simulates and analyzes student data to determine placement readiness. This tool helps educational institutions and training centers monitor and visualize performance, placement status, soft skills, and more.

📌 Project Overview
This project emulates a placement analytics dashboard using synthetic student data generated via the Faker library. It provides a centralized platform for stakeholders to:

Monitor student progress and eligibility.

Visualize placement trends.

Filter/search candidates based on customizable criteria.

Run insightful SQL queries directly on the data.

📂 Technologies Used
Technology	Purpose
Python	Core programming language
Streamlit	Frontend web framework
SQLite	Lightweight database for structured data
Faker	Generate realistic fake student data
Pandas	Data manipulation & analysis

📊 Key Features
✅ Overview Page
Brief introduction to the dashboard and its functionality.

Project structure and data source info.

🔍 Search & Filter Students
Filter students by name, city, enrollment year, placement status, and company.

Combines students and placements tables into a unified view.

💼 Placement Reports
Metrics for total placed students & average package.

Top hiring companies and package range.

Placement status distribution.

🧮 SQL Queries
Select from 10 predefined insightful SQL queries.

View real-time query results (e.g., gender distribution, avg. age, top placements).

Query execution without showing SQL code to the user.

👤 Creator Info
About the developer with background, tools used, and contact information.

🛠️ Database Structure
Tables:
students – student personal & academic info

placements – mock scores, placement status, company & package

programming – coding proficiency data (language, problems solved, projects)

softskills – assessment scores for communication, leadership, etc.

All data is stored in students.db and created via script using Faker.

📁 Folder Structure
bash
Copy
Edit
├── app.py               # Streamlit app
├── students.db          # SQLite database
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
📦 Installation & Running
bash
Copy
Edit
# Clone the repo
git clone https://github.com/your-username/placement-dashboard.git
cd placement-dashboard

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py
📄 Sample SQL Queries Used
Total number of students

Average age per batch

Top 5 packages offered

Placement status distribution

Programming language popularity
