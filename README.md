📄 README.md for llm-code-evaluator
markdown
Copy
Edit
# 🧠 LLM Code Evaluator (Code Quality Analyzer)

This project is a web-based tool built using **Django**, designed to evaluate the quality of Python code. It uses static analysis tools like **Pylint** and **Radon** to assess coding standards, complexity, and maintainability — all critical when reviewing code generated by Large Language Models (LLMs) or human developers.

## 🔍 Key Features

- ✅ Paste Python code and analyze it instantly
- 🧪 Uses **Pylint** to detect syntax, style, and logic issues
- 📊 Uses **Radon** to calculate cyclomatic complexity and maintainability index
- 📈 See visual and textual breakdowns of how clean and efficient the code is
- 💡 Helps determine *"what good looks like"* in code evaluation

## 🛠 Tech Stack

- **Backend**: Django (Python)
- **Analysis Tools**: Pylint, Radon
- **Frontend**: HTML, Bootstrap (basic styling)
- **Others**: SQLite (if DB used)

## 🚀 Getting Started

### 🧩 Prerequisites
- Python 3.x
- pip

### 📦 Installation

```bash
git clone https://github.com/07Raunak/llm-code-evaluator.git
cd llm-code-evaluator
pip install -r requirements.txt
python manage.py runserver
Then open your browser at:

cpp
Copy
Edit
http://127.0.0.1:8000/


📚 Use Case
This tool is ideal for:

Evaluating code quality from AI-generated suggestions (e.g., ChatGPT, Copilot)

Practicing clean code structure and maintainability

Teaching or benchmarking best practices in coding interviews or coursework

👨‍💻 Author
Raunak Kumar
📧 raunak2002pcc@gmail.com

This project reflects my ability to analyze, critique, and improve code — a key requirement for AI code assistant roles.

yaml
Copy
Edit

--
-

