# Chat Assistant with SQLite
This project is a simple chat assistant built using Streamlit that interacts with an SQLite database to answer user queries related to employees and departments. It supports natural language queries and converts them into SQL to fetch real-time data.

## 👨‍💻 Developed by: Ganesh Patel
## 🚀 Features
✅ **Natural Language Que ries**: Accepts user queries in plain English and converts them into SQL statements.

✅ **Real-Time Data Fetching**: Retrieves and displays data from an SQLite database in real time.

✅ **Error Handling**: Gracefully handles errors with clear messages and input validation.

✅ **Interactive UI**: Streamlit interface for a simple and engaging user experience.

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
✔️ SQL Injection Protection: Uses parameterized queries to prevent SQL injection attacks.

✔️ Input Validation: Validates department names and dates to prevent errors.

## 🏗 Code Quality Improvements
🔹 Refactored chat_assistant.py into modular components with separate helper functions for database queries.

🔹 Enhanced error handling for unexpected inputs.

🔹 Added comments and docstrings to improve code readability.

## 🎨 User Experience Enhancements
🖥️ Clear error messages for better guidance.

🎨 Streamlit UI for a more interactive and user-friendly experience.

📊 Logging functionality to track API usage and errors.

## 🚀 Deployment
This project is deployed on Streamlit Cloud. You can access the deployed version of the Chat Assistant App here: 👉 https://chatassistent.streamlit.app

## 📜 Known Limitations & Future Improvements
⚡ Currently supports a predefined set of queries. Future versions could extend support for more complex natural language processing.

🔒 **Authentication**: Adding user authentication for secure access is a future improvement.

# 🔥 Maintained by: Ganesh Patel
