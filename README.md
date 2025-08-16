# Code-Debugging-Assistant
An AI-powered debugging assistant that runs code, captures errors, and uses GPT to suggest fixes.

# 🐛 Code Debugging Assistant

An **AI-powered debugging assistant** that runs code, captures errors, and uses GPT to suggest intelligent fixes.  
Upload your script, and the assistant will execute it, parse errors, and provide corrections in plain language.

---

## 🔹 How It Works

1. **Upload a script**  
   User provides a Python script to be debugged.  

2. **Execution & Error Capture**  
   The system runs the code using a sandboxed Python execution environment.  
   Errors and tracebacks are captured automatically.  

3. **Error Parsing**  
   Extracts the root cause of the error from the traceback.  

4. **GPT-Powered Suggestions**  
   Uses OpenAI GPT to analyze the error and suggest fixes with explanations.  

---

## 🛠️ Components

- **ComputerTool** – for handling uploaded scripts.  
- **Python Execution** – runs the user’s code in a controlled environment.  
- **Error Parser** – extracts error messages and key issues.  
- **OpenAI (GPT)** – suggests corrections and improvements.  

---

## ⚡ Features

- Upload and debug Python scripts instantly.  
- Get **clear explanations** of errors.  
- GPT suggests **fixes with reasoning**.  
- Easy to extend for multiple programming languages.  

---
