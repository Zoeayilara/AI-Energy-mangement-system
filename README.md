# AI-Energy-mangement-system
The AI-Powered Energy Management System is designed to optimize energy consumption in commercial facilities by leveraging real-time monitoring, AI-driven insights, and historical data analysis. This system provides facility managers with a dashboard to track energy usage, efficiency, and load distribution, allowing for data-driven decision-making to improve sustainability and cost savings.

Features
✅ User Authentication – Secure login system to manage access.
✅ Real-Time Energy Monitoring – Displays live energy production, consumption, and efficiency.
✅ AI-Driven Insights – Predicts energy usage patterns and recommends optimizations.
✅ Historical Analysis – Tracks past energy consumption trends for better decision-making.
✅ Dark/Light Mode Toggle – Customizable UI for improved user experience.
✅ Sidebar Navigation – Enhanced accessibility with structured menu options.

Installation Guide
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/Zoeayilara/AI-Energy-mangement-system.git
cd EnergyIntelligence project
2️⃣ Create a Virtual Environment (Optional but Recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Set Up the Database
bash
Copy
Edit
python manage.py migrate  # If using Django
flask db upgrade  # If using Flask with SQLAlchemy
5️⃣ Run the Application
bash
Copy
Edit
python manage.py runserver  # For Django
flask run  # For Flask
Now, visit http://127.0.0.1:5000/ (or Django’s default port 8000) in your browser.

Usage Guide
Login using your credentials on the authentication page.
Navigate the Dashboard to view real-time energy metrics.
Analyze Insights provided by AI to optimize energy usage.
Toggle Dark/Light Mode from the Settings page.
Access Historical Data to track long-term energy trends.
Technology Stack
Backend: Python (Flask/Django), SQLite
Frontend: HTML, CSS, Bootstrap, JavaScript
Machine Learning: AI models for energy prediction
Database: SQLite for data storage
Contributing
If you want to contribute:

Fork the repository
Create a new branch (feature-branch)
Commit your changes
Push to your fork
Create a Pull Request (PR)

Contact
For questions or suggestions, feel free to open an issue or contact Ayilara Zoe.

📌 Notes:
Ensure you have Python installed before running the project.
If using Flask, check that the .env file is configured properly.
If using Django, update settings.py with the correct database configurations.
This README follows standard GitHub formatting and makes your project clear, professional, and easy to install. 🚀
