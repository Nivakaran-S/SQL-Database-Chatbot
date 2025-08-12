# 🦜 LangChain SQL Database Chatbot — Conversational Data Explorer

## 🚀 Project Overview

This project is an **AI-powered SQL database assistant** built with **LangChain** and **Streamlit** that allows users to query both **SQLite** and **MySQL** databases in **natural language**, no SQL knowledge required.

The chatbot translates user questions into SQL queries, executes them on the connected database, and returns clear, human-readable answers. It’s powered by **Groq’s Llama3-8b-8192** model and showcases skills in **LangChain toolkits, database integration, and conversational AI**.

---

## 💡 Key Features

- **Dual Database Support**  
  - 🗄 **SQLite** (built-in sample `student.db`)  
  - 🛢 **MySQL** (connect to your own database)
- **Natural Language to SQL**  
  - Automatically converts questions into SQL queries and executes them.
- **Groq LLM Integration**  
  - Uses `Llama3-8b-8192` for accurate query generation and answer formatting.
- **LangChain SQL Agent Toolkit**  
  - Handles query construction, execution, and context understanding.
- **Streamlit Chat UI**  
  - Interactive chat interface with persistent conversation history.
- **One-Click History Clear**  
  - Easily reset chat to start fresh.

---

## 🎯 Why This Project?

This project demonstrates **industry-relevant AI + data skills**:

- **LLM-powered database interaction** without writing SQL.
- **Seamless integration** of multiple database backends.
- **LangChain SQLDatabaseToolkit** for query execution.
- **Real-time conversational querying** with context retention.
- **Streamlit front-end design** for non-technical users.

It’s a practical example of building **data accessibility tools**, valuable for analytics teams, BI dashboards, and data-driven products.

---

## 📦 Tech Stack

| Technology               | Purpose                                        |
| ------------------------ | ---------------------------------------------- |
| Python 3.8+              | Core programming language                      |
| Streamlit                | Web application framework                      |
| LangChain                | LLM orchestration and SQL agent tools          |
| Groq LLM API             | Natural language processing & SQL generation   |
| SQLite                   | Local database option                          |
| MySQL                    | External database option                       |
| SQLAlchemy               | Database connectivity                          |
| python-dotenv            | Environment variable management                |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- **Groq API Key** (register at [Groq](https://www.groq.com/))
- For MySQL option: a running MySQL server with credentials

### Installation

```bash
git clone https://github.com/yourusername/langchain-sql-chatbot.git
cd langchain-sql-chatbot

python -m venv venv
source venv/bin/activate  # Windows: .\venv\Scripts\activate

pip install -r requirements.txt
```
Place your student.db SQLite file in the project root or connect to your MySQL database from the sidebar.

### ⚡ Running the App
```bash

streamlit run app.py

```
1. Choose database type from the sidebar:
    - SQLite: Uses included student.db file
    - MySQL: Enter connection details

2. Enter your Groq API Key
3. Ask questions in plain English: no SQL required!
4. View results directly in the chat window.

## 📈 How It Works
1. User Input: Plain English question (e.g., "Show me all students with grades above 80")
2. LangChain SQL Agent: Converts the query into SQL syntax.
3. Database Execution: Runs the SQL query against the chosen DB.
4. Answer Generation: Formats and returns results in a conversational tone.
5. Context Retention: Keeps chat history for follow-up questions.

## 🔍 Example Queries
- "List all students enrolled in the Computer Science department"
- "What is the average grade for Mathematics?"
- "Show the top 5 students by score"

💡 This mini project is part of my AI portfolio to showcase practical LLM-powered database querying solutions for real-world analytics.


