<div align="center">

# 🧠 Crisis Signal Detector

### Real-Time Mental Health Crisis Detection using Fine-Tuned BERT

An AI-powered Natural Language Processing application that detects crisis-related text using a fine-tuned **BERT** model and provides real-time predictions through an interactive **Streamlit** dashboard deployed on **Hugging Face Spaces**.

<p>

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep_Learning-red?style=for-the-badge&logo=pytorch)
![Hugging Face](https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=for-the-badge)
![BERT](https://img.shields.io/badge/BERT-NLP-success?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-ff4b4b?style=for-the-badge&logo=streamlit)
![Docker](https://img.shields.io/badge/Docker-Container-blue?style=for-the-badge&logo=docker)
![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

### 🚀 Live Demo

**https://huggingface.co/spaces/mshakeelrasheed/crisis-signal-detector**

</div>

---

# 📑 Table of Contents

- Overview
- Features
- Dashboard Preview
- System Architecture
- Technology Stack
- Repository Structure
- Installation
- Usage
- Project Documentation
- Results
- Future Improvements
- Model Information
- Author
- License

---

# 📖 Overview

Crisis Signal Detector is a Natural Language Processing (NLP) application that identifies whether a piece of text contains a potential crisis signal.

The project utilizes a **fine-tuned BERT model** from Hugging Face Transformers to perform binary text classification and provides predictions through an interactive Streamlit dashboard.

This project was developed as the final capstone project during the **NAVTTC-sponsored Artificial Intelligence & Machine Learning Training Program** conducted at **Corvit Systems Bahawalpur**.

---

# ✨ Features

- 🔹 Real-time crisis text detection
- 🔹 Fine-tuned BERT model
- 🔹 Binary text classification
- 🔹 Confidence score prediction
- 🔹 Interactive Streamlit interface
- 🔹 Hugging Face deployment
- 🔹 Docker support
- 🔹 Clean and responsive dashboard

---

# 📸 Dashboard Preview

<p align="center">
<img src="screenshots/dashboard.png" width="900">
</p>

---

# 🏗️ System Architecture

<p align="center">
<img src="screenshots/architecture.png" width="900">
</p>

---

# 🧠 Model Workflow

```text
User Input
      │
      ▼
Text Preprocessing
      │
      ▼
BERT Tokenizer
      │
      ▼
Fine-Tuned BERT Model
      │
      ▼
Softmax Layer
      │
      ▼
Prediction
      │
      ▼
Confidence Score
```

---

# 🛠 Technology Stack

| Category | Technologies |
|-----------|--------------|
| Programming Language | Python |
| Deep Learning | PyTorch |
| NLP | Hugging Face Transformers |
| Model | BERT |
| Web Framework | Streamlit |
| Deployment | Hugging Face Spaces |
| Containerization | Docker |
| Data Analysis | Pandas, NumPy |

---

# 📂 Repository Structure

```text
crisis-signal-detector/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── README.md
├── LICENSE
│
├── model/
│   ├── config.json
│   ├── tokenizer.json
│   └── tokenizer_config.json
│
├── notebook/
│   └── training.ipynb
│
├── presentation/
│   └── CrisisSignalDetector.pdf
│
└── screenshots/
    ├── dashboard.png
    └── architecture.png
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/mshakeelrasheed/crisis-signal-detector.git
```

Move into the project folder

```bash
cd crisis-signal-detector
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

# 🚀 Usage

1. Open the application.
2. Enter any text into the input box.
3. Click **Run Prediction**.
4. View:
   - Prediction
   - Confidence Score
   - Probability Chart

---

# 📄 Project Documentation

The repository includes:

- Project Presentation
- Model Configuration Files
- Source Code
- Notebook
- Screenshots
- Docker Configuration

---

# 📊 Results

The application predicts whether the input text represents a potential crisis signal by using a fine-tuned BERT model.

Outputs include:

- ✅ Crisis / Normal Classification
- ✅ Confidence Score
- ✅ Probability Visualization

---

# ⚠️ Model Weights

The trained model weights (`model.safetensors`) are not included in this repository because they exceed GitHub's file size limit.

The complete deployed application is available on Hugging Face Spaces.

---

# 🔮 Future Improvements

- Multi-language support
- REST API integration
- Explainable AI (XAI)
- Mobile application
- Larger and more diverse datasets
- Continuous model retraining

---

# 👨‍💻 Author

## Muhammad Shakeel Rasheed

**BS Artificial Intelligence**

Islamia University Bahawalpur

### Connect with me

- GitHub: https://github.com/mshakeelrasheed
- LinkedIn:https://www.linkedin.com/in/muhammad-shakeel-rasheed

---

# 📜 License

This project is licensed under the MIT License.

---

<div align="center">

⭐ If you found this project useful, consider giving it a Star.

</div>
