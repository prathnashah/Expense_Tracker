📊 Expense Tracker — Flask Web App

A lightweight and visually clean Expense Tracking Web Application built with Flask, SQLite, SQLAlchemy, TailwindCSS, and Chart.js.
The app allows users to record expenses, filter them, visualize spending patterns, and understand their financial habits through interactive charts.

🚀 Features
✅ Add & Manage Expenses

- Add expenses with title, amount, category, and date
  
- View all expenses in an easy-to-read table

- Edit or delete any expense

- Real-time success/error alerts using flash() messages

🔎 Smart Filtering

Users can filter expenses by:

- Start date

- End date

- Category

Filters can be combined. A reset option quickly clears all filters.

📈 Data Visualization (Chart.js)

Two dynamic charts update based on filters:

🥧 Pie Chart — Spending by Category : Shows how much you spent across categories like Food, Shopping, Transport, etc.

📅 Bar/Line Chart — Spending Over Time : Visualizes daily spending to reveal patterns and trends.

🛠 Tech Stack
Backend

- Python

- Flask

- Flask-SQLAlchemy

- SQLite

Frontend

- TailwindCSS

- HTML (Jinja2 Templates)

- Chart.js

⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker

2. Create a virtual environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

3. Install dependencies
pip install -r requirements.txt

4. Run the app
python app.py




se, modify, and distribute.
