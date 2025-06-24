# Bank-application using docker
# 🏦 Flask-Based Banking Application

## 🎯 Objective
The main objective of this project is to create a simple web-based banking system using Python and Flask that allows users to:
- Create accounts
- Deposit and withdraw money
- Check their balance
- View account statements (placeholder)

It is designed as a beginner-friendly project to practice **web development** and **database integration** using **Flask** and **SQLite**.

---

## 🧰 Tech Stacks Used
- **Programming Language:** Python
- **Web Framework:** Flask
- **Database:** SQLite
- **Frontend:** HTML (rendered using `render_template_string`)
- **Hosting (optional):** Can be deployed using local server or platforms like Replit, Render, or Heroku.

---

## 🔄 Steps Included
1. **Database Initialization**
   - Created a SQLite database (`bank.db`) to store account information.

2. **Flask App Setup**
   - Defined all routes (`/`, `/create`, `/balance`, `/deposit`, `/withdraw`, `/statement`).
   - Used Flask’s `render_template_string()` to serve basic HTML forms and views.

3. **Account Creation**
   - Accepts user name and initial balance.
   - Stores data in the database with unique account ID.

4. **Check Balance**
   - Allows users to check their current balance using their account ID.

5. **Deposit & Withdraw**
   - Deposits/withdraws a specified amount into/from the user's account.
   - Checks for sufficient balance before withdrawal.

6. **Statement (Planned Feature)**
   - Placeholder for future statement functionality.

7. **Styling**
   - Used simple in-page CSS for layout and design.

---

## 💡 Key Insights
- Understood basic CRUD operations with SQLite using Python.
- Learned to structure a Flask web application.
- Gained hands-on experience with form handling in web apps.
- Applied basic web design to make user interfaces more intuitive.
- Practiced clean code organization and commenting.

---

## 📁 Folder Structure
project/
├── app.py (main file)
├── bank.db (auto-generated database file)
└── README.md

yaml
Copy
Edit

---

## ▶️ How to Run the Project Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2.Install Flask (if not installed):
-pip install Flask
3.Run the app:
-python app.py
4.Open in browser:
-http://localhost:5005/





