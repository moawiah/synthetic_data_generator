# 🧠 Synthetic Data Generator

A simple Python-based tool and Colab demo to generate synthetic data using Hugging Face models. 
This project supports both script-based and notebook-based workflows and is great for bootstrapping AI/ML datasets or prototyping text generation pipelines.

---

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

