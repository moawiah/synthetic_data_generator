# 🧠 Synthetic Data Generator

A Python-based tool to generate structured, synthetic job postings using open-source LLMs from Hugging Face.  
This project supports both **script-based execution** and an **interactive Colab notebook**, making it ideal for rapid prototyping, dataset bootstrapping, or demonstrating prompt engineering techniques.



![Demo Screenshot](https://github.com/user-attachments/assets/c0e229ac-ddb7-4a37-8088-f04ca735cd81)


This tool helps:
- Researchers create labeled training data for NLP classification or QA
- HR tech startups prototype recommendation models
- AI instructors demonstrate few-shot prompting in class

  
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


## Example Output - 1 Job

```JSON
{
"title": "Software Engineer"
,
"description": "We are seeking a highly skilled software engineer to join our team and contribute to the development of innovative software solutions. The ideal candidate will have experience in designing, coding, and testing software systems, and will be able to work collaboratively with cross-functional teams. Responsibilities include writing clean, maintainable, and efficient code, as well as actively participating in code reviews and continuous integration processes. This is an excellent opportunity for a self-starter with a passion for technology and a desire to grow in their career."
,
"requirements":[
"0":"Bachelor's degree in Computer Science or related field",
"1":"Minimum of 2 years experience in software development",
"2":"Strong proficiency in Java or C++",
"3":"Experience with agile development methodologies",
"4":"Good understanding of data structures and algorithms",
"5":"Excellent problem-solving and analytical skills"
],
"location":"New York, NY",
"company_name":"ABC Technologies"
}

```


## Future Improvements
🔁 Add support for more job roles and industries

🧠 Model selector from UI

💾 Export dataset as CSV

☁️ Optional integration with LangChain or RAG workflows





