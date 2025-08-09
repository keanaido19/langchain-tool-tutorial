# langchain-tool-tutorial

## 📖 Project Overview
The **langchain-tool-tutorial** project follows a guided tutorial on how to create a **LangChain Tool** in Python.  
It uses **LangChain's integration with OpenAI GPT-3.5** and demonstrates the complete process of:
- Building a custom tool.
- Binding the tool to an LLM.
- Invoking the tool through a LangChain chain.

This tutorial is implemented in a **Jupyter Notebook** for an interactive learning experience.

---

## 🚀 Features
- **LangChain + OpenAI Integration**  
  Uses `langchain` with `langchain-openai` to interact with GPT-3.5.
- **Tool Creation Tutorial**  
  Step-by-step process for making a custom LangChain Tool.
- **Binding to LLM**  
  Demonstrates how to attach the created tool to a large language model.
- **Chaining and Invocation**  
  Shows how to execute the tool through a chain for complex workflows.

---

## 🛠️ Technologies Used
- **Python**  
- **LangChain** `0.1.17`  
- **LangChain-OpenAI** `0.1.6`  
- **Jupyter Notebook** for code execution and tutorial flow.

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/keanaido19/langchain-tool-tutorial.git
cd langchain-tool-tutorial
```

### 2. Create a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
Required Python Packages:

    langchain==0.1.17
    langchain-openai==0.1.6
    python-dotenv
    jupyter

### 4. Set Up Environment Variables

Create a .env file in the root directory:
```dotenv
OPENAI_API_KEY=your_openai_api_key_here
```

---

## ▶️ Usage

#### 1. Start Jupyter Notebook:
```bash
jupyter notebook
```

#### 2. Open the provided tutorial notebook (e.g., LangChain_Tool_Tutorial.ipynb).

#### 3. Follow the step-by-step instructions in the notebook.