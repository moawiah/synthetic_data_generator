# 🧠 Synthetic Data Generator

A Python-based tool to generate structured, synthetic job postings using open-source LLMs from Hugging Face.  
This project supports both **script-based execution** and an **interactive Colab notebook**, making it ideal for rapid prototyping, dataset bootstrapping, or demonstrating prompt engineering techniques.

---

## ✨ Features

- 🔗 Integrates Hugging Face Transformer models
- 📄 Generates realistic job postings in structured JSON format
- 🧪 Supports prompt engineering with control over output length and variability
- 🧠 Minimal Gradio UI for non-technical users
- 📓 Jupyter/Colab support for experimentation and reproducibility

## 📂 Project Structure
<pre> ```
. ├── app/ 
    │ 
    ├── app.py # Main script entry point 
    │ 
    ├── consts.py # Configuration and constants 
    │ 
    └── requirements.txt # Python dependencies 
  ├── data/ 
    │ 
    └── software_engineer_jobs.json # Sample input data (JSON format) 
  ├── notebooks/ 
    │ 
    └── synthetic_data_generator.ipynb # Interactive Colab notebook 
  ├── .env.example # Sample environment variable config 
  ├── .gitignore # Git ignored files list 
  └── README.md
  ``` </pre>

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/moawiah/synthetic_data_generator.git
cd synthetic_data_generator
```
### Install Dependencies
```bah
pip install -r app/requirements.txt
```
### Hugging Face Token
You need to create a `.env` file with your HuggingFace token like `HF_TOKEN=your-token-here`

### Run
run the app using
`python app/app.py`

## Future Improvements
🔁 Add support for more job roles and industries

🧠 Model selector from UI

💾 Export dataset as CSV

☁️ Optional integration with LangChain or RAG workflows

## Demo Snapshot

![image](https://github.com/user-attachments/assets/c0e229ac-ddb7-4a37-8088-f04ca735cd81)


