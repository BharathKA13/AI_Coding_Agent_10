

```markdown
# 🚀 AI Coding Agent

An intelligent **multi-agent AI coding system** that can:

- 🖼 Extract coding problems from images (LeetCode-style screenshots)
- 🧠 Generate optimized Python solutions
- ⚙️ Execute code securely inside a sandbox
- 📊 Explain execution results and errors clearly

Built using **Streamlit + OpenAI + Gemini + E2B Sandbox + Agno Agents**

---

## 🏗 Architecture Overview

```

User Input (Image/Text)
↓
Vision Agent (Gemini)
↓
Coding Agent (OpenAI o3-mini)
↓
Sandbox Execution (E2B)
↓
Execution Agent (Result Explanation)
↓
Streamlit UI

````

This project demonstrates a **true multi-agent workflow** with role-based LLM specialization.

---

## ✨ Features

- ✅ Multi-modal input (Image or Text)
- ✅ Automatic problem extraction from screenshots
- ✅ Optimized Python code generation
- ✅ Secure code execution (E2B Sandbox)
- ✅ Timeout handling (30 seconds)
- ✅ Intelligent runtime error explanation
- ✅ Clean Streamlit UI
- ✅ Modular multi-agent architecture

---

## 🧠 Agents Used

### 1️⃣ Vision Agent (Gemini)
- Extracts coding problem from image
- Converts it into structured natural language format

### 2️⃣ Coding Agent (OpenAI o3-mini)
- Generates optimal Python solution
- Adds documentation and type hints
- Handles edge cases

### 3️⃣ Execution Agent (OpenAI o3-mini)
- Executes generated code
- Explains runtime output
- Diagnoses errors clearly

---

## 🛠 Tech Stack

| Component | Technology |
|------------|------------|
| UI | Streamlit |
| Vision Model | Gemini 2.0 Flash |
| Coding Model | OpenAI o3-mini |
| Execution Environment | E2B Sandbox |
| Agent Framework | Agno |
| Image Processing | Pillow |

---

## 📦 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/ai-coding-agent.git
cd ai-coding-agent
````

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If requirements.txt is missing, install manually:

```bash
pip install streamlit agno openai google-generativeai e2b-code-interpreter pillow
```

---

## 🔑 Required API Keys

You need:

* OpenAI API Key
* Google Gemini API Key
* E2B API Key

These are entered directly in the Streamlit sidebar when the app runs.

---

## ▶️ Running the Application

```bash
streamlit run app.py
```

Then open the local URL shown in your terminal.

---

## 🖼 How to Use

### Option 1: Upload Image

* Upload a screenshot of a coding problem
* The system extracts the problem automatically

### Option 2: Enter Text

* Type a coding problem manually

### Then:

* Click **Generate & Execute Solution**
* View:

  * Generated Python code
  * Execution results
  * Error explanations (if any)

---

## 🔐 Security

* Code runs inside **E2B sandbox**
* 30-second execution timeout
* Prevents infinite loops or unsafe execution
* No direct execution on host machine

---

## 🧩 Project Structure

```
ai-coding-agent/
│
├── app.py              # Main Streamlit application
├── requirements.txt
└── README.md
```

---

## ⚙️ Design Principles

* Role-based LLM specialization
* Clean separation of concerns
* Secure execution isolation
* Graceful error handling
* Modular agent architecture

---

## 🚀 Future Improvements

* Streaming responses
* Multi-file project generation
* Persistent agent memory
* Docker-based fallback execution
* Code quality scoring
* Multi-language support (C++, Java, etc.)
* RAG-based coding assistant
* Deployment on Streamlit Cloud

---

## 📌 Example Workflow

1. Upload LeetCode screenshot
2. Gemini extracts problem
3. OpenAI generates optimal solution
4. Code executes in sandbox
5. Execution agent explains output

---

## 🎯 Use Cases

* Coding interview preparation
* Educational AI tutor
* Automated coding assistant
* AI agent orchestration demo
* LLM multi-agent research

---

## 📜 License

MIT License

---

## 👨‍💻 Author

Built as a Multi-Agent AI System demonstrating:

* Agent orchestration
* Vision-to-Code pipelines
* Secure AI code execution
* Production-grade architecture

---
