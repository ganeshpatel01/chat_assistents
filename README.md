# Chat Assistant with SQLite
## Overview
This is a simple chat assistant that interacts with an SQLite database to answer user queries. It is built using Streamlit (previously Flask) and supports various queries related to employees and departments.

# 👨‍💻 Developed by: Ganesh Patel
## 🚀 Features
✅ Accepts natural language queries
✅ Converts queries into SQL to fetch data from an SQLite database
✅ Returns structured responses in real-time
✅ Handles errors gracefully with clear messages
✅ Simple and interactive Streamlit UI

## 🗂 Database Schema
This project uses an **SQLite database** with the following tables:

## Employees Table:
| ID | Name    | Department   | Salary | Hire_Date  |
|----|--------|-------------|--------|------------|
| 1  | Alice  | Sales       | 50000  | 2021-01-15 |
| 2  | Bob    | Engineering | 70000  | 2020-06-10 |
| 3  | Charlie| Marketing   | 60000  | 2022-03-20 |

## Departments Table:
| ID | Name         | Manager |
|----|-------------|---------|
| 1  | Sales       | Alice   |
| 2  | Engineering | Bob     |
| 3  | Marketing   | Charlie |

## 🛠 Supported Queries
"Show me all employees in the [department] department."
"Who is the manager of the [department] department?"
"List all employees hired after [date]."
"What is the total salary expense for the [department] department?"
## 📦 Installation & Setup
## 1️⃣ Clone the Repository:
https://github.com/ganeshpatel01/chat_assistents/
## 2️⃣ Install Dependencies:
pip install -r requirements.txt
## 3️⃣ Run the Streamlit Application:
streamlit run chat_assistant.py
## 🔒 Security Improvements
✔️ Uses parameterized queries to prevent SQL injection.
✔️ Implements input validation to handle incorrect department names and invalid dates.

## 🏗 Code Quality Improvements
🔹 Refactored chat_assistant.py to make it more modular by separating database queries into helper functions.
🔹 Improved error handling for unexpected inputs.
🔹 Added comments and docstrings to enhance readability.

## 🎨 User Experience Enhancements
🖥️ Provides clearer error messages.
🎨 Uses a Streamlit UI for a better chat experience.
📊 Implements logging to track API usage and errors.

## 🚀 Deployment
This project is deployed on Streamlit Cloud. You can access it at: 👉 Chat Assistant App

📜 Known Limitations & Future Improvements
⚠️ Currently supports only a predefined set of queries.
⚡ Can be extended to support more complex natural language processing.
🔒 Add authentication for secure access.

# 🔥 Maintained by: Ganesh Patel
