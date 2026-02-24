📊 VendorIQ — Smart Vendor Scoring & Recommendation Platform

VendorIQ is an intelligent vendor evaluation and recommendation system that uses data-driven scoring, analytics, and machine learning to help businesses score, compare, and select the best vendors efficiently and reliably.

This platform empowers procurement, supply chain, and vendor management teams with insights to make better sourcing decisions based on performance, risk, cost, and strategic alignment.

🚀 Key Features

✨ Automated Vendor Scoring
Calculate vendor performance scores using configurable criteria like quality, delivery, cost, compliance, sustainability, etc.

📊 Customizable Scorecards
Define your own scoring weights and KPIs for vendor evaluation.

📈 Responsive UI
Automatically adjusts its layout, content, and elements to fit different screen sizes and devices.

🔍 Analytics Dashboard
Interactive visualizations for vendor comparisons, trends, and smart insights.

🤝 Vendor Profiles & History
Maintain detailed profiles with performance history, contracts, and scorecards.

🔐 Secure & Extendable
Role-based access control, modular architecture for easy enhancements.

🧠 How It Works

VendorIQ ingests data from various sources such as:

Vendor performance reports

Procurement systems

Historical delivery/quality logs

Compliance and regulatory sources

The engine then:

Preprocesses and normalizes vendor data

Applies scoring logic based on weighted KPIs

Generates holistic vendor scorecards

Outputs recommendations and dashboards

🛠️ Tech Stack
1. Frontend
 HTML, CSS, JavaScript
2. Backend
Python (Django)
3. Database
SQLite3 (db.sqlite3) - Lightweight and Fast
4. Security
HTTPS, env‑stored secrets, Django auth/permissions

Clone the repository

git clone https://github.com/your-org/VendorIQ-Smart-Vendor-Scoring-Recommendation-Platform.git
cd VendorIQ-Smart-Vendor-Scoring-Recommendation-Platform

Backend Setup (Django)
# Go to project folder
cd vendoriq

# Activate virtual environment (if created)
venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py makemigrations
python manage.py migrate

# Run server
python manage.py runserver



Frontend setup

cd frontend
npm install
npm run dev


Database

Configure Postgres/MongoDB

Run migrations (if applicable)

🧪 Demo
Check the Screenshots of the project in the "ss of project VendorIQ" in this repository.
