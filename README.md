# AI Fluency Task – Day 1 🤖

This project is part of the **AI Fluency Task – Day 1**, focused on building and working with an AI-powered application using Python.

## 📌 Project Overview

The project demonstrates a Python-based AI workflow with components for:

* AI agent interaction
* Chatbot functionality
* Challenge/task handling
* Configuration management
* Tool integration
* Workflow execution

## 🛠️ Technologies Used

* **Python**
* AI/LLM APIs
* Environment Variables
* Python Virtual Environment
* Git & GitHub

## 📂 Project Structure

```text
AI-FLUENCY-TASK-DAY1/
│
├── agent.py
├── challenge.py
├── chatbot.py
├── check_setup.py
├── config.py
├── tools.py
├── workflow.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── output/
    └── Screenshots
```

## ⚙️ Setup

### 1. Clone the repository

```bash
git clone https://github.com/nishanth183/AI-FLUENCY-TASK-DAY1.git
cd AI-FLUENCY-TASK-DAY1
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure environment variables

Create a `.env` file in the project directory:

```env
GROQ_API_KEY=your_api_key_here
```

⚠️ **Never upload `.env` or API keys to GitHub.**

The `.env` file is excluded using `.gitignore`.

## ▶️ Running the Project

After activating the virtual environment and installing the dependencies, run the required Python file:

```bash
python workflow.py
```

You can also run the individual components depending on the task:

```bash
python agent.py
python chatbot.py
python challenge.py
```

## 📸 Output

Screenshots and generated outputs are stored in the `output/` directory.

## 🔐 Security

API keys and sensitive credentials should be stored in environment variables rather than directly inside source code.

The following files/directories should not be committed:

```text
.env
.venv/
__pycache__/
*.pyc
```

## 👨‍💻 Author

**Nishanth M**

B.E. Computer Science and Engineering
Bannari Amman Institute of Technology

---

⭐ This repository contains the implementation and learning work completed for **AI Fluency Task – Day 1**.
# AI-FLUENCY-TASK-DAY1
